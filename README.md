# desafio-ner
Desenvolva uma solução de named entity recognition para as recomendações do DNIT

## Introdução

Nesse projeto, você é desafiado a implementar um modelo de [named entity recognition](https://en.wikipedia.org/wiki/Named-entity_recognition). 

No final do projeto, você precisa responder as seguintes perguntas:

- Qual é a estrutura do modelo?
- Como você preprocessou e transformou os dados de entrada?
- Como você escolheu um bom modelo para essa tarefa?
- Como aperfeiçoar ainda mais o seu modelo?

## Qual é a estrutura do modelo?

O modelo deve preferencialmente ser desenvolvido com Google TensorFlow. Caso você não possua experiência com TensorFlow, você pode usar outro framework ou mesmo implementar o modelo por você mesmo.
É importante que o modelo seja executável para que possamos reproduzir os seus resultados. Liste as bibliotecas que você usou e se possível, disponibilize um python notebook ou script que possamos executar seu código a partir dele. Lembre-se: reproducibilidade é essencial!

O modelo deve receber como entrada um bloco de texto extraído do PDF e retornar as entidades e suas posições no texto. Fique à vontade pra determinar o formato da saída.

Note que o modelo não precisa modificar o arquivo PDF original para mostrar as entidades. Apenas fornecer uma estrutura de dados com as informações é bastante.

Não se esqueça de informar os hiperparâmetros de treinamento e informar como você fez para ajustar seu modelo aos dados.

## Como você preprocessou e transformou os dados de entrada?

Esse projeto utiliza arquivos em formato PDF com as resoluções do Departamento Nacional de Infraestrutura de Transportes - DNIT.

Elas podem ser encontradas no seguinte endereço: https://www.gov.br/dnit/pt-br/central-de-conteudos/atos-normativos/tipo/recomendacoes

Esses arquivos possuem referências às seguintes entidades:

- Leis, por exemplo: "Lei 8.112/1990", "Lei nº 8.162/1991" ou ainda "Ler 8666/93"
- Instruções normativas: "IN/SEGES/MP nº 05/2018", "Instrução Normativa/DG DNIT nº 8 de 12 de junho de 2018" ou "Instrução Normativa/SEGES MPDG nº 5 de 25 de maio de 2017"

Os arquivos são versões OCR dos documentos originais. Liste os problemas nos dados que você encontrou e o que você fez para lidar com eles.

Neste repositório você pode encontrar apenas a RECOMENDAÇÃO DAF Nº 15/2019 com as entidades acima destacadas:

![image](https://github.com/norelod/desafio-ner/assets/37966960/dcd626d1-baf3-468f-92f9-ff8b350720a5)

![image](https://github.com/norelod/desafio-ner/assets/37966960/40e4b457-5d41-45c3-8597-4160b3cc8295)

Note que nos textos outras entidades podem ser encontradas, como decretos, acórdãos e processos. Essas entidades não precisam ser reconhecidas pelo modelo.

As demais recomendações devem ser obtidas diretamente do site do DNIT.

## Como você escolheu um bom modelo para essa tarefa?

Indique no seu código que métricas você escolheu para selecionar o melhor modelo.

## Como aperfeiçoar ainda mais o seu modelo?

Você ficou satisfeito com o modelo final? O que aconteceria se houvessem mais tipos de entidades para detecção, como decretos e acórdãos?

## Compartilhando seu projeto

Quando você achar que tudo está pronto, nos envie o link do seu repositório para que possamos avaliar seu projeto!

## Ficou com dúvidas?

Qualquer dúvida, não exite em nos enviar suas perguntas!
