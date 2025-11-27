# Earth Attack (0/2)

**Événement :** 404CTF 2025  
**Catégorie :** Renseignement en Source Ouverte (OSINT)  
**Difficulté :** Facile  

---

## 📸 Description
![Image du challenge](img/challenge.png)

---

## 🧩 Résolution

Sur le site du **BEA** (Bureau d’Enquêtes et d’Analyses pour la Sécurité de l’Aviation Civile), on trouve un moteur de recherche permettant de filtrer les incidents aériens.

En appliquant les filtres suivants :

- **Catégorie :** Avion  
- **Constructeur :** CESSNA  
- **Conséquences humaines :** Légère  
- **Type d'événement :** Panne moteur  
- **Autorité :** France  

… il ne reste **que 10 résultats**.

**Lien vers le moteur de recherche:**  
<https://bea.aero/les-enquetes/evenements-notifies/>

![Image du challenge](img/image1.png)


Le **premier résultat** est localisé à **Roura (973)**, une ville de **Guyane**, ce qui est particulièrement cohérent avec la thématique du 404CTF 2025. 
De plus le format de l'immatriculation de l'avion est la seulle à correspondre exactement avec le format du flag.

---

## ✅ Flag  
404CTF{9H-MDJ}
