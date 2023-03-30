// English:
# Tkinter Bookstore Example
This code is an example of a Tkinter GUI application for a bookstore. It allows the user to select a book from a list and purchase it. The code is intended for educational purposes only.

# Getting Started
To run the application, simply execute the following command:
python3 main.py

# Prerequisites
This application requires Python 3 and the Tkinter library.

# Usage
Upon launching the application, the user will be prompted to enter their name. Once they have done so, they will be presented with a list of books to choose from. When the user clicks the "Comprar" button next to a book, a message will be displayed confirming the purchase.

# Code Example
The following code snippet demonstrates how the book list is displayed:

for i,(livro, preco) in enumerate(livros):
    tk.Label(table, text=livro).grid(row=i, column=0)
    tk.Label(table, text=f"R$ {preco:.2f}").grid(row=i, column=1)
    tk.Button(table, text="Comprar", command=lambda row=i: select_row(row)).grid(row=i, column=2, padx=5, pady=10)

# Contributing
This code is intended for educational purposes only and is not actively maintained. However, if you would like to contribute to the project, please feel free to submit a pull request.

# License
This code is released under the MIT License. See LICENSE.md for more information


// PT-BR:
# Exemplo de Livraria Tkinter
Este código é um exemplo de um aplicativo Tkinter GUI para uma livraria. Ele permite ao usuário selecionar um livro de uma lista e comprá-lo. O código destina-se apenas para fins educacionais.

# Começando
Para executar o aplicativo, basta executar o seguinte comando:

'python3 main.py'

# Pré-requisitos
Este aplicativo requer Python 3 e a biblioteca Tkinter.

# Uso
Ao iniciar o aplicativo, o usuário será solicitado a inserir seu nome. Depois de o terem feito, ser-lhes-á apresentada uma lista de livros à escolha. Quando o usuário clicar no botão "Comprar" ao lado de um livro, será exibida uma mensagem confirmando a compra.

# Exemplo de código
O trecho de código a seguir demonstra como a lista de livros é exibida:

for i,(livro, preco) in enumerate(livros):
     tk.Label(tabela, texto=livro).grid(linha=i, coluna=0)
     tk.Label(tabela, text=f"R$ {preço:.2f}").grid(linha=i, coluna=1)
     tk.Button(table, text="Comprar", command=lambda row=i: select_row(row)).grid(row=i, column=2, padx=5, pady=10)
		 
# Contribuindo
Este código destina-se apenas para fins educacionais e não é mantido ativamente. No entanto, se você quiser contribuir com o projeto, sinta-se à vontade para enviar uma solicitação de recebimento.

# Licença
Este código é liberado sob a licença MIT. Consulte LICENSE.md para obter mais informações
