# Generator formulárů pro INBAS 

### Instalace INBAS S-Pipes

Generator formulárů pro systém INBAS pozostává z dvou částí:

1) Definice skriptů pro generování formulárů je obsažena v stejné složce jako tento soubor. Zde je nastaveni adresy RDF4J serveru (viz. sekce bind-rdf4j-server / sml:value). Implicitni hodnota je "http://localhost:8080/rdf4j-server". RDF4J server musi být přístupný ze všech klientů systému INBAS (stroje které pouští webovú aplikaci INBAS). S Implicitní hodnotou je tedy možné pouštet generování formulárů jen ze stejného stroje. Pro pouštení INBAS systému z libovolné lokace je potřeba hodnotu změnit např. na veřejnou IP adresu stroje, kde je INBAS S-Pipes nainstalována. 

2) Aplikace s-pipes (https://kbss.felk.cvut.cz/web/portal/s-pipes) je obsažena vo webovom archíve s-pipes.war. Tento archiv obsahuje soubor config.properties, ktery odkazuje na adresar definice skriptů v promenné scriptsDir.

### Sestavení S-Pipes ze zdrojových souborů

WAR archiv je možné vytvořit i ze zdrojových souborů webové aplikace S-Pipes. Zdrojové soubory lze získat ze stránky https://kbss.felk.cvut.cz/web/portal/s-pipes. Archiv obsahuje soubor README.md, který popisuje jak takýto archiv vytvořit a nakonfigurovat.
