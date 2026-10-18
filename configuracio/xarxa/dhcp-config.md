# Configuració del servei DHCP

## 1. Activació del servei DHCP

S'activa el servei DHCP al router o servidor de la xarxa perquè assigne automàticament una adreça IP als equips connectats.

## 2. Rang d'adreces IP

Es configura el rang d'adreces dinàmiques des de `192.168.1.10` fins a `192.168.1.50`. Així, els equips poden rebre una IP automàticament dins d'aquest rang.

## 3. Porta d'enllaç

S'indica la porta d'enllaç per defecte, que és l'adreça IP del router que permet als equips comunicar-se amb altres xarxes.

## 4. Servidor DNS

S'indica l'adreça IP del servidor DNS, que permet traduir noms de domini, 
com ara `google.com`, a adreces IP.

## 5. Verificació amb tres equips de prova

Es connecten tres equips a la xarxa i es comprova que:

- [ ] El primer equip rep una adreça IP dins del rang configurat.
- [ ] El segon equip rep una adreça IP dins del rang configurat.
- [ ] El tercer equip rep una adreça IP dins del rang configurat.
- [ ] Els tres equips tenen configurades correctament la porta d'enllaç i el DNS.
- [ ] Es comprova la connectivitat de xarxa.
