
## **Titlul Lucrării:** YieldCMS - Sistem de management al conținutului  
#### PROIECT PENTRU OBŢINEREA ATESTĂRII PROFESIONALE ÎN INFORMATICĂ   
---  

**Nume:** Wiliam-Ioan Toader  
**Clasa:** a XII-a A  
*Colegiul Național „Nicolae Bălcescu”*  
**Profesor coordonator:** Mădalina Nicolae  

---  

### Cuprins  

1. [Introducere](#Introducere)  
2. [Structura aplicației](#Structura-aplicației)  
3. [Detalii tehnice](#Detalii-tehnice)  
4. [Procesul de dezvoltare](#Procesul-de-dezvoltare)  
5. [Resurse de hardware si software](#Resurse-de-hardware-si-software)  
6. [Funcționalitate](#Funcționalitate)  


# Introducere  
Proiectul are ca scop crearea unei platforme ce poate fi folosită pentru administratea conținutului static de pe un site web. La baza sa se află o interfață web prin care se pot administra individual paginile site-ului cât și structura și ordinea link-urilor din bara de navigație. Crearea/Actualizarea paginilor de tip articol nu necesită editarea manuală a codului sursă, deoarece am integrat in platformă o componentă de editor WYSIWYG [Summernote](https://summernote.org/). Deoarece ansamblul de componente software folosite în acest proiect este unul amplu care necesită configurarea unui server HTTP, a unei baze de date și setarea unor parametri ce țin de conexiune, pentru a demonstra funcționalitatea platformei am dezvoltat o soluție de instalare rapidă pe baza unui container Docker, care acționează precum o mașină virtuală, oferind un mediu similar cu cel al unui sistem de operare, în care am preîncărcat toate componentele software pe care se bazează platforma, ele fiind preconfigurate pentru a oferi o experiență demonstrativă cât mai simplu de pus în funcțiune, urmând să recomand câteva modalități de a rula proiectul.  
  
## Ghid rapid de instalare  
Recomand folosirea uneia din următoarele platforme deoarece acestea oferă gratuit accesul la mașini virtuale găzduite prin intermediul cărora proiectul poate fi instalat cu o singură comandă.  
- Google Cloud Platform Cloudshell  
- Play with Docker  

În cazul în care acestea nu sunt disponibile, pe DVD-ul inclus se va afla o imagine precompilată a sistemului de operare în format container, care poate fi instalată local pe majoritatea distribuțiilor moderne de linux(sau Windows 10 prin intermediul Windows Subsystem for Linux) prin intermediul suitei [Docker Engine](https://docs.docker.com/engine/install/).  
  
### Instalarea pe Google Cloud Platform Cloudshell  
Se va intra pe adresa `https://cloud.google.com/shell`  
![Cloudshell](https://github.com/williamtoader/documentatie-proiect-atestat/blob/main/cloudshell-screenshots/cs.png?raw=true)  
![Cloudshell](https://github.com/williamtoader/documentatie-proiect-atestat/blob/main/cloudshell-screenshots/1.PNG?raw=true)  
![Cloudshell](https://github.com/williamtoader/documentatie-proiect-atestat/blob/main/cloudshell-screenshots/2.PNG?raw=true)  
![Cloudshell](https://github.com/williamtoader/documentatie-proiect-atestat/blob/main/cloudshell-screenshots/3.PNG?raw=true)  

---  
  
Se va copia comanda  
`docker run -it --env YIELD_DOMAIN=.cloudshell.dev -p 8080:8080 wiliamtoader/yieldcms:demo`  
și se va insera în terminal cu `Shift + Insert` după care se dă `Enter`  
  
---  
  
![Cloudshell](https://github.com/williamtoader/documentatie-proiect-atestat/blob/main/cloudshell-screenshots/4.png?raw=true)  
![Cloudshell](https://github.com/williamtoader/documentatie-proiect-atestat/blob/main/cloudshell-screenshots/5.png?raw=true)  
![Cloudshell](https://github.com/williamtoader/documentatie-proiect-atestat/blob/main/cloudshell-screenshots/6.png?raw=true)  
![Cloudshell](https://github.com/williamtoader/documentatie-proiect-atestat/blob/main/cloudshell-screenshots/7.png?raw=true)  

# Structura aplicației  

# Detalii tehnice  

# Procesul de dezvoltare  

# Resurse de hardware si software  

# Funcționalitate  

# Prevederi privind instalarea manuală a soluției  
