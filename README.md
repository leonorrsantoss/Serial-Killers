# Serial-Killers :drop_of_blood:

**De onde vêm os dados?** WIKIPEDIA

**Como "recolheram" os dados?** Através do KAGGLE
  
**A fonte é confiável?** Sim, contudo, como apresenta datas e detalhes de crimes bastante antigos, não temos certeza absoluta que estejam corretos. 
  
**Há alguma outra consideração que tiveram em consideração ao “recolher” estes dados?** Fizemos uma breve pesquisa sobre o tema e sobre alguns dos assassinos.
  
  
### “Limpeza” dos dados

**Existem valores “ausentes”? Eles ocorrem em campos que são importantes para os objetivos do projeto?** Não.
  
**Existem duplicados? Eles ocorrem em campos que são importantes para os objetivos do projeto?** Não.
  
**Quais são os campos mais relevantes para os objetivos do projeto?** O nome dos assassinos e as suas vítimas comprovadas ('Name', 'Proven Victims')
  
**Há algum problema de tipo de dados (por exemplo, palavras em campos que deveriam ser numéricos, datas, horas…)?** Sim, na coluna ('Years Active') das datas em que os assassinos cometeram os crimes existem palavras em campos que deviam ser numéricos. A maior parte deles, são representados da seguinte forma:"x to y".
  
**Como serão corrigidos?** No notebook, tentámos dividir essa coluna em duas, de forma a conseguir utilizar os dados numéricos. Posteriormente, eliminámos a coluna de dados original.
  
**Precisam de rejeitar algum dado?** A coluna original ('Years Active'), como mencionado acima.
  
  



## Contexto

Este conjunto de dados contém uma lista com dados sobre 34 dos serial killers mais periogosos e com **mais crimes cometidos na história da humanidade** desde 1990.
Contém dados **(Name, Country, Active years, Proven victims, Possible victims, Notes)** sobre estes serial killers.

## Bibliografia

Este conjunto de dados é retirado do Dados extraídos do [KAGGLE](https://www.kaggle.com/datasets/vesuvius13/serial-killers-dataset), cujos dados foram retirados da WIKIPEDIA.

## Estrutura

- Highest_victim_count.csv : contém dados (Name, Country, Active years, Proven victims, Possible victims, Notes) sobre os 34 serial killers com maior número de assassinatos no mundo desde 1990. Dados extraídos do [KAGGLE](https://www.kaggle.com/datasets/vesuvius13/serial-killers-dataset)

[Highest_victim_count.csv](https://github.com/leonorrsantoss/Serial-Killers/files/8900043/Highest_victim_count.csv)

## API's usados - novas técnicas

## Dicionário de dados

[Dicionário de Dados.csv](https://github.com/leonorrsantoss/Serial-Killers/files/8900131/Dicionario.de.Dados.csv)

