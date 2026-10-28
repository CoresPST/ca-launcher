# a base do launcher

fui montando o launcher do Counter Advanced pra ter um lugar pra abrir o jogo, mexer nas opções e pegar as atualizações. fiz essa parte do PC em C# com .NET Framework.

no começo parece que é só fazer um botão escrito jogar kkk, mas esse botão precisa pegar as opções que a pessoa escolheu e abrir o jogo do jeito certo. janela, tela cheia, resolução e essas coisas.

separei a parte da tela da parte que cuida de abrir o jogo e atualizar os arquivos. assim da pra mudar o visual sem precisar refazer tudo que acontece por trás.

as configurações do jogador ficam separadas tbm. atualizar o launcher não pode apagar o que a pessoa já ajustou no jogo.

uma coisa que fui ajeitando foi o retorno dos botões. se ta baixando, mostra o progresso. se deu erro, fala que deu erro. nada de deixar o botão parado e a pessoa sem saber se clicou ou não.

a ideia da base é mais ou menos essa: a tela pega a escolha da pessoa, a lógica confere o que precisa fazer e aí abre o jogo. o launcher ajuda nessa parte, ele não é a engine do jogo.

[tem um texto do atualizador aqui](https://github.com/CoresPST/ca-auto-updater) e [outro da adaptação dos modelos](https://github.com/CoresPST/ca-modelos).
