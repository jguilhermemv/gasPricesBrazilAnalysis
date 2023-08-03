# Prompts

## Python

- Dado o arquivo em anexo que contém os preços de gasolina no Brasil de 2004 a 2021, sugira no máximo 5 requisitos de negócio para desenvolver um script Python bem simples para analisar esse dados. Não escreva código até o momento. Os requisitos devem levar em conta que o script deve ser implementado em até 30 minutos. Abra o arquivo e identifique a sua estrutura de dados e informações disponíveis para dar a sua resposta.

GPT: Vai dar uma resposta com uma análise do arquivo e com uma lista de requisitos de negócio.

- Transforme os requisitos de negócio { escolha a lista aqui } em requisitos funcionais bem detalhados para os desenvolvedores de software.

GPT: Vai responder com os detalhes dos requisitos funcoinais para o desenvolvimento do software.

- Os desenvolvedores só tem conhecimento em Python, engenharia e análise de dados. E fizeram o seguinte repositório de código para o esqueleto do projeto: https://github.com/jguilhermemv/gasPricesBrazilAnalysis

A estrutura do projeto é a seguinte:

.
├── LICENSE
├── README.md
├── __init__.py
├── datasets
│   └── brazilian_gas_prices_2004-2021.tsv
├── main.py
├── pyproject.toml
└── src

O brazilian_gas_prices_2004-2021.tsv é o arquivo onde os dados estão. Dito isso, crie um plano para arquitetar uma solução para implementação em Python, dos requisitos funcionais detalhados. Lembre-se que é preciso utilizar as boas práticas de engenharia de software como TDD (principalmente), Domain Driven Design e SOLID.

GPT: Irá responder com a criação do plano de arquitetura

- Agora explique como executar a parte {x} do plano.