# Teste de Programação e Sistemas de Informação - Módulo 12 - Turno 2

Cria um repositório **privado** no GitHub com o nome **"PSI_Teste_M12_2"** e com um ficheiro **README**.

Podes fazer ***clone*** do repositório para o teu computador (ou para o Replit) e preencher o **README** localmente (ou no Replit) com as respostas dos exercícios.
Seguidamente, terás de fazer ***commit*** e ***push*** das atualizações.

Alternativamente, podes preencher o ficheiro **README** diretamente no GitHub. A partir da página principal do repositório, clica em "Edit File" (ícone representando um lápis).
Com o **README** preenchido, carrega no botão "Commit Changes".

Para entregar a ficha, acede a [este link](https://docs.google.com/spreadsheets/d/1DrdGnICVAA8q9bs9_LAURFKoReAO7jJGB8qqvUWacL0/edit?usp=sharing) (separador **Teste Módulo 12**), e mete o **URL** do teu repositório ao lado do teu nome.
No teu repositório, acede a "Settings -> Collaborators -> Add People" e adiciona o utilizador "Manuel Geraldes" para ter acesso.

## P1 - Realiza os seguintes exercícios, com respostas detalhadas. (10v)
1. Explica a função dos modelos em sistemas de gestão bases de dados. Como contribuem para a estrutura e organização de dados? (3v)
é um software que deixa os utilizadores criar, manter e manipular os dados e o sgbd serve como uma ligaçao entre as base de dados e o utilizador.
como ao longo do tempo sao criados imensos dados e gerados precisamos de um local de grande armazenamento , gestao e acesso ao mesmo como tambem asseguram a integridade dos seus conteudos,se nao tivermos uma fonte centralizada podemos perder os dados e por isso tem o controlo de ficheirs, folhas de calculo e outros documentos. Tambme ajuda quando temos mais que um utilizador a usar a mesma conta para retirar os fundos sem um sistema bom e inteligente podem ocorrer inconsistencias. Outro exemplo é escalabilidade e desempenho um exemplo uma pagina online precisa de ter algma referencia sobre os produtos, se estiver com a forma de armazenar os dados de forma antiga o desempenho da pagina vai degradar comforme os acessos vao subindo com isso usam mecanimos como indexaçao caching e otimizaçao de consultas. E por ultimos temos a parte de backup e recuperaçao de dados, se algo importante esta num pc de um funcionario q se esqueceu de copiar eles as proprias base de dados colocam mecanismos q precisamos q asseguram a disponibilidade e a conservaçao dos ficheiros, criam copias constantes de ficheiros, dados e outras coisas importante e guardam num local seguro

2. Apresenta uma definição dos seguintes termos relacionados com bases de dados: (4v)
- Tabela
  Unidade básica de organização numa base de dados
- Chave estrangeira
  Coluna ou conjunto de colunas numa tabela que se refere à chave primária noutra tabela
- Índice
  Fornece acesso rápido a linhas específicas com base em colunas indexadas
- Normalização
  Processo de organizar dados para reduzir a redundância e melhorar a integridade dos mesmos
  
3. Descreve o conceito de redundância em bases de dados. Que riscos lhe estão associados, e como é que esta pode ser mitigada? (3v)

## P2 - Para cada uma das afirmações seguintes, indica se é **Verdadeira** ou **Falsa**. Justifica a tua escolha. (10v)
1. Bases de dados só são necessárias em empresas de larga escala, não sendo relevantes para pequenos negócios.
Falso. Bases de dados são relevantes para negócios de todos os tamanhos, incluindo pequenas empresas. Mesmo pequenos negócios podem se beneficiar do uso de bases de dados para armazenar e gerenciar informações importantes, como registros de clientes, inventário de produtos, transações financeiras, entre outros. O uso apropriado de bases de dados pode ajudar a melhorar a eficiência operacional, facilitar análises de dados, tomar decisões embasadas e manter a integridade dos dados, independentemente do tamanho do negócio.

  
2. Uma chave estrangeira numa base de dados assegura que um valor numa coluna de uma tabela tem de existir enquanto chave primária noutra tabela.
  Verdadeiro. Uma chave estrangeira em um banco de dados garante a integridade referencial, o que significa que um valor em uma coluna de uma tabela deve existir como chave primária em outra tabela. Isso ajuda a manter a consistência e a relação entre os dados em diferentes tabelas.
3. Bases de dados NoSQL não requerem um esquema pré-definido, para que possam conter dados.
Verdadeiro. Bases de dados NoSQL não requerem um esquema pré-definido, permitindo que possam conter dados de diferentes estruturas, o que as torna mais flexíveis em comparação com bases de dados relacionais tradicionais. Isso significa que as bases de dados NoSQL podem lidar com dados não estruturados ou semi-estruturados de forma eficaz.
   
4. Numa base de dados, uma *query* é usada para inserir novos conteúdos.
   Falso. Em uma base de dados, uma query é usada para recuperar, atualizar, inserir ou excluir dados, dependendo do tipo de operação que está sendo realizada.
5. Redundância em dados pode levar a inconsistências e anomalias numa base de dados.
Verdadeiro. A redundância de dados em uma base de dados pode levar a inconsistências e anomalias, como a inserção, atualização ou exclusão de dados de forma inconsistente, o que pode resultar em dados duplicados, desatualizados ou até mesmo contraditórios. 
