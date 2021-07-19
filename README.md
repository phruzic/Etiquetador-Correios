# etiquetador-correios

<div align="center">
  <img alt="NodeJS" src="https://img.shields.io/badge/node.js-%2343853D.svg?style=for-the-badge&logo=node-dot-js&logoColor=white"/>
  <img alt="JavaScript" src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
  <img alt="TypeScript" src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white"/>
</div>

> Gerador completamento dinamico de **etiquetas do Correios**, nesse projeto buscamos mimicar exatamente o mesmo PDF que a API do correios produz utilizando-se de duas bibliotecas:
> 1. PDFKit para a producao de PDFs
> 2. BwipJs para **codigo de barras e QR Code**
> 
<p textalign="right" align="right"> By wh1t3h47 </p>
<p textalign="right" align="right"> Antônio Martos Harres </p>
<p textalign="right" align="right"> https://github.com/wh1t3h47 </p>

# Etiqueta original do correios
> Modelamos nossa etiqueta em cima da etiqueta oficial deles
![Screenshot of etiquetador-correios](https://beeimg.com/images/i48543337921.png)
# Screenshot da nossa etiqueta
> Aqui podemos ver o que geramos com **BwipJs** e **PDFKit**

![Screenshot feito 4 etiquetas](https://i.ibb.co/qYVLmjS/Target.png)
## Desenvolvimento:
![Another screenshot](https://beeimg.com/images/r63492071253.png)

## Como rodar?
### Para instalar, desenvolver, rodar, etc...


`yarn serve # Servir pagina de desenvolvimento`

`yarn install # Para instalar as dependencias`

`yarn tsc && node build/index.js # Rodar build`

## Para desenvolver (Brinde aos devs)
> ### TESTES Manuais:
> Toda vez que eu altero o DrawStream ou uma parte crucial do programa eu testo a etiqueta
`firefox /tmp/lol.pdf # PDF Gerado`
`xdg-open /tmp/lol.pdf`
`chromium /tmp/lol.pdf`
`chrome /tmp/lol.pdf`

> ### Como testar BarCode
> TODO: Documentar pendencias, mas ele gera um tempfile com nome unico
