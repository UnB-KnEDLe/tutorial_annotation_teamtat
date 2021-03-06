# Tutorial de Anotação

Nesse repositório está o tutorial de como anotar os documentos do Diário Oficial do Distrito Federal (DODF) de acordo com os requisitos do Tribunal de Contas do Distrito Federal (TCDF).

A ferramenta usada para realizar as anotações será o [NidoTat](http://nido.cic.unb.br/), um fork do [TeamTat](https://www.teamtat.org/). Essa é uma ferramenta online para anotação que permite que várias pessoas anotem e revisem um mesmo documento facilitando a geração de uma base de dados padrão ouro.

Algumas funcionalidades foram incluídas no NidoTat para melhor atender às necessidades do projeto [KnEDle](https://unb-knedle.github.io/nido.html). Dentre elas, constam alguns atalhos de teclado, cujos valores padrão são descritos na tabela abaixo:

Função | Tecla
------- | -------
Navegação: próxima palavra | d
Navegação: palavra anterior | a
Navegação: próximo caractere | e
Navegação: caractere anterior | q
Navegação: avançar várias palavras | s
Navegação: voltar várias palavras | w
Seleção de texto | SHIFT + tecla de navegação
Percorrer lista de entidades selecionadas | CTRL
Adicionar anotação de entidade | SPACE
Remover anotação de entidade | r
Adicionar relação | v

Outra melhoria que vale a pena mencionar é a possibilidade de excluir anotações usando o botão direito do mouse.

A anotação dos documentos do DODF será feita a nível de atos de entidades. Os atos as serem anotados estão apresentados a seguir e as respectivas entidades estão nos tutoriais individuais dos atos.

*   [Exoneração](ato_exoneracao/README.md)
*   [Nomeação](ato_nomeacao/README.md)
*   [Ato tornado sem efeitos](ato_tornado_sem_efeito/README.md)
*   [Retificação](ato_retificacao/README.md)
*   [Aposentadoria](ato_aposentadoria/README.md)
*   [Reversão](ato_reversao/README.md)
*   [Abono de permanência](ato_abono_permanencia/README.md)
*   [Retificação](ato_retificacao/README.md)
*   [Substituição de Funções](ato_substituicao/README.md)
*   [Cessão](ato_cessoes/README.md)


Vamos começar!

Primeiramente, é fornecida uma URL única para o anotador. Com ela, é possível acessar os projetos e os documentos a serem anotados, portanto, é importante salvá-la em um lugar em que possa ser acessada posteriormente.

Ao acessar a URL, o anotador é direcionado para a página de perfil de usuário do TeamTat, em que é possível modificar seu nome de usuário e enviar a URL de acesso por e-mail.

![alt text](imagens/profile.PNG "Perfil de usuário")

Para acessar os documentos a serem anotados, basta clicar em "Projects" e, em seguida, no projeto referente ao documento desejado.

![alt text](imagens/project.PNG "Projetos")

Os rótulos usados para a anotação estão diponíveis na aba "Types".

![alt text](imagens/types.PNG "Rótulos dos atos e entidades")

Vamos começar a anotar!

Para encontrar os atos a serem anotdados no documento, pesquise, pressionando CTRL+F, a palavra chave do ato em questão. Este tutorial mostra a anotação de um ato de exoneração como exemplo, então será pesquisada a palavra "exonerar". A pesquisa também indicará quantos atos desse tipo existem no documento.

![alt text](imagens/ctrlF.PNG "Busca Global")

Após isso, as entidades serão anotadas. Se existirem poucos atos do tipo escolhido no documento, 20 ou menos, é recomendado anotar uma entidade por vez, ou seja, anote todos os nomes de servidores do documento,  todas as matrículas do documento e assim por diante. Caso haja muitos atos, é recomentado anotar as entidades por parágrafo.

Para fazer a anotação em si, escolha qual a entidade deve ser anotada e selecione seu rótulo na aba esquerda da tela. Para selecionar a entidade, aperte a tecla com o número correspondente da entidade, 0 a 9. Caso a entidade não esteja nessa faixa, aperte "CTRL" para mudar a faixa de valores. A faixa escolhida será apresentada em negrito.

![alt text](imagens/entidades-tec.png "Entidades")

Então, com o mouse, selecione o texto correspondente a esse rótulo.

![alt text](imagens/rotulo.png "Rótulo selecionado")

![alt text](imagens/entidade-1.PNG "Texto selecioando e entidade anotada")

O texto selecionado ficará grifado com a cor correspondente ao rótulo escolhido.

Outra forma de anotar as entidades é através de atalhos do teclado. Selecione o parágrafo que contém a entidade e, para percorrer as palavras, aperte "D" para ir uma palavra para frente, "A" para ir uma palavra para trás, "S" para ir algumas palavras para frente e "W" para ir algumas palavras para trás. Para ir um caractere para frente ou para trás, aperte "E" e "Q", respectivamente. Para selecionar um conjunto de palavras, aperte "SHIFT" e os caracteres listados anteriormente.

Caso tenha feito uma anotação incorreta e queira apagá-la, selecione, através dos atalhos de teclado, a anotação e, em seguida, aperte "R".

Esses atalhos não são fixos e podem ser alterados na aba "Shortcuts".

![alt text](imagens/shortcuts-aba.png "Aba de atalhos")

![alt text](imagens/shortcuts.png "Atalhos")

Após anotar as entidades do ato, é necessário anotar o ato completo. Para isso, escolha o rótulo do ato na aba esquerda e selecione o texto correspondente. Uma tela pop-up irá aparecer, pois já existem anotações no texto selecionado. Nessa tela, escolha a opção "Create New Annotation".

![alt text](imagens/popup.PNG "Tela para selecionar nova anotação")

![alt text](imagens/ato.PNG "Ato anotado com suas entidades")

Quando os atos e as entidade estiverem anotados, é necessário criar as relações, lembrando que a relação é feita entre o ato e suas respectivas entidades, nunca entre atos. Para isso, selecione o texto que contém as entidades a serem relacionadas, assim que a janela pop-up aparecer, selecione as entidades e o ato que fará parte da relação e aperte em "Add to Relation".

![alt text](imagens/relacao-types.png "Selecionar as entidades e o ato que farão parte da relação")

![alt text](imagens/relacao-1.PNG "Criar a relação")

![alt text](imagens/relacao-2.PNG "Relação pronta")

Da mesma forma que para anotação de entidades, existem atalhos de teclado para criar relações. Selecione o trecho de texto que contém as anotações e aperte em "" pra criar a relação.

Por fim, quando todo o documento estiver pronto, clique em "DONE".

![alt text](imagens/done.PNG "Documento pronto")
