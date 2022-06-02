normalize.css: o normalize tem a mesma função que o reset.css

para boas praticas, é sempre bom criar um arquivo css pra cada coisinha do html, para que fique mais organizado e de facil manutenção. 
Quando tem muitos arquivos para a mesma coisa, exemplo: menu, se cria uma pasta

B E M: Block Element Modifier (bloco elemento modificador){
    bloco é basicamente o pequeno contexto do que ele vai fazer
    bloco
    bloco__elemento
    bloco--modificador
    bloco__elemento--modificador
}

no banner o position absolute no titulo deixa ele absoluto à pagina inteira, porém quando é colocado position relative na classe banner, o titulo passa a ser relativo à classe banner e somente a ele 

100vh: viewportheight>tamanho da janela de navegador
height: calc(100vh - 72px): nesse caso ele vai desconsiderar o cabeçalho, dessa forma a imagem fica de facil visualização ao entrar na pagina

B E M é especifico para nomenclatura de classes

flex-wrap:wrap>>vai quebrar os elementos de linha para colunas

as imagens das pessoas não estão no html, pois as imagens são apenas para estilização, logo essas imagens devem ser colocadas no css, devido a isso não se criar um <img> e sim um <div>

justify-content: space-around>>espaço entre todas os elementos

background-image: url('../../img/pessoas/roberta.jpg')>> o ../ serve para voltar uma pasta

para boas praticas é sempre bom organizar em ordem alfabética o css