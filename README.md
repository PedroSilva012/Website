[README.md](https://github.com/user-attachments/files/32685825/README.md)
# TravelsGo

Landing page de uma agência de viagens fictícia, criada com HTML, CSS e JavaScript. A página apresenta destinos, hospedagens, formas de contato e um resumo de como funciona o planejamento de uma viagem.

## O que há na página

- **Cabeçalho fixo:** menu, logotipo e botão de contato. Ao rolar a página, o JavaScript adiciona a classe `rolar` ao cabeçalho, alterando suas cores e o logotipo exibido.
- **Apresentação:** imagem de fundo, mensagem principal e botão “Quero conhecer”.
- **Vantagens:** blocos sobre conforto, destinos e hotéis.
- **Contato:** botões visuais para WhatsApp, e-mail, telefone e formulário.
- **Hospedagens:** chamada com imagem de fundo e botão para conhecer hotéis.
- **Como funciona:** três etapas, do primeiro contato à viagem.
- **Rodapé:** ícones de redes sociais e links informativos.

## Tecnologias

- HTML5 para o conteúdo;
- CSS3 para o visual e os efeitos de hover;
- JavaScript puro para a mudança do cabeçalho ao rolar;
- Google Fonts (Poppins e Titillium Web) e Bootstrap Icons carregados por links externos.

## Estrutura de arquivos

O `index.html` espera a seguinte organização:

```text
projeto/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── menu.js
└── images/
    ├── logotipo.png
    ├── logotipo_p.png
    ├── bg-inicio-site.jpg
    ├── aviao.png
    ├── carro.png
    ├── hoteis.png
    ├── hotel-bg.jpg
    ├── atendimento-ao-cliente.png
    ├── planejamento.png
    └── viagem.png
```

## Como abrir

1. Coloque `style.css` na pasta `css/` e `menu.js` na pasta `js/`, ao lado do `index.html`, conforme a estrutura acima.
2. Adicione à pasta `images/` as imagens com os nomes indicados. **As imagens não estavam entre os três arquivos enviados**, então partes visuais ficarão ausentes até que sejam adicionadas.
3. Abra `index.html` no navegador. Não há instalação nem servidor obrigatório. Para carregar as fontes e os ícones externos, é necessária conexão com a internet.

## Onde alterar cada parte

| Arquivo | Responsabilidade |
| --- | --- |
| `index.html` | Textos, seções, imagens e links. |
| `css/style.css` | Cores, tamanhos, layout, fundos e estado visual do cabeçalho após a rolagem. |
| `js/menu.js` | Adiciona ou remove a classe `rolar` do elemento `#header` conforme a posição da página. |

## Pontos para finalizar

- Os itens do menu, vários botões e os links do rodapé usam `href="#"`; substitua-os pelos endereços ou âncoras corretos antes de publicar.
- O botão “Contato” no cabeçalho aponta para `https://w.app/Frontend`; confirme se é o endereço desejado.
- Os textos `Lorem ipsum` na seção de vantagens ainda são provisórios.
- A seção de contato aparece duas vezes no HTML. Confira se a repetição faz parte do layout desejado.
- O título da aba do navegador ainda é `WEBSITE`; pode ser alterado no elemento `<title>`.

> Este repositório contém uma interface estática. Os botões de contato e de navegação dependem da configuração dos seus links; não há sistema de reservas ou formulário funcional no código enviado.
