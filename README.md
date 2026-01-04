# 📚 Análise de Desempenho Acadêmico com Python

Este projeto foi desenvolvido com base no estudo de caso do canal **Eficiência Programada**, onde analisei uma base de dados educacional para identificar quais hábitos impactam as notas dos alunos.

## 🔍 Principais Insights do Projeto:
* **Horas de Estudo:** Identificamos uma correlação positiva forte (0.83). Alunos que estudam mais de 5h/dia têm médias 100% superiores aos que estudam menos de 2h [00:14:02].
* **Redes Sociais:** Existe uma correlação negativa. Quanto maior o tempo de tela, menor a tendência da nota do aluno [00:08:16].
* **Saúde Mental e Física:** O uso de `boxplots` revelou que uma boa saúde mental e a prática frequente de exercícios estão ligados a melhores medianas de notas [00:23:03].

## 🛠️ O que eu pratiquei:
* **Limpeza e Filtros:** Uso de `pd.cut` para criar faixas de tempo (bins) [00:16:53].
* **Visualização de Dados:** * `sns.heatmap` para matriz de correlação [00:05:32].
    * `sns.lmplot` para linhas de regressão linear [00:10:01].
    * `sns.boxplot` para análise de distribuição e outliers [00:18:14].
* **Estatística Descritiva:** Cálculo de médias, medianas e desvio padrão para comparar grupos de gênero [00:24:15].

---
*Base de dados e inspiração: [Eficiência Programada](https://youtu.be/r2WUzuqleH4)*
