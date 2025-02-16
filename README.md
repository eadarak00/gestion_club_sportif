## 🏆 Gestion Club Sportif  

#### 📌 Description  
Le projet **Gestion Club Sportif** est une application Java utilisant **Maven** et **JPA** pour gérer les adhérents d'un club sportif.  

---

### ⚙️ Technologies utilisées  
- **Java 17+**  
- **Maven** (Gestion des dépendances)  
- **JPA / Hibernate** (Persistance des données)  
- **Mariadb** (Base de données)  

---

### 📌 Fonctionnalités principales

✅ Gestion des adhérents : Ajouter, modifier, supprimer les membres du club  
✅ Gestion des sports :  Ajouter, modifier, supprimer les membres du club 
---

### 🛠 Installation et exécution  
1️⃣ **Cloner le projet**  
```sh
git clone https://github.com/eadarak00/gestion_club_sportif.git
cd gestion_club_sportif
```
2️⃣ **Construire le projet avec Maven**  
```sh
mvn clean install
```
3️⃣ **Exécuter l'application**  
```sh
mvn exec:java -Dexec.mainClass="com.example.club.MainApp"
```

---

### 📂 Structure du projet  
```
gestion_club_sportif/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── sn.uasz.m1.tp1/
│   │   │   │   ├── Main.java
│   │   │   │   ├── entity/
│   │   │   │   │   ├── Membre.java
│   │   │   │   │   ├── Sport.java
│   │   │   │   ├── dao/
│   │   │   │   │   ├── MembreDAO.java
│   │   │   │   │   ├── SportDAO.java
│   │   │   │   │   ├── JpaUtil.java
│   ├── resources/
│   │   ├── META-INF/
│   │   │   └── persistence.xml
├── pom.xml
├── .gitignore
├── README.md
```
