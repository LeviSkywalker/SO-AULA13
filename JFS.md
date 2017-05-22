É um sistema de arquivo criado pela IBM, para o sistema operacional AIX, utilizado também para uso no GNU/Linux e posteriormente teve seu código fonte liberado.

Criado para uso de servidores corporativos. Sendo um sistema com estrutura inode, que armazena a localização dos blocos de cada arquivo nas estruturas do disco.

O JFS é formado pelas seguintes estruturas internas:

-Agregado: matriz de blocos de disco que inclui um superbloco e um mapa de alocação.
-Fileset: contém as estruturas de controle, sendo O superbloco agregado, o mapa de alocação de disco, o descritor de arquivos, o mapa de inodes, os inodes, os diretórios e as estruturas de endereçamento representam as estruturas de controle ou metadados do JFS.
-Logs: sim
-cluster :4096 bytes


