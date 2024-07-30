@@ -0,0 +1,26 @@
: raiz {
    --branco- principal :  #FFFFFF ;
    --cinza-secundario :  # C0C0C0 ;
    --botao-azul :  # 167BF7 ;
    --cor-de-fundo :  # 00030C ;
}

corpo {
    cor de fundo :  var ( -cor-de-fundo );
    cor :  var ( --branco-principal );
}

* {
    margem :  0 ;
    preenchimento :  0 ;
}

. diretor {
    imagem de fundo :  url ( "img/Background.png" );
    background-repeat : sem repetição;
    tamanho-de-fundo : conter;
}

. recipiente {
    altura :  100 vh ;
}
