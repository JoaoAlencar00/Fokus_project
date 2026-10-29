# Fokus

Temporizador de foco desenvolvido com HTML, CSS e JavaScript para praticar manipulação do DOM, eventos e contagem regressiva.

## Recursos

- Ciclos de foco de 25 minutos e pausas de 5 ou 15 minutos.
- Controles para iniciar e pausar a contagem.
- Troca de tema, imagem e texto conforme o ciclo selecionado.
- Controle de música ambiente e efeitos sonoros.

## Tecnologias e organização

- `index.html`: estrutura da interface.
- `styles.css`: estilos e temas.
- `script.js`: eventos, temporizador e reprodução de áudio.
- `imagens/` e `sons/`: recursos visuais e sonoros.

## Como executar

Clone o repositório e abra `index.html` em um navegador. Também é possível servir a pasta com uma extensão como Live Server.

A versão atual usa caminhos absolutos com o prefixo `/Fokus-projeto-base/` em parte das imagens e dos sons, além de `/imagens/pattern.png` no CSS. Esses caminhos precisam corresponder à estrutura do servidor para que todos os recursos carreguem; a execução local pela raiz do repositório pode exibir recursos ausentes.

## Aprendizados

Seletores do DOM, listeners de eventos, alteração de classes e atributos, `setInterval`, controle de estado e uso da API de áudio do navegador.

## Créditos

Projeto educacional desenvolvido por João Alencar com a Alura. A interface representa um produto fictício, sem fins comerciais. Conforme os créditos do projeto, as imagens foram geradas com Adobe Firefly.
