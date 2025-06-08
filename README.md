# Análise de Sentimentos com Language Studio no Azure AI
Repositório com anotações do Laborátorio de Análise de Sentimentos com Language Studio no Azure AI da DIO (Digital Innovation One)

## Análise de texto e resposta a perguntas
A analise de texto de uma IA consegue determinar o idioma predominante em uma frase, observar o sentimento, identificar frases-chave e verificar entidades, no exemplo da primeira aula, França. 
É necessário definir uma base de conhecimento de pares de perguntas e respostas para obter as melhores respostas.

## Serviço de bot do Azure
Já usado a algum tempo como chatbot para atender clientes. Para isso, é necessário utilizar uma base de conhecimento para que o bot tenha a melhor resposta para a dúvida de uma pergunta. Evoluiu de forma que, mesmo que digitamos errado, o bot entende nossa solicitação, antes eram utilizado algo parecido como um "ramal" para entrar em opções de perguntas que o chatbot consegue responder.
O serviço de bot do Azure é uma plataforma baseada em nuvem para desenvolvimento de bots. Possui integração com AI Language e outros serviços e conectividade através de vários canais.

## Compreensão da linguagem coloquial
A linguagem coloquial é a forma cotidiana em que conversamos
1. Declaração - O que eu preciso que você (o bot) faça;
2. Entidade - Identificação de onde eu quero que o dispostivo interaja;
3. Intenção - Identificação da minha necessidade.
O objetivo é dar ordens para dispositivos utilizando a linguagem informal.

### Reconhecimento e síntese de fala
O bot usa recursos de fala para texto do serviço de fala para gerar áudios audíveis com base em um texto. Muito útil para acessibilidade.

## Links úteis
[MSLearn Ai Fundamentals - Transcrições e Conversão de Texto para Áudio](https://aka.ms/ai900-speech)

[MSLearn Ai Fundamentals - Análise de Texto](https://aka.ms/ai900-text-analysis)

## Conhecendo o Estudio de fala
É necessário criar um recurso para iniciar nosso projeto. o recurso de conversão de fala em tempo real necessita de um arquivo de áudio para realizar a transcrição e devemos informar o idioma do áudio.
É possível utiliza-lo em um call center, fazer legendas em tempo real em chamadas, entre outros.

## Conhecendo o Language Studio
O language studio faz análises semanticas de texto e fala conforme linguagem natural. Nos ajuda a interpretar textos e áudio. É necessário criar um recurso. 
No language.cognitive vamos em classificação de texto e em análise de sentimentos.

