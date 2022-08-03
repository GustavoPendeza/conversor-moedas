# Conversor de Moedas

Projeto de conversão de moedas utilizando API do site <a href="https://hgbrasil.com">HG Brasil</a>

## Sobre

Escolha um campo (Real, Dólar ou Euro), escreva o valor desejado e os outros campos serão convertidos automaticamente ao mesmo tempo.

## Tecnologias

<div>
    <img alt="Flutter" title="Flutter" src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white">
    <img alt="Dart" title="Dart" src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white">
</div>

## Tela do App

<div>
    <img alt="Tela App" title="Tela App" height="500em" src="https://user-images.githubusercontent.com/53589614/182686010-c18e9833-34fd-4b4d-a032-635980c495a8.png">
    <img alt="Tela App Convertendo" title="Tela App Convertendo" height="500em" src="https://user-images.githubusercontent.com/53589614/182686068-6a630129-9301-4a30-8c07-80cbe5be36d3.png">
</div>

## Utilização

Coloque sua chave da API do HG Brasil na linha 5 no main.dart:

```bash
# Troque o SUA_CHAVE pela sua chave da API
const request = "https://api.hgbrasil.com/finance?key=SUA_CHAVE";
```