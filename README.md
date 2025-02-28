<!DOCTYPE html >
< html  lang =" pt-br " >

< cabeça >
    < meta  charset =" UTF-8 " >
    < meta  name =" viewport " content =" width=largura-do-dispositivo, escala-inicial=1.0 " >
    < link  href =" https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css " rel =" folha de estilo " >
    < link  rel =" folha de estilo " href =" https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css " >
    < link  rel =" folha de estilo " href =" style.css " >
    < title > Meu portfólio </ title >
</ cabeça >

< corpo >
    < header  class =" container text-center " >
        < img  src =" img/avatar-perfil.png " alt =" avatar da Fernanda " class =" rounded-circle " width =" 150 " height =" 150 "
            srcset ="" >
        < p  class =" lead " > Eu sou Fernanda_ </ p >
        < h1 > Eu ensino Programação </ h1 >
        < p > Sou Engenheira de Computação e Pedagoga. Ensino pensamento computacional para estudantes do Ensino
            Fundamental e Médio. Ensino sobre pensamento computacional usando HTML, CSS e JavaScript. Veja os projetos
            que já desenvolvi! </ p >
        < p > Minhas habilidades </ p >
        < div >
            < p  class =" emblema bg-secundário " > HTML </ p >
            < p  class =" emblema bg-secundário " > CSS </ p >
            < p  class =" emblema bg-secundário " > JavaScript </ p >
            < p  class =" badge bg-secondary " > Arranhar </ p >
        </div>​​
    </ cabeçalho >
    < classe principal  =" contêiner mt-5 " >
        < h2 > Meus projetos </ h2 >
        < div  class =" linha " >
            <!-- Projeto 1 -->
            < div  classe =" col-md-4 " >
                < div  class =" cartão " >
                    < img  src =" img/projeto-1.png " class =" card-img-top " alt =" Imagem do projeto de biblioteca virtual " >
                    < div  class =" corpo-do-cartão " >
                        < h5  class =" card-title " > Minha Biblioteca: Uma página personalizada </ h5 >
                        < p  class =" card-text " > Este projeto é uma página web que apresenta uma lista dos meus livros
                            favoritos, incluindo informações sobre os autores, dados de publicação e links para compra
                            na Amazônia. A página é estilizada com CSS para uma visualização agradável e usa fontes
                            externas do Google Fonts.
                        </ p >
                        < tipo de botão  =" botão " classe =" btn btn-link " data-bs-toggle =" modal " data-bs-target =" #modal1 " > Veja
                            o projeto </ button >
                    </div>​​
                </div>​​
            </div>​​
            <!-- Projeto 2 -->
            < div  classe =" col-md-4 " >
                < div  class =" cartão " >
                    < img  src =" img/projeto-2.png " class =" card-img-top " alt =" Imagem do projeto de biblioteca virtual " >
                    < div  class =" corpo-do-cartão " >
                        < h5  class =" card-title " > Decidindo o Futuro: Uma Jornada Interativa sobre a Inteligência
                            Artificiais </ h5 >
                        < p  class =" card-text " > Este projeto é um jogo interativo baseado em navegador que explora o
                            impacto e as implicações da Inteligência Artificial (IA) na sociedade, permitindo que as
                            as pessoas fazem escolhas que influenciam o revelador de uma narrativa sobre o
                            futuro da IA. </ p >
                        < tipo de botão  =" botão " classe =" btn btn-link " data-bs-toggle =" modal " data-bs-target =" #modal2 " > Veja
                            o projeto </ button >
                    </div>​​
                </div>​​
            </div>​​

            <!-- Projeto 3 -->
            < div  classe =" col-md-4 " >
                < div  class =" cartão " >
                    < img  src =" img/projeto-3.png " class =" card-img-top " alt =" Imagem do projeto de biblioteca virtual " >
                    < div  class =" corpo-do-cartão " >
                        < h5  class =" card-title " > Explorando o Universo: Uma Aventura Interativa em Astronomia com Scratch
                        </ h5 >
                        < p  class =" card-text " > Este projeto Scratch cria uma experiência interativa educativa sobre
                            astronomia, permitindo aos usuários explorar informações sobre constelações, eclipses, e a
                            forma da Terra através de cenários dinâmicos e diálogos informativos.
                        </ p >
                        < tipo de botão  =" botão " classe =" btn btn-link " data-bs-toggle =" modal " data-bs-target =" #modal3 " > Veja
                            o projeto </ button >
                    </div>​​
                </div>​​
            </div>​​
        </div>​​
    </ principal >

    <!-- Modal 1 -->
    < div  classe =" modal " id =" modal1 " tabindex =" -1 " >
        < div  classe =" diálogo-modal " >
            < div  classe =" conteúdo-modal " >
                < div  class =" cabeçalho-modal " >
                    < h5  class =" modal-title " > Minha Biblioteca: Uma página personalizada </ h5 >
                    < tipo de botão  = " botão " classe = " btn-close " data-bs-dismiss = " modal " aria-label = " Fechar " > </ botão >
                </div>​​
                < div  class =" corpo-modal " >
                    < p > O projeto é uma página web criada com HTML e CSS, destinada a exibir uma coleção pessoal de
                        livros favoritos. O objetivo é criar um ambiente virtual onde seja possível compartilhar
                        seus livros preferidos, fornecem uma descrição breve de cada um, incluindo o autor, o ano
                        de publicação e uma opção de compra. </ p >
                    < p > A estrutura do site é baseada em HTML, que define a semântica e o layout do conteúdo,
                        enquanto o CSS é usado para estilizar a página visualmente, incluindo núcleos, tipografia e a
                        disposição dos elementos. </ p >
                    < p > O HTML organiza o conteúdo em um cabeçalho com o título do site, seguido por uma divisão
                        principal (.container) que apresenta o propósito do site e a coleção de livros em uma seção
                        flexível (.livros). Cada livro é destacado em seu próprio contêiner (.livro), mostrando uma
                        imagem da capa, detalhes do livro e um link de compra. O design responsivo é garantido pelo
                        uso de uma meta tag viewport e um layout flexível que se adapta a diferentes tamanhos de
                        tela. </ p >
                    < p > O CSS personaliza o visual do site, usando variáveis ​​para cores, estilizando o texto com uma
                        fonte importada do Google Fonts e aplicando um esquema de cores suaves e botões interativos.
                        O uso de HTML e CSS é importante pois assim é possível criar um site acessível e
                        esteticamente agradável sem a necessidade de scripts complexos, com foco na usabilidade e na
                        experiência da pessoa usuária. A escolha da tipografia e do esquema de cores contribui para
                        a atmosfera acolhedora do site, incentivando a exploração da coleção de livros. </ p >
                    < img  src =" img/projeto-1.png " class =" img-fluid w-100 "
                        alt =" Imagem representativa do projeto de uma biblioteca online " >
                </div>​​
                < div  classe =" rodapé-modal " >
                    < a  href =" https://femascheti.github.io/minhas-leituras/ " > Ver projeto ao vivo </ a >
                    < a  href =" https://github.com/femascheti/minhas-leituras " > Ver código do projeto </ a >
                </div>​​
            </div>​​
        </div>​​
    </div>​​
    <!-- Modal 2 -->
    < div  classe =" modal " id =" modal2 " tabindex =" -1 " >
        < div  classe =" diálogo-modal " >
            < div  classe =" conteúdo-modal " >
                < div  class =" cabeçalho-modal " >
                    < h5  class =" modal-title " > Minha Biblioteca: Uma página personalizada </ h5 >
                    < tipo de botão  = " botão " classe = " btn-close " data-bs-dismiss = " modal " aria-label = " Fechar " > </ botão >
                </div>​​
                < div  class =" corpo-modal " >
                    < p > O projeto consiste em uma aplicação web interativa, desenvolvida com HTML, CSS, e JavaScript, que
                        simula uma experiência narrativa centrada no tema da Inteligência Artificial. O objetivo é
                        envolver os jogadores em um cenário fictício que aborda o avanço da IA ​​e suas possíveis
                        consequências para a humanidade, destacando a importância da reflexão ética sobre a tecnologia.
                    </ p >
                    < p > O HTML estrutura o conteúdo da página, dividindo-o em frascos como a tela inicial, caixa de
                        perguntas, alternativas de resposta, e o resultado final baseado nas escolhas do jogador. O CSS
                        é utilizado para estilizar a página, empregando um esquema de cores futurista e layout
                        responsivo para melhorar a experiência do usuário. JavaScript é usado para adicionar
                        interatividade ao jogo, manipulando o DOM para atualizar o conteúdo da página conforme
                        escolhas do jogador, e determinando o fluxo da narrativa através de uma série de perguntas e
                        respostas. </ p >
                    < p > O HTML organiza o conteúdo em um cabeçalho com o título do site, seguido por uma divisão
                        principal (.container) que apresenta o propósito do site e a coleção de livros em uma seção
                        flexível (.livros). Cada livro é destacado em seu próprio contêiner (.livro), mostrando uma
                        imagem da capa, detalhes do livro e um link de compra. O design responsivo é garantido pelo
                        uso de uma meta tag viewport e um layout flexível que se adapta a diferentes tamanhos de
                        tela. </ p >
                    < p > Os scripts JavaScript incluem módulos para gerar nomes aleatórios, definir as perguntas e as
                        lógicas de jogo, como iniciar o jogo, apresentar perguntas e alternativas, processar as escolhas
                        dos jogadores, e exibir o resultado final. Este design modular facilita a manutenção e a
                        expansão futura do jogo. A importância das ferramentas utilizadas (HTML, CSS, JavaScript) reside
                        na criação de uma experiência interativa que não apenas entretém, mas também educa os jogadores
                        sobre a complexidade ética e social da IA, incentivando a reflexão crítica sobre o papel da
                        tecnologia em nossas vidas.
                    </ p >
                    < img  src =" img/projeto-2.png " class =" img-fluid w-100 "
                        alt =" Imagem representativa do projeto de uma biblioteca online " >
                </div>​​
                < div  classe =" rodapé-modal " >
                    < a  href =" https://femascheti.github.io/tecnicas-computacionais-refletindo-sobre-ia/ " > Ver projeto ao
                        vivo </ a >
                    < a  href =" https://github.com/femascheti/tecnicas-computacionais-refletindo-sobre-ia " > Ver código do
                        projeto </ a >
                </div>​​
            </div>​​
        </div>​​
    </div>​​

    <!-- Modal 3 -->
    < div  classe =" modal " id =" modal3 " tabindex =" -1 " >
        < div  classe =" diálogo-modal " >
            < div  classe =" conteúdo-modal " >
                < div  class =" cabeçalho-modal " >
                    < h5  class =" modal-title " > Minha Biblioteca: Uma página personalizada </ h5 >
                    < tipo de botão  = " botão " classe = " btn-close " data-bs-dismiss = " modal " aria-label = " Fechar " > </ botão >
                </div>​​
                < div  class =" corpo-modal " >
                    < p > O projeto é uma aplicação educativa interativa focada em ensinar conceitos básicos de
                        astronomia. Utilize uma série de scripts associados a diferentes atores (sprites) e
                        cenários para criar uma experiência de aprendizagem envolvente. O objetivo é familiarizar
                        os usuários com descrições como as fases da Lua, eclipses, a visibilidade de diferentes
                        constelações dependendo da localização geográfica na Terra, e da forma da Terra, através
                        de interações e visualizações dinâmicas. </ p >
                    < p > Cada ator no projeto possui scripts que definem seu comportamento em resposta a eventos
                        específicos, como o início do programa (quando a bandeira é clicada), cliques do
                        usuário, ou mensagens recebidas. Estes eventos desencadeiam ações como mudanças de
                        cenário, movimentos de atores, exibição ou ocultação de atores, e a apresentação de atores
                        diálogos informativos. Por exemplo, ao clicar em determinados direcionadores, os usuários podem
                        "receber" uma prova, o que leva a uma mudança de cenário e a exibição de informações
                        relevantes ou a visualização de uma constelação específica. </ p >
                    < p > A importância das ferramentas utilizadas, como os blocos de código visual do Scratch,
                        residir na sua acessibilidade e na capacidade de envolver alunos de diferentes idades
                        no pensamento computacional e na exploração de conceitos científicos de forma
                        interativo. O uso de cenários, movimentos e diálogos dinâmicos ajuda a criar uma
                        experiência de aprendizado mais rica e inovadora, encorajando os usuários a explorar e
                        interagir com o conteúdo de maneira ativa, em vez de passivamente. </ p >
                    < img  src =" img/projeto-3.png " alt =" Projeto 3 " class =" img-fluid w-100 " >
                </div>​​
                < div  classe =" rodapé-modal " >
                    < a  href =" https://scratch.mit.edu/projects/951732825/ " > Ver projeto ao vivo </ a >
                </div>​​
            </div>​​
        </div>​​
    </div>​​
    < rodapé  classe =" contêiner py-5 " >
        < h2 > Entre em contato </ h2 >
        < div >
            < i  class =" bi bi-github " > </ i >
            < a  href =" https://github.com/femascheti " > GitHub </ a >
        </div>​​
        < p  class =" my-5 text-center " > © Copyright 2024. Produzido por Fernanda Mascheti </ p >
    </ rodapé >

    < script  src =" https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js " > </ script >
</ corpo >

</ html >

