1-Obtenir domini:

El primer que hem de fer es aconseguir el nostre domini, per aconseguir un hem de cercar la APP de DNS que hem instalat previament amb el nostre servei de DNS. Despres d'entrar en la APP trobarem el nostre servidor, al que hem de donar click dret i ens obrira una pestanya, de totes les opcions hem de seleccionar new zone. Una vegada dins d'aquest apartat hem de donar a Next fins arribar a zone name, que en el nostre cas volem que sigui el nostre cognom. Despres d'aixó, a la seguent pagina ens creara un domini anomenat gognom.dns, pero nosaltres l'hem de cambiar a cognom.cat. I per ultim donarem a seguent fins finalitzar.

![image](https://github.com/AitoDJ/deus-mp07-uf01-04-dns-win2020/assets/145341924/e283e86f-6a89-4d92-a918-e855662e56e1)

2-Obtenir HOST

Ara toca crear els hosts (o registres de tipus A) que relacionen un nom amb una adreça IP. Per crear un hem d'entrar en el nostre domini, fer click dret, donar-li a new host, i completar l'informacio.

![image](https://github.com/AitoDJ/deus-mp07-uf01-04-dns-win2020/assets/145341924/dc5e4993-d9d6-44c5-8402-c2cfcb5b1f5e)

3-Obtenir CNAME

Ara toca crear els alies (o registres de tipus CNAME) que relacionen un nom amb un altre nom. Per crear un CNAME hem de donar al click dret sobre el nostre dominim, i hem de selecionar l'opció de New Alias (CNAME). En el primer recuadre hem d'introduir el sobrenom o el alias, i en l'ultim recudre hem de cercar desde el browse el host al que fem referencia.

![image](https://github.com/AitoDJ/deus-mp07-uf01-04-dns-win2020/assets/145341924/197d95c5-5daf-41a4-aea7-7a5ac40a4fe3)

La seguent llista mostra la relació entre HOST i CNAME:
HOST            CNAME
izandeus        izan
sarajurado      sara
albertodeus     albertod
sergioacero     sergio
manolijurado    manoli
amparonaranjo   amparo
damariscastro   damaris
albertovaliño   albertov
laialopez       laia
ikerlopez       iker
davidaranda     david
alexvazquez     alex
xavimoreno      xavi

4-Obtenció registres de tipus MX

De vegades volem que alguns serveis especials, com el cas del servei de correu electrònic es relacionin amb un domini amb el HOST on s’ha d’entregar el correu. Per aquest motiu hem hem de crear un registre del tipus MX. Per crear un el que hem de fer es fer click dret sobre el nostre domini, i li donarem a crear New Mail Exanger. Una vegada dins trobarem que hem de completar una informació. El primer que hem d'introduir es el nom del Host, posteriorment, hem de donar-li a browse i cercarem el mail server que volem fer servir, i per ultim seleccionarem la prioritat del nostre servidor de correu.

![image](https://github.com/AitoDJ/deus-mp07-uf01-04-dns-win2020/assets/145341924/8ecdcaf8-9b2e-40ed-be92-655e9489a1d9)



