Mini-ERP de Estoque
Sistema de controle de estoque inspirado em módulos ERP profissionais.
Desenvolvido para fins educacionais, com funcionalidades de cadastro, movimentação, relatórios e gráficos.

 Funcionalidades
-Cadastro de Produtos
-Nome
-Categoria
-Preço
-Quantidade inicial
-ID automático gerado pelo sistema

Exclusão de Produtos
Permite remover produtos pelo ID

Listagem de Produtos

Mostra ID, nome, categoria, preço e quantidade
Produtos com estoque menor que 5 recebem alerta 

 Movimentação de Estoque
Entrada: aumenta quantidade
Saída: diminui quantidade, respeitando estoque disponível

 Dashboard de Gráficos 

Quantidade por produto (gráfico de barras)

Comparação por categoria (gráfico de barras)

Curva ABC (valor total em estoque por produto)

Obs.: Os gráficos usam Matplotlib, que já vem instalado no Google Colab.

 Tecnologias Utilizadas

Python 3
Matplotlib

Estruturas de dados: listas e dicionários

 Como Executar

Abra o Google Colab: https://colab.research.google.com
Crie um novo notebook
Cole o arquivo main.py ou o código do ERP na primeira célula
Execute a célula e interaja com o menu


Exemplos de Gráficos
Estoque por produto
Comparação de estoque por categoria
Curva ABC do valor do estoque

Autor

Erlâne Manuela Santos Parente




