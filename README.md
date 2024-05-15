# Leaf Theme Modified -> vulnerable / OLD

This was my original theme to matheuslaidler.github.io
Esse ja foi meu principal tema para matheuslaidler.github.io

 - **PORTUGUESE [PT-BR]**
Sobre>
** Att: Virou uma página de tema jekyll editado, que eu usava antes. Iria ser usado como minha pagina de rascunho, mas desisti. Por eu ter parado de usar - até por supostamente ter erros que quero explorar antes de corrigí-los -, passei a usar e criar meus materiais no gitbook (matheuslaidler.gitbook.io), mas a ideia eh meu projeto oficial ser por aqui e separar wayofsecurity e road2tech de alguma forma, então voltarei a deixar minhas publicações oficiais por aqui e deixar os do gitbook como rascunhos. Este repositório vai ficar como uma forma de manter este tema com as modificações que eu fiz para quem quiser usar e começar a editar também. Altere a versão bundler para 2.2.33 ou superior :-: [vulnerabilidade: CVE-2020-36327] - saiba mais sobre a vuln abaixo (ingles)
____________________________________________________________________________________
 - **ENGLISH [ENG]**
Vuln>
Package: bundler (RubyGems)
Affected versions: >= 1.16.0, < 2.2.10
Patched version: 2.2.10

Bundler 1.16.0 through 2.2.9 and 2.2.11 through 2.2.17 sometimes chooses a dependency source based on the highest gem version number, which means that a rogue gem found at a public source may be chosen, even if the intended choice was a private gem that is a dependency of another private gem that is explicitly depended on by the application.
____________________________________________________________________________________


### Modificações no tema leaf
                          
*Tema editado para meus objetivos; tema original: "jekyll-theme-leaf theme"*
              
              . Resumo geral das mudanças;
              ----------------------------
        - add; Categorias
        
        - Retirado; Imagem do centro da barra de menus e a aba Contact
        
        - Modificado; Cores



Credits

Matheus Laidler (Founder of this project) [Site/Posts/Theme-edit]

   -github.com/MatheusLaidler
 
 
SupunKavinda (Founder of Hyvor); [Theme]
 - newlink: https://github.com/supun-io/jekyll-theme-leaf

