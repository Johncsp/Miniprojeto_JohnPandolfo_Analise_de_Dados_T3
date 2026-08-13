# Mini-Projeto Avaliativo - Análise de Dados no Varejo

---

## Sobre este projeto

O objetivo foi pegar uma base de dados e fazer todo o processo de diagnóstico, limpeza, transformação e análise inicial usando Python e a biblioteca Pandas.

---

## Arquivos no repositório

* Miniprojeto_JohnPandolfo_Analise_de_Dados_T3.ipynb: Notebook onde fiz todo o código, dividindo o trabalho em Sprints e comentando cada passo.
* Base Varejo.csv: Base de dados para análise.
* df_limpo.csv: O arquivo de dados final, gerado depois de toda a limpeza e tratamento dos dados.
* Readme.md: Este arquivo com as explicações e instruções do projeto.

---

## Como rodar o código

1. Baixe os arquivos deste repositório para o seu computador.
2. Certifique-se de ter o Python instalado com a biblioteca pandas.
3. Deixe o arquivo Base Varejo.csv na mesma pasta onde está o notebook.
4. Abra o arquivo Miniprojeto_JohnPandolfo_Analise_de_Dados_T3.ipynb no VS Code e rode todas as células na sequência.

---

---

## Insights e Conclusões da Análise

1. Remoção de colunas vazias: Removidas colunas totalmente vazias que foram criadas por causa do separador ; no final da linha.
2. Tratamento de Ausentes: Onde a categoria do produto estava como ND foi alterada para "Sem Categoria".
3. Ajuste no Formato de datas: Convertido a coluna DATA para formato datetime.
4. Verificado que a média é de 1.15 filhos por cliente.
