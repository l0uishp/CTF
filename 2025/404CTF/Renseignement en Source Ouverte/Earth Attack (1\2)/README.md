# Earth Attack (1/2)

**Événement :** 404CTF 2025  
**Catégorie :** Renseignement en Source Ouverte (OSINT)  
**Difficulté :** Difficile

---

## 📸 Description
![Image du challenge](img/challenge1.png)

## 🗂️ Ressources
Une capture d'écran de la conversation 
![Image du challenge](img/capture_conv.png)

---

## 🧩 Résolution

Bon pour ce challenge la premiere piste que j'ai suivi était celle de la localisaiton par les éléments de la convertation à savoir une mascotte de l'aérospatial donc plutot une entreprise francaise relativement ancienne qui rayonne dans le secteur de l'aérospatial. Proche d'une foret et avec une entrée sud. Aprés une premiere recherche avec Google et Google maps je tombe sur un poste de garde airbus defense and space répertorié sur Google maps et a coté de l'entrée sud du CNES, je me dis que je tient peut etre un truc meme si il n'y a pas de foret proche mais finalement celà ne donne rien. Je décide donc d'utiliser overpass turbo pour rechercher tous les batiements en lien avec l'aérospatial à moins de 10km d'une foret et un poste de garde ou une entrée sud mais celà ne donne rien de concluant. Aprés avoir relu le texte de la conversation pour la centieme fois je tique sur la structure en 3 phrases courtes et je me souviens d'un outils qui à n'importe quelle localisation associe 3 mots uniques et vice verca (https://what3words.com/) sans trop y croire je me demande quels most je vais utilser, commencont par les premiers de chaque pharses : mascotte, scier, parions et la bingo un point pile poil sur un batiment de Thales Avionics

---

## ✅ Flag  
404CTF{thales_avionics}

