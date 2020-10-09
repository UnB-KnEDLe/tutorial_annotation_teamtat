# Ato de Substituição de Funções

Primeiro é necessário verificar se existem atos de substituiço no DODF, bastando pressionar CTRL+F e pesquisar pelos termos "para substituir" ou "em substituição". Após encontrar um ou mais blocos relacionados a substituição, deve-se fazer a correspondência de cada bloco de texto em relação a um dos padrões definidos a seguir.

## Link para vídeo no YouTube

Em breve.

## Padrão do ato

DESIGNAR/Designar o **[nome_substituto] (1)**, matrícula nº **[matricula_substituto] (2)**, **[cargo_substituto] (5)**, **[simbolo_substituto] (6)**, para substituir **[nome_substituido] (3)**, matrícula nº **[matricula_substituido] (4)**, **[cargo_objeto_substituicao] (7)**, Símbolo **[simbolo_objeto_substituicao] (8)**, do **[hierarquia_lotacao] (9)**, cargo **[orgao] (10)**, no período de **[data_inicial] (11)** até **[data_final] (12)**, por motivo de **[motivo] (14)**.


### Tabela de entidades e padrões

As entidades que deverão ser identificadas são:

ID | Rótulo | Entidade (descrição)  | Padrão | Obrigatório? 
------- | ------- | ------- | ------- | -------
(1) | nome_substituto | Nome do Servidor | n.a. | Sim
(2) | matricula_substituto | Matrícula do Servidor Substituto | Letras maiúsculas aṕos 'DESIGNAR' | Sim
(3) | nome_substituido | Nome do Servidor a ser Substituido | Após 'para substituir' | Não
(4) | matricula_substituido | Matrícula do Servidor a ser Substituido | Após 'matrícula n°' | Sim
(5) | cargo_substituto | Cargo efetivo ou comissionado do servidor substituto | Sem Padrão | Não
(6) | simbolo_substituto | Símbolo do cargo do servidor substituto | Após 'Símbolo' | Não
(7) | cargo_objeto_substituicao | Cargo comissionado objeto da substituição |	Sem padrão | Não
(8) | simbolo_objeto_substituicao | Símbolo do cargo comissionado objeto da substituição |	Após 'Símbolo' | Não
(9) | hierarquia_lotacao | Hierarquia da Lotação|	Sem Padrão | Não
(10) | orgao | Órgão |	Sem Padrão | Sim
(11) | data_inicial | Data Inicial da Vigência |	Após 'no período de' | Não
(12) | data_final | Data Final de Vigência |	Após Data Inicial da Vigência | Não
(13) | matricula_SIAPE | Matrícula SIAPE |	Após 'SIAPE' (apenas para Pol. Civil) | Não
(14) | motivo | Motivo da substituição |	'em virtude ou a pedido'  | Não

### Exemplos de atos de substituição de função

> Art. 1º Designar **ANA PAULA VEIGA TRIERS(1)**, matrícula **1402016-5(2)**, como **executora substituta do Convênio nº 008/2019 - NCC/CODAG/FHB(5)**, em substituição a **Ysis Martins Aquino(3)**, matrícula: **1681885-7(4)**, objeto do processo nº 00063-00002158/2019-34. Art. 2º Designar **ANA PAULA VEIGA TRIERS(1)**, matrícula **1402016-5(2)**, como executora principal do Convênio nº 001/2019 NCC/CODAG/FHB, em substituição a **Ysis Martins Aquino(3)**, matrícula: **1681885-7(4)**, e **Ana Louise Ferreira de Araújo(1)**, matrícula **1694463-1(2)**, como executora substituta do Convênio nº 001/2019 NCC/CODAG/FHB, em substituição a **Madellon Melo de Assis(3)**, matrícula: **1681964-0(4)**, objeto do processo nº 00063-00000127/2019-49. Art. 3º Esta Instrução entra em vigor na data de sua publicação.

