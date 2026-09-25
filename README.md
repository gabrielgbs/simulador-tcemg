# Simulador de Carreira - Auditor de Controle Externo (TCE-MG)

Simulador web para estimar a evolução salarial e a remuneração líquida de um auditor de controle externo do TCE-MG ao longo da carreira, considerando parâmetros como padrão, ADE, função gratificada, previdência, descontos, benefícios e projeção inflacionária.

## Como usar

1. Acesse https://gabrielgbs.github.io/simulador-tcemg/.
2. Navegue pelas abas para alterar parâmetros de carreira, previdência ou adicionais.
3. Consulte a tabela com a simulação por ano.
4. Revise os valores de remuneração bruta, descontos e líquida final.

## O que o simulador considera

- Ano na carreira e evolução do padrão
- Pontos de ADE
- Avanço por titulação
- Função gratificada / cargo comissionado
- Projeção de reajuste inflacionário
- Regime de previdência e contribuição Prevcom
- Dependentes para IRPF
- Auxílio-alimentação, auxílio-saúde, auxílio-creche e outras verbas
- Descontos da associação (ASSCONTAS), SERPRO e outros descontos em folha
- Abate-teto e cálculo de base previdenciária e tributária

## O que (ainda) não está contemplado

- Desconto do AudTCE-MG
- Férias
- 13º
- Variações no desconto da ASSCONTAS
- Modo de comparação, estilo https://taes.com.br (eu vim da carreira de TAES, e essa funcionalidade me faz falta 😅)
- Carreira de Oficial de Controle Externo

Caso você queira adicionar esses recursos, fico feliz em receber seu pull-request 😁

## Funcionalidades implementadas

- Simulação por ano da carreira até o limite do padrão TC-94
- Divisão de parâmetros de cálculo em abas para separar carreira, previdência e adicionais/descontos
- Cálculo de remuneração bruta e líquida final
- Aplicação de reajuste inflacionário projetado
- Ajuste do valor da função gratificada e do ADE conforme parâmetros informados
- Cálculo de IRPF com dedução por dependentes
- Cálculo de Previdência por RPPS ou RGPS, com ou sem Prevcom
- Cálculo de auxílio-creche conforme idade e tipo do auxílio
- Persistência dos dados preenchidos no navegador; ou seja, o navegador se lembra dos seus últimos parâmetros 😉
- Tema claro/escuro
- Ocultação automática de colunas zeradas na tabela para facilitar leitura

## Observações

- A simulação foi estruturada com base na Lei Estadual nº 25.808/2026.
- O projeto é uma ferramenta de estimativa e pode servir como referência para análise e planejamento pessoal.
- Pequenas defasagens de R$0,01 podem ocorrer por arredondamento.
- O cálculo do RPPS pode apresentar divergência em relação ao contracheque real. Por favor me informe caso aconteça com você.
- O projeto é uma página estática em HTML/CSS/JavaScript, sem dependências externas.
- Os valores podem ser usados apenas como referência para análise e planejamento pessoal.
- Caso você tenha sugestões, críticas, ou encontre um bug, entre em contato comigo pelo Teams.

