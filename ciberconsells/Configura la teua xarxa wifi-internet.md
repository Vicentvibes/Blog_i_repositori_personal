# COMPRÉN I CONFIGURA LA TEUA XARXA WIFI (INTERNET)

L'objectiu d'aquest blog és donar a entendre amenament la majoria de conceptes importants i relatius a la instal·lació d'internet en la nostra llar. Començarem explicant tota una sèrie de conceptes, aparells i protocols. Més endavant es donaràn alguns consells per configurar la nostra xarxa privada. 

## Què és internet?

Inter- és un sufixe que significa "entre varios". Net en anglés significa xarxa. Per tant, internet significa "xarxa entre varios". Podem pensar en internet com un sistema de correus amb una capàcitat de càrrega i velocitat redículament superiors a qualsevol altre servei de correus postal o paqueteria. És un servei de missatgeria que empra una insfraestructura sofisticada i novedosa per a l'ésser humà. Els missatges/paquets que transporta són dades produïdes per màquines i pensades per ser rebudes per altres màquines. El seu mitjà de transport són ones electromagnètiques (Wi-Fi, cobertura del mòbil, cobertura per satel·lit...), mitjançant impulsos elèctrics (cables de coure) o impulsos lumínics ([fibra òptica](https://www.youtube.com/watch?v=_OywbkAIJq0)). Ara ja tenim una idea pràctica de què és internet. Però, si és com un sistema de correu postal o paqueteria, quines són les adreces?

## IP 
És ben conegut el concepte de IP, però no és tan popular saber què significa i implica. IP són les sigles de Internet Protocol i és bàsicament un identificador/adreça que serveix per identificar de forma única els aparells connectats a internet. Hui dia hi ha dos versions de les IP, les IPv4 i les IPv6. La funció de cada versió és la mateixa, però canvien el seu format. Les Ipv4 estàn formades per quatre nombres entre 0 i 255 separats per un punt (.), per exemple: 192.168.1.254, 10.0.0.5, 78.233.241.1... Les IPv6 són més llargues i complexes. Estan formades per fins a 8 grups de 4 caràcters separats per dos punts (:) i que poden ser dígits entre 0 i 9 i lletres entre A i F. Alguns exemples són: 2001:0db8:85a3:0000:0000:8a2e:0370:7334, fe80::1ff:fe23:4567:890a, 2001:db8:85a3::8a2e:370:7334...

IPv6 es va desenvolupar degut a que les direccions IPv4 corren el risc d'esgotar-se per culpa de la expansió que ha patit internet a nivell global. Ara mateix ens trobem en una transició on els aparells moderns solen tindre una IPv4 i altra IPv6, l'objectiu és que en un futur sols hi hagen IPv6, ja que no correm risc de exhaurir les possibles combinacions d'aquesta versió. Fins aleshores, hi ha una classificació important sobre les IP que cal saber. Les IP poden ser:

- IP privada: són direccions que s'utilitzen per identificar aparells dintre d'una xarxa local. És a dir, són direccions IP que el nostre router assigna dinàmicament (dinàmicament vol dir que segons ens connectem a internet i eixim de casa, aquestes direccions IP poden canviar) als aparells que estàn connectats a internet a través d'ell. Per exemple, les IP del vostre mòbil, ordinador i televisió quan estan connectats a l'internet de casa són IP privades. Aquestes direccions IP estàn dintre dels següents rangs: 10.0.0.0 a 10.255.255.255, 172.16.0.0 a 172.31.255.255 i 192.168.0.0 a 192.168.255.255.
- IP pública: És l'adreça que identifica a una xarxa a nivell global. Això vol dir que "l'internet" de la nostra llar té un identificador únic i que si algú ens vol manar un whatsapp, l'enviarà a aquesta direcció IP i el nostre router s'encarregarà de reenviar-lo únicament al nostre smartphone. Per ficar altre exemple, quan vegem una pel·lícula en netflix el que fem és comunicar-nos amb els servidors de netflix emprant la IP pública d'aquestos, ells ja s'apanyen com calga per manar-nos la pel·lícula que volem vore.

Recopilem breument. Ja sabem vagament què és internet i que les IP són les nostres adreces d'intre d'internet. Podem inferir que les IP públiques i privades funcionen com si foren les direccions de carrer i nombre (IP pública) i per rematar la transmisió, la direcció de la nostra porta i pis (IP privada) dintre del nostre edifici. Però, falta una cosa: Com saben els aparells electrònics qui és qui? Com s'identifiquen els uns als altres? Si ja tenim l'adreça del missatge, no ens falta el nom del destinatari? Efectivament, vegem què són les MAC?

## MAC
Una MAC (Media Access Control) és un identificador únic de cada aparell electrònic que és capaç de connectar-se a internet. És un codi que funciona com un DNI per identificar aquestos parells. Aquest codi està gravat en les targetes de red (els xips encarregats de connectar l'aparell a internet) i són molt difícils de modificar (si bé si que es pot mitjançant programari especialitzat, suplantar temporalment una MAC). 




