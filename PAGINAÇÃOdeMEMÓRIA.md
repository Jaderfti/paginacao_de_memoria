#Memória RAM

Memória RAM é um hardware de armazenamento randômico e volátil de memória. Isto significa que esta peça armazena dados de programas em execução enquanto o computador está ligado. RAM do inglês Random Access Memory e significa Memória de Acesso Aleatório. 

A memória RAM tem acesso rápido e é essencial para acompanhar a velocidade do processador. A memória RAM recebe as informações do HD, e as armazena temporariamente, disponibilizando este conteúdo ao processador. Seria muito mais lenta a execução de um programa caso o processador tivesse que procurar os dados diretamente do HD.

Um exemplo da utilidade da memória RAM é um documento de texto. Enquanto o usuário está digitando e editando o texto, os dados ficam na memória RAM. Após o arquivo ser salvo em um diretório, passa a ser armazenado no disco rígido.

Caso haja algum problema com a máquina e a mesma desligue enquanto o texto está sendo editado, as informações serão perdidas, e a última informação salva estará no HD.

Tipos de memória RAM

Existem 4 memórias RAM no mercado, basicamente: DDR, DDR2  DDR3 e DDR4, sendo a DDR4 a mais potente no mercado atual. Cada um destes tipos de memória tem uma velocidade que é medida em MHz. 

#Memória ROM

ROM significa Read-Only Memory, ou Memória Somente de Leitura é encontrada principalmente no chip responsável pela iniciação do sistema e é lá que as informações básicas do computador ficam armazenadas, portanto não são afetadas quando o dispositivo é desligado.

Memórias RAM são encontradas em diversos tipos de dispositivos, como computadores, impressoras e smartphones. Já memórias do tipo ROM são equipadas em chips da BIOS, por exemplo, além de mídias físicas como CD-ROMs e os antigos cartuchos de vídeo-game.

#SWAP

O que é SWAP?

Podemos dizer que seja uma técnica computacional usada pelos sistemas operacionais para aumentar quantidade de memória real do computador a fim de rodar os programas e o próprio sistema sem travamentos.

Essa memória virtual que vai auxiliar a memória RAM fica armazenada no seu HD e tem diferenças de sistema para sistema, porém cumpre a mesma função.

O swap pode ficar tanto em uma partição, quanto em um arquivo no disco. No caso de ficar numa partição em um disco comum (não-SSD), recomenda-se colocar a partição no início do disco, assim a leitura durante a rotação do disco magnético é mais rápida. No caso de partições em disco SSD, tanto faz pois não há rotações como um disco comum. Algumas distribuições, como Debian e Ubuntu, tem no instalador uma opção para colocar a partição no início do disco.

Importante lembrar que o swap é bem mais lento que a memória RAM. Se você colocar swap demais num sistema e começar a usá-lo muito você vai ganhar uma grande de uma lentidão.

#Paginação de Memória

Paginação da memória do computador é um processo de virtualização da memória que consiste na subdivisão da memória física em pequenas partições, que são frames, para permitir-lhe uma utilização mais eficiente. As frames da memória física correspondem a páginas de memória virtual. A alocação de memória é requisitada por páginas, a menor unidade deste método. Cada página é mapeada numa frame de memória através de um processo que chama paginação.

A paginação é implementada normalmente por unidades dedicadas de hardware integradas nos processadores. No caso dos processadores da família Intel x86, esta funcionalidade está atribuída à MMU. A paginação é obtida através de consulta a tabelas que relacionam os endereços lineares das páginas de memória com os endereços físicos das frames de memória respectivas.

Neste sistema, cada processo no computador tem a sua própria tabela de páginas, em que a cada endereço virtual corresponde o endereço físico em que a informação está efectivamente armazenada. Visto que a informação está dividida em pequenas unidades, o seu armazenamento não tem de ser necessariamente sequencial, o que elimina a fragmentação externa da memória.
