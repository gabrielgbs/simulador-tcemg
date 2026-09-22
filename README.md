# Simulador de Carreira - Auditor de Controle Externo (TCE-MG)

Simulador web para estimar a evolução salarial e a remuneração líquida de um auditor de controle externo do TCE-MG ao longo da carreira, considerando parâmetros como padrão, ADE, função gratificada, previdência, descontos e projeção inflacionária.

## O que o simulador considera

- Ano na carreira e evolução do padrão
- Pontos de ADE
- Avanço por titulação
- Função gratificada / cargo comissionado
- Projeção de reajuste inflacionário
- Regime de previdência e alíquota Prevcom
- Dependentes para IRPF
- Auxílio-alimentação, auxílio-saúde e auxílio-creche
- Descontos da associação (ASSCONTAS) e outros descontos em folha

## O que o simulador (ainda) não considera

- Desconto do AudTCE-MG
- Férias
- 13º
- Variações no desconto da ASSCONTAS

Caso você queira adicionar esses recursos, fico feliz em receber seu pull-request 😁

## Possíveis problemas

- Pequenas defasagens de R$0,01 nas parcelas, devido a arredondamentos. 
- O cálculo da contribuição do RPPS potencialmente pode ter divergências com o seu contracheque. Por favor me informe caso aconteça com você.

## Como usar

1. Acesse https://gabrielgbs.github.io/simulador-tcemg/.
2. Ajuste os parâmetros no formulário.
3. Consulte a tabela com a simulação por ano.
4. Revise os valores de remuneração bruta, descontos e líquida final.

## Trabalhos futuros (Não necessariamente nessa ordem)

- Modo de comparação, estilo https://taes.com.br (eu vim da carreira de TAES, e essa funcionalidade me faz falta 😅)
- Carreira de Oficial de Controle Externo
- Desconto do AudTCE-MG
- Férias
- 13º

## Observações

- A simulação foi estruturada com base na Lei Estadual nº 25.808/2026.
- O projeto é uma página estática em HTML/CSS/JavaScript, sem dependências externas.
- Os valores podem ser usados apenas como referência para análise e planejamento pessoal.

## Estrutura do projeto

- `index.html` - interface e lógica da simulação
- `README.md` - documentação do projeto

## Observações

- Este projeto é disponibilizado para uso acadêmico e pessoal, sem garantia formal de precisão legal ou contábil.
- Caso você tenha sugestões, críticas, ou encontre um bug, entre em contato comigo pelo Teams.

