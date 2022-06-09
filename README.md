# Serial-Killers

De onde vêm os dados? WIKIPEDIA

  Como "recolheram" os dados? Através do KAGGLE
  
  A fonte é confiável? Sim, contudo, como apresenta datas e detalhes de crimes bastante antigos, não temos certeza absoluta que estejam corretos. 
  
  Há alguma outra consideração que tiveram em consideração ao “recolher” estes dados? .............
  
  
“Limpeza” dos dados

  Existem valores “ausentes”? Eles ocorrem em campos que são importantes para os objetivos do projeto? Não.
  
  Existem duplicados? Eles ocorrem em campos que são importantes para os objetivos do projeto? Não.
  
  Quais são os campos mais relevantes para os objetivos do projeto? O nome dos assassinos e as suas vítimas comprovadas ('Name', 'Proven Victims')
  
  Há algum problema de tipo de dados (por exemplo, palavras em campos que deveriam ser numéricos, datas, horas…)? Sim, na coluna das datas em que os assassinos cometeram os crimes. A maior parte deles, são representados da seguinte forma:"x to y".
  
  Como serão corrigidos? .......
  
  Precisam de rejeitar algum dado? Não.
  
  
Contexto sócio histórico

# Contexto

Este conjunto de dados contém uma lista com dados sobre 34 dos serial killers mais periogosos e com **mais crimes cometidos na história da humanidade** desde 1990.
Contém dados **(Name, Country, Active years, Proven victims, Possible victims, Notes)** sobre estes serial killers.

# Bibliografia

Este conjunto de dados é retirado do Dados extraídos do [KAGGLE](https://www.kaggle.com/datasets/vesuvius13/serial-killers-dataset), cujos dados foram retirados da WIKIPEDIA.

# Estrutura

- Highest_victim_count.csv : contém dados (Name, Country, Active years, Proven victims, Possible victims, Notes) sobre os 34 serial killers com maior número de assassinatos no mundo desde 1990. Dados extraídos do [KAGGLE](https://www.kaggle.com/datasets/vesuvius13/serial-killers-dataset)
- Highest_victim_count_EDITADO : contém dados(Name, Country, Year begin, Years end, Proven victims, Possible victims, Notes) sobre os 34 serial killers com maior número de assassinatos no mundo desde 1990. Foi editado para separar os anos em que os assassinos cometeram os crimes. Dados extraídos do [KAGGLE](https://www.kaggle.com/datasets/vesuvius13/serial-killers-dataset)

# API's usados - novas técnicas

# Dicionário de dados

