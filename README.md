<h1>Linux Ubuntu e Git atualizando o GitHub</h1>
<p>Neste artigo será feito testes e será usado comandos no terminal do gnome.</p>
<p>Aqui mostro mais uma expêrencia no meu início de utilização do Linux como eu gosto muito de usar o GitHub para salvar meus projetos,
um dos primeiros passos após a instalação do Ubuntu foi justamente instalar o Git para poder atualizar minha página no GitHub</p>
<p>Logo no início do artigo já deixo claro os nomes Git e GitHub, pois são coisas diferentes e que podem confundir quem está iniciando no mundo da programação.</p>
<p>O Git é uma ferramenta de controle de versão, o papel mais básico do Git é gerenciar e guardar um histórico das 
alterações que fazemos em nossos arquivos.O Git foi criado pelo Linus Trovalds em 2005.O Git não depende do GitHub para ser utilizado.</p>
<p>GitHub é um site onde você pode subir seus projetos e compartilhar com o mundo.E você vai subi-los usando o Git.Você pode usar o GitHub como um protifólio do seu código, no GitHub estão a maioria dos projetos open source.O GitHub ´e uma espécie de rede social para desenvolvedores, que podem seguir outros membros, ver o código, baixar projetos e até contribuir no desenvolvimento de aplicações, projetos etc.</p>
<h3>Baixar pacotes do git</h3>
<p>Para instalar o Git no Ubuntu foi muito simples, apenas utilizei o gerenciador de pacotes padrão apt-get</p>
<p>sudo apt-get install git </p>
<p>Utilizei o sudo na frente do comando para ele instalar como um usuário, na primeira vez que você utilizar o sudo ele irá pedir sua senha de root. </p>
<h3>Configurando o Git</h3>
<p>Para configurar o Git utilizei alguns comandos da página oficial para setar usuário e email</p>
<p>git config --global user.name "seu_usuario"
 git config --global user.email seuemail@email.com</p>
<h3>Verificar suas configurações</h3>
<p>O comando abaixo lista suas configurações do git</p>
<p>git config --list</p>

