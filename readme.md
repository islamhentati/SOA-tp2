# CalculatriceWS – Service Web SOAP avec Jakarta XML Web Services

TP2 – Architecture SOA et services web | LSI3-GLSI
Faculté des Sciences de Sfax | Année universitaire 2025-2026
**Réalisé par : Islem Henteti**


---

## 1. Description

*CalculatriceWS* est une application Java qui expose un service web *SOAP* de calculatrice. Elle propose quatre opérations : somme, soustraction, multiplication et division.

Le service est développé avec *Jakarta XML Web Services (JAX-WS)*, géré par *Maven*, publié avec Endpoint.publish et testé avec *SoapUI*.


### Activité 1 : Projet Maven

*Structure du projet*

![Structure du projet](image/h.png)

*Fichier pom.xml*

![pom.xml](image/l.png)



### Activités 2 et 3 : Interface, classe métier et annotations

**Interface ICalculatrice**

![Interface ICalculatrice](image/d.png)

**Classe Calculatrice**

![Classe Calculatrice](image/c.png)

### Activité 4 : Publication du service

**Classe ServeurJWS**

![Classe ServeurJWS](image/i.png)

*Console du serveur*

![Console du serveur](image/n.png)

voici url : http://localhost:8080/CalculatriceWS?wsdl

*WSDL généré*

![WSDL](image/m.png)



### Activité 5 : Tests avec SoapUI

*Création du projet SoapUI*

![Nouveau projet SoapUI](image/g.png)

*Opérations importées*

![Arborescence SoapUI](image/b.png)

**Opération somme**

![Somme](image/f.png)
![Somme](image/e.png)
**Opération soustraction**

![Soustraction](image/bb.jpg)

**Opération multiplication**

![Multiplication](image/a.png)

**Opération division**

![Division](image/aa.jpg)





## 12. Auteur

*islem henteti* – LSI3-GLSI – Faculté des Sciences de Sfax – 2026-2027  