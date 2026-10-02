# labbar2026

### Namn: William avramidis
### Datum: 2026-10-01
### kurs ICX26/git och dokumentation 


=======
### Beskrivning 

### Jag har använt Oracle virtualbox där två VMs finns, ett virtuellt nätverk kopplades mellan datorerna (internal network) och datorerna fick varsin statisk IP address och ligger på sammma subnät.

| Hostname      | Operativsystem  | IP-adress    | Subnätmask    | Standard Gateway |
|---------------|-----------------|--------------|---------------|------------------|
| wille         | Windows 11      | 192.168.10.10| 255.255.255.0 | 192.168.10.1     |
| ubuntu        | Ubuntu 26.04.1  | 192.168.10.15| 255.255.255.0 | 192.168.10.1     |




 ## Kommandon som användes för information.
1: Linux
Hostname visar hostname
<img width="238" height="56" alt="Image" src="https://github.com/user-attachments/assets/bca7e553-13e4-4d38-804d-a88f3b93cbee" />

cat /etc/os-release
<img width="702" height="248" alt="Image" src="https://github.com/user-attachments/assets/da4e4154-6778-4414-9df4-6cc02da0d3a0" />

Ip a - visar  IP address och subnät
<img width="1038" height="251" alt="Image" src="https://github.com/user-attachments/assets/c33e267e-7092-44ec-a661-3f0e96ab7fca" />

ip route default gateway 192.168.10.1


2: Windows 

Hostname
<img width="317" height="57" alt="Image" src="https://github.com/user-attachments/assets/0d94ff54-d36a-4d8b-8f94-b90cd515583a" />

systeminfo
<img width="564" height="132" alt="Image" src="https://github.com/user-attachments/assets/256819dc-32cb-4daa-a0c5-592769fac549" />

ipconfig 
<img width="619" height="176" alt="Image" src="https://github.com/user-attachments/assets/7b04c48d-6ef5-4bf7-92d7-443850a20629" />



## Windows Uppgifter
* Skapade en mapp i c: med kommandot New-item-Itemtyp Directory -Path c\Systementor\Konsultdata

<img width="906" height="280" alt="Image" src="https://github.com/user-attachments/assets/d86ca411-37de-4cd6-b798-f7479efad16c" />

* Rättigheter för mappen Konsultdata

<img width="1001" height="238" alt="Image" src="https://github.com/user-attachments/assets/fca67be4-36f3-4e24-8891-a3a69818820f" />

* Pingade Linux
<img width="607" height="228" alt="Image" src="https://github.com/user-attachments/assets/096fcfeb-23de-450b-a265-a5c66787ecd1" />

* Ipconfig
<img width="870" height="490" alt="Image" src="https://github.com/user-attachments/assets/fdcbd2a1-1048-44c6-868c-a4de90db230b" />



## Linux bash
* Skappade en mapp med hjälp av kommandot mkdir 
 <img width="574" height="36" alt="Image" src="https://github.com/user-attachments/assets/25a9e99b-c6cc-43d0-8b5b-b5a3724f47d0" />

* Tilldelade till Gruppen consult


* Rättigheter 750/640 på huvudmappen och underfilen och 640 på filen
<img width="818" height="150" alt="Image" src="https://github.com/user-attachments/assets/927ab38b-b7b2-4937-b60c-0d424efb7a75" />

* Rättighetslistan 
<img width="717" height="446" alt="Image" src="https://github.com/user-attachments/assets/bf0abf53-fdf5-453b-b21d-6cff885cc7dd" />
<img width="533" height="140" alt="Image" src="https://github.com/user-attachments/assets/8c327436-6207-42be-a164-e175435cf222" />



* Ping till windows 11
<img width="1307" height="690" alt="Image" src="https://github.com/user-attachments/assets/2489359f-40ca-4143-8250-323e16fa1acd" />



## Länk till GitHub och logg av commits

<img width="1262" height="74" alt="Image" src="https://github.com/user-attachments/assets/029a2af5-8607-4a29-ba26-da9b861fce97" />
<img width="1281" height="99" alt="Image" src="https://github.com/user-attachments/assets/0bfffe43-649e-4506-9a8a-d9ed7750bbc6" />
<img width="1279" height="147" alt="Image" src="https://github.com/user-attachments/assets/619d6aba-ebf4-4f25-b5dd-a2248e0a4ea0" />


## AI logg och UTVÄRDERING

Prompten var följande Ge mig information om hur IPconfig /all fungerar och vilka scenarion är det viktigt att använda det
https://chatgpt.com/uc/6abe2bc6-b770-83ea-b34a-0568a37f8585 

Detta var svaret och det var korrekt då den beskriver i vilka scenario som Ipconfig /all kan användas i och visar exempel när det kan vara använtbart tex flushdns eller renew, samt visar vilka andra commandos som kan användas med hjälp av Ipconfig / dns tex och beskriver vad /all gör exakt men också ger ut information om vad exakt de dem gör och vad som kommer hända om den kommandos körs. Den informationen de gav, stammer väldig bra om man jämför med andra källor:
https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/ipconfig
https://www.teamviewer.com/en/insights/what-does-ipconfigall-do/





