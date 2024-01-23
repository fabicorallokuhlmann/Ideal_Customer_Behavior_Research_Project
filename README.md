# Ideal Customer Behavior Research Project

Projeto elaborado com o objetivo de gerar insights diagnósticos sobre o **perfil de cliente ideal para a empresa**, visando o **melhor direcionamento do orçamento disponível em marketing**. O banco de dados possui uma coluna de nota de 0 a 100 para cada cliente e a partir da análise dos demais dados, espera-se chegar a tal perfil.  
<br/>
Para tanto, os seguintes passos listados abaixo foram adotados:
1) Importação da base de dados
   <br/>
2) Visualização da base de dados
   <br/>
3) Tratamento de erros
   <br/>
5) Análise inicial dos dados para compreender o estado atual dos cancelamentos
   <br/>
6) Análise profunda dos dados para encontrar as motivações do cancelamento
   <br/>
  
Com a lista de passos em mãos, o desenvolvimento do código seguiu o seguinte raciocínio:
   <br/>
  I) importação das bibliotecas necessárias para a análise:  **Matplotlib, Pandas, Plotly, Seaborn e NumPy**
   <br/>
 II) leitura do arquivo juntamente com a correção dos erros de acento e separador para melhor visualização
<br/>
 III) visualização da tabela
<br/>
 IV) identificação os possíveis tratamentos para a tabela 
<br/>
 V) retirada de colunas desnecessárias, correção de tipo de entrada e remoção de valores vazios
<br/>
 VI) análise inicial para visualização da distribuição de notas dos clientes
<br/>
 VII) análise gráfica da nota média dos clientes de acordo com as características relacionadas nas colunas</b>
<br/><br/>
 
 **Resultado**: através das relações apresentadas graficamente, pode-se afirmar que o perfil ideal de cliente: <br/>
 - **maior do que 20 anos** (não há muita diferença entre as faixas etárias depois dessa)<br/>
 - que exerça atividades profissionais relacionados a **entreterimento e artes** (evitar construção, pois pela nota média é um perfil problemático)<br/>
 - tamanho de família de **até 7 membros**<br/>
 - tem entre **10 a 15 anos de experiência profissional**<br/>
 - **faixa de renda parece não ter grande influência** na determinação da nota <br/>
