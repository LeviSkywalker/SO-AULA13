É um sistema de arquivo criado pela IBM, para o sistema operacional AIX, utilizado também para uso no GNU/Linux e posteriormente teve seu código fonte liberado.

Criado para uso de servidores corporativos. Sendo um sistema com estrutura inode, que armazena a localização dos blocos de cada arquivo nas estruturas do disco.

O JFS é formado pelas seguintes estruturas internas:

-Agregado: matriz de blocos de disco que inclui um superbloco e um mapa de alocação.
-Fileset: contém as estruturas de controle, sendo O superbloco agregado, o mapa de alocação de disco, o descritor de arquivos, o mapa de inodes, os inodes, os diretórios e as estruturas de endereçamento representam as estruturas de controle ou metadados do JFS.
-Logs: Os logs do JFS são mantidos em cada agregado e usados para gravar informações sobre operações nos metadados.
Journaling: armazena em logs os metadados.
JFS aloca dinamicamente o espaço para inodes de disco conforme sua necessidade, liberando esse espaço quando deixar de ser requerida. Esse suporte impede que os inodes se localizem em regiões fixas do disco. A versão JFS2 armazena esses I-nodes em uma árvore binária utilizada para acelerar o acesso a essas informações e, conseqüentemente, aumentar a velocidade de acesso aos dados dos arquivos
512 a 4096 bytes.
Cluster size: n/a
maximum file size: n/a
maximum file size:4096 bytes.
