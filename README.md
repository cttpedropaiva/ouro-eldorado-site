# Site Ouro Eldorado

Compra de ouro em Contagem, Minas Gerais. Página única, sem build.

## Como roda

`index.html` é autocontido. Abre com duplo clique ou vai pra qualquer host
estático como está. Não tem `npm install`, não tem passo de compilação.

O que vem de fora:

- **Google Fonts** (Bodoni Moda, Cormorant Garamond, Jost)
- **three.js 0.140.0** via jsDelivr, para a peça de ouro do topo

A logo está embutida no HTML como data URI, então a página não depende de
`assets/` para renderizar. A pasta guarda o arquivo original recortado.

## Deploy na Vercel

Projeto novo na Vercel apontando pra este repositório:

- **Framework Preset:** Other
- **Root Directory:** `/`
- **Build Command:** vazio
- **Output Directory:** vazio

Cada push na `main` publica sozinho.

## Cuidado

Este repositório é público na prática: tudo que estiver aqui fica acessível na
URL do deploy. Briefing, pesquisa, componentes em desenvolvimento e qualquer
material do cliente ficam no MazyOS, em `projetos/Ouro-Eldorado/`, fora daqui.

## Pendências

- Confirmar horário de atendimento com o cliente (o site oficial diverge do Waze e de diretórios)
- Logo em vetor ou PNG com fundo transparente (a atual é dourado sobre preto chapado, aplicada com `mix-blend-mode: screen`)
- Fotos reais da loja, da equipe e do processo de avaliação
- História de fundação: ano, fundador e origem do negócio
- Decidir a variante do material da peça: ouro maciço ou ouro líquido