> Art. 1º Designar **EVANDRO LUIZ DE SOUZA OLIVEIRA(1)**, matrícula nº **1.402.084-X(2)**, para substituir **EVANDRO MARTINS RIBEIRO(3)**, matrícula nº **169066-16(4)**, titular do Cargo de Natureza Especial, Símbolo **CNE-07(8)**, de **Pregoeiro(7)** da **Fundação Hemocentro de Brasília(10)**, nos seus **afastamentos e impedimentos legais(14)** e sem acumular vencimentos;
> Art. 2º Designar **EVANDRO LUIZ DE SOUZA OLIVEIRA(1)**, matrícula nº **1.402.084-X(2)**, para substituir **SALOMÃO SANCHES LEONEL BATISTA(3)**, matrícula nº **1.690.356-0(4)**, titular do Cargo de Natureza Especial, Símbolo **CNE-06(8)**, de **Chefe(7)** do **Centro de Compras(9)** da **Fundação Hemocentro de Brasília(10)**, nos seus **afastamentos e impedimentos legais(14)** e sem acumular vencimentos.
> Esta Instrução **entra em vigor na data de sua publicação(11)**.

> DESIGNAR **LUCIMAR GOMES DA SILVA(1)**, matrícula  nº **83.588-9(2)**, ocupante do cargo de **Assistente(5)** da Gerência de Gestão de Pessoas, do Serviço de Limpeza Urbana do Distrito Federal, para substituir a **Gerente de Gestão de Pessoas(7)**, do **Serviço de Limpeza Urbana do Distrito Federal(10)**, no período de **31/05/2019(11)** a **09/06/2019(12)**, por motivo de **férias regulamentares(14)**.

> DESIGNAR **ANTONIA SHARLA PENHA CARREIRO(1)**, matrícula  nº **273.641-1(2)**, **Gerente(5)**, Símbolo **DFG-14(6)**, para substituir **JOSÉ GENIVALDO SOUSA DE SILVA(3)**, matrícula nº **171.583-6(4)**, **Coordenador(7)**, Símbolo **CNE-07(8)**, da **Coordenação de Logística da Subsecretaria de Administração Geral(9)**, da **Secretaria de Estado de Obras e Infraestrutura(10)**, no período de **03 de junho de 2019(11)** a **22 de junho de 2019(12)**, por motivo de **férias do titular(14)**.

## Sugestão de como realizar/corrigir a anotação de um ato de substituição de funções:


1. **Delimite o espaço visual de anotação:** Posicione o texto do DODF na tela do computador que contemple, no mínimo, 1 bloco de texto relacionado ao ato;

2. **Anote todos os nomes dos servidores:** São todas as palavras que aparecem logo após a palavra “Designar” ou "DESIGNAR";

3. **Anote os cargos:** Eles aparecerão perto do nome e/ou matrículas.

4. **Anote as matrículas:** Sempre aparecem logo depois da palavra “matrícula”.

5. **Anote o símbolo:** Aparecem após o Cargo comissionado objeto da substituição;

6. **Anote os órgãos e as hierarquias de lotação:**  São todas as palavras que ficam entre o cargo em comissão e o órgão. O tamanho deste atributo varia bastante.

7. **Anote a data inicial e final da substituição:** Costuma aparecer após os órgãos;

8. **Anote o motivo:** Costuma aparecer como a última entidade do ato;

9. **Anote os atos de substituição na íntegra:** Anote todas as palavras desde "Designar” ou "DESIGNAR" até o ponto final mais próximo.


**IMPORTANTE:** Após anotar todos os atos de substituição em um documento, ative a opção "Curatable" no canto direito superior do documento.


## Observações Gerais sobre os atos substituição de funções:

* O padrão dos atos de substituição costumam variar bastante, podendo um bloco de texto relacionado ao ato encontrar várias substituições, que estão relacionados a um servidor que substituirá pelo menos uma função. Nesse caso, simplifique. Anote uma entidade no bloco de texto que pode representar o ato;
* As entidades de data inicial e final podem variar, apresentando apenas a vigência, por exemplo: entre 03 e 10 de janeiro de 2020, ao invés de (como definido no documento de requisitos do TCDF) 03 de janeiro de 2020 à 10 de janeiro de 2020. Nesse caso, coloque a anotação de data inicial como 03 e a data final como 10 de janeiro de 2020;
* Nem sempre o ato terá todos os atributos, mas anote todos os que você encontrar;
* Não anote vírgulas e pontos, a não ser que eles estejam dentro do atributo, como acontece em Hierarquia de Lotação;
* Tenha muito cuidado para não apagar todas as anotações de um documento, mesmo tendo função de anotador;
* Recomendo sempre que for fazer uma pausa mais prolongada, que salve um arquivo xml com as suas anotações, por precaução. Desta forma, você terá um backup caso aconteça alguma coisa e você perca todas as anotações feitas no documento, e com isso não terá que começar a anotar do zero;
