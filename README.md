# labbar2026

### Namn: William avramidis
### Datum: 2026-10-01
### kurs ICX26/git och dokumentation 


=======
### Beskrivning 

### Jag har använt Oracle virtualbox där två VMs finns, ett virtuellt nätverk kopplades mellan datorerna (internal network) och datorerna fick varsin statisk IP address och ligger på sammma subnät.

|Info|Dator1|Dator2|

|---|---|---|

|Hostname|wille|Labbb

|OS|Win11|Linux Ubuntu 26.02|

|ip adress|192.168.10.15|192.168.10.10|

|subnätmask|255.255.255.0|255.255.255.0|

|Standard gateway|192.168.10.1|192.168.10.1|



 ## Kommandon som användes för information.
1: Linux
Hostname visar hostname



cat /etc/os-release

Ip a - visar  IP address och subnät

ip route default gateway 192.168.10.1


2: Windows 
Hostname

systeminfo

ipconfig 




## Windows Uppgifter
* Skapade en mapp i c: med kommandot New-item-Itemtyp Directory -Path c\Systementor\Konsultdata

* Rättigheter för mappen Konsultdata

* Pingade Linux

* Ipconfig





## Linux bash
* Skappade en mapp med hjälp av kommandot mkdir 
 
* Tilldelade till Gruppen consult

* Rättigheter 750/640 på huvudmappen och underfilen och 640 på filen

* Rättighetslistan 




* Ping till windows 11



## Länk till GitHub och logg av commits




## AI logg och UTVÄRDERING

Prompten var följande Ge mig information om hur IPconfig /all fungerar och vilka scenarion är det viktigt att använda det
https://chatgpt.com/uc/6abe2bc6-b770-83ea-b34a-0568a37f8585 

Detta var svaret och det var korrekt då den beskriver i vilka scenario som Ipconfig /all kan användas i och visar exempel när det kan vara använtbart tex flushdns eller renew, samt visar vilka andra commandos som kan användas med hjälp av Ipconfig / dns tex och beskriver vad /all gör exakt men också ger ut information om vad exakt de dem gör och vad som kommer hända om den kommandos körs. Den informationen de gav, stammer väldig bra om man jämför med andra källor:
https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/ipconfig
https://www.teamviewer.com/en/insights/what-does-ipconfigall-do/





