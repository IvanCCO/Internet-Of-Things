# Arquitetura para IOT:

Utilizamos um modelo de 5 camadas, onde temos:

| negócios |
| Aplicação |
| processamento |
| Redes |
| Percepção |

O protocolo começando de baixo para cima se explica da seguinte forma:

## Percepção

Camada onde temos o dispositvo em SI, onde o dispositvo captura os dados do mundo externo

## Redes ou abstração

Essa camada é responsável por trazer os dados que são gerados pelo dispositvo IOT e trazer para
camada de "código", onde agora temos Dados em SI.

## Processamento

O tratamento dos dados que fazemos, por exemeplo, capturamos dados com valores numéricos, o dado por
si só não é nada, mas nessa camada nos processamos e dizemos por exemplo que esses dados são o
a latitude e longitude de algum lugar.

## Aplicação

Onde nós mostramos os dados capturados e tratados para o cliente, isso pode ser por meio de uma
aplicação web, por exemplo.

## Negócios

Onde temos as regras do nosso negócio para conseguir gerar valor com nossa aplicação, valor esse
definido por nós mesmos em algum caso.
