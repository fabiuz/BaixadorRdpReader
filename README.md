@Programa: BaixadorRdpReader
Este programa está sendo criado para baixar cada página de um livro que está no leitor rdp dentro do navegador.
Estive inspecionando o código, cada página, é um arquivo de imagem, tais páginas estão hospedados em servidores CDN.
Na url no navegador, há o número isbn do livro, em seguida, o número da página, entretanto, não é possível saber a quantidade das páginas.
O que será feito, que irei enviar uma solicitação GET para a url sem o número de página, pra retornar a primeira página, nem sempre a página começa em 0 ou 1, pode começar assim _9, _8, aí depois, chegar em 1.
Aí, depois, dentro do conteúdo html retornado da página, irei pegar a próxima página e assim por diante.

O que o programa fará será:
Acessar a primeira página do livro, baixar a imagem da página hospedada no servidor cdn.
Em seguida, dentro do código html, irei analisar a tag e recuperar a próxima página e assim por diante até terminar.
Cada livro baixado, terá uma pasta com o número do isbn.
Dentro da pasta, o arquivo correspondente da primeira página do livro terá o nome do arquivo neste formato:
isbn_pag.extensao


Este programa está em desenvolvimento.

[ATENÇÃO: ESTE PROJETO ESTÁ SUSPENSO NO MOMENTO EM BREVE ESTAREI ATUALIZANDO]
