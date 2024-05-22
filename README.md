# Projeto de conclusão de Machine Learning II
### Integrantes:
#### Luiz Gustavo Queiroz de Aguiar Vasconcelos
#### Jonatan Gomez
#### Júlio Malta
--- 
## Objetivos do projeto:
### - Este projeto tem como finalidade realizar uma análise exploratória  dos dados do **Enem 2023**, para inferir sobre a seguinte questão:
### - Há vantagem de estudantes de escolas privadas sobre os estudantes de escolas públicas?
#### - A disparidade nas notas entre estudantes de escolas públicas e privadas é um tema relevante e urgente. Este projeto visa lançar luz sobre essa discussão.
Muitas vezes, para promover mudanças significativas, é necessário fundamentá-las em evidências sólidas. Este projeto representa um ponto de partida essencial para abordar a desigualdade educacional entre estudantes de escolas públicas e privadas. Ao analisar as notas no ENEM, buscamos não apenas identificar disparidades, mas também fornecer embasamento real para futuros projetos reparativos.

---
## Links e Informações 
O dataset escolhido está disponível no site do MEC, mais especificamente através do link: https://download.inep.gov.br/microdados/microdados_enem_2023.zip

### No zip há também um dicionário para interpretação do banco de dados, que também foi usado para a construção do projeto.

--- 
## Organização
### Utilizamos o Framework **OSEMN** (Obtain, Scrub, Explore, Model, Interpret)
### O projeto está dividido em três arquivos, dos quais são:
1. EDA - Análise inicial e inclusão da problemática.
2. Agrupamento de dados via clustering.
3. ML - Regressão.
   
---

Dicionário de Dados (prévio)
### Colunas Socioeconômicas:
- Q001 e Q002: Escolaridade do pai e mãe respectivamente.
- Q003 e Q004: Grupo que contempla a ocupação (trabalho) do pai e mãe respectivamente.
- Q005: Quantidade de moradores na residência.
- Q006: Faixa da renda mensal familiar, sendo A nenhuma renda, B R$1.320,01 e acrescendo R$660,00 por letra até o P. A letra Q é acima de R$26.400,00.
- Q007: Se na casa trabalha empregado(a) doméstico(a).
- Q010: Quantidade de carros na residência.
- Q011: Quantidade de motos na residência.
- Q012: Quantidade de geladeiras na residência.
- Q019: Quantiadde de televisão na residência.
- Q021: Se possui TV por assinatura.
- Q022: Se possui telefone celular.
- Q024: Se possui computadores.
- Q025: Se possui acesso à internet.

### Dados do participante:
- TP_ESCOLA: Tipo da escola do Ensino Médio. Tendo 3 como privada, 2 como Pública

### Dados da prova:
- NU_NOTA_CN: Nota da prova de Ciências da Natureza
- NU_NOTA_CH: Nota da prova de Ciências Humanas
- NU_NOTA_LC: Nota da prova de Linguagens e Códigos
- NU_NOTA_MT: Nota da prova de Matemática
- NU_NOTA_REDACAO: Nota da prova de Redação
