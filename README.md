Crie uma aplicação React que permita ao usuário introduzir conteúdo textual e imagens, e ao final gerar um PDF e enviar o mesmo para uma API.

	Requisitos

Formulário de entrada de dados:

Crie um formulário dinâmico em que o usuário possa introduzir qualquer número de parágrafos e/ou imagens.
O conteúdo desses parágrafos e imagens será utilizado para gerar um arquivo PDF.

	Renderização do PDF:

Use a biblioteca @react-pdf/renderer para criar um PDF com base no conteúdo do formulário preenchido pelo usuário.
O PDF deve ter um cabeçalho (criado a seu critério) que aparece em todas as páginas.
A renderização das imagens deve ser feita em páginas avulsas, ou seja, sempre que houver uma imagem, ela deve ser renderizada sozinha (incluindo o cabeçalho), em uma única página.
Você deve utilizar uma fonte não usual para o texto.
Deverá ser possível pré-visualizar o PDF gerado, sem necessidade de realizar o download do mesmo.
Deverá ser possível fazer o download do PDF gerado.
Envio do PDF para a API:
Deverá ser possível enviar o PDF para alguma API (não precisa fazer isso de verdade, somente o mock da chamada HTTP já é o suficiente).
