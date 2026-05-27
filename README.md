# AdaProjeto2
Projeto Final — Análise do Mercado de Trabalho em Dados
I Para o projeto de conclusão do Módulo 2 – Técnicas de Programação I, iniciamos criando um repositório remoto com uma branch individual para cada integrante do grupo. Em seguida, realizamos a distribuição das tarefas, garantindo que todos pudessem contribuir de forma organizada para o desenvolvimento do projeto. Cada participante também configurou seu repositório local, permitindo o versionamento e a integração contínua do código.

Na etapa seguinte, conduzimos uma análise exploratória dos dados disponíveis no banco de dados fornecido. A partir dessa investigação, respondemos às perguntas propostas e identificamos padrões, inconsistências e informações relevantes. Por fim, consolidamos as conclusões obtidas, estruturando os resultados de forma clara para embasar as decisões e o entendimento geral do projeto.

Integrantes:

João Victor -
Roberto - roblei007
Tereza - tecfccaetano-wq
Dataset: Data Science Salaries 2024 (Kaggle) https://www.kaggle.com/datasets/sazidthe1/data-science-salaries

Perguntas escolhidas:

Progressão salarial por nível de experiência. Qual é o salário médio em cada nível (EN, MI, SE, EX)? A progressão é parecida entre os cargos principais (Data Analyst, Data Scientist, Data Engineer)?

Trabalho remoto compensa? Cargos totalmente remotos pagam mais, menos ou igual aos presenciais? A resposta muda se compararmos por nível de experiência?

Comparativo entre cargos. Comparem Data Analyst, Data Scientist, Data Engineer e Machine Learning Engineer (ou similares no dataset): qual paga mais, qual tem mais vagas, qual tem maior crescimento ao longo dos anos?

Conclusões:

O Salario médio por nível de experiência é:

EN (Entry-level) - 84,448.92 ;
MI (Mid-level) - 119,019.81 ;
SE (Senior-level)- 162,071.06 ;
EX (Executive-level) - 189,687.35
Conforme analise das informações, para os cargos de Data Engineer e Data Science os salários tem a tendência a se eleveram conforme o nivel de experiencia, seguindo a progessão por nível de experiêcia, porem para o cargo de Data Analiyst esta ordem não ocorreu, visto que a média salario dos empregados do nível sênior é superior ao nível executivo.

Em média, uma das modalidades (geralmente Remote) apresenta salários maiores do que as demais (ajustar com base nos resultados reais). A diferença tende a ser mais visível em níveis intermediários e seniores, sugerindo que profissionais mais experientes conseguem negociar melhor em regime remoto. Nos níveis iniciais, a diferença entre modalidades é menor, indicando que o impacto do remoto no salário cresce ao longo da carreira.

Assim, trabalho remoto tende a compensar mais para quem já possui alguma experiência na área de dados.

Salário: O cargo de Machine Learning Engineer apresenta a maior média salarial entre os analisados. Demanda: Data Engineer e Data Scientist possuem o maior volume de registros (vagas), indicando uma demanda consolidada. Tendência: A evolução anual mostra como o mercado tem valorizado cada especialidade ao longo do tempo, permitindo identificar áreas em aquecimento.
Como rodar o projeto localmente:

git clone git@github.com:roblei007/AdaProjeto2.git > git status
Trazendo o branch individualmente: git branch -r > git fetch --all > git chekout -b (nome da branch) origin/(nome da branch)
Enviando as alterações: git add (branch) > git commit -m "alterações" > git push
