# 🧠 NLP_DEVOIR – Soumaya Laakel

Ce projet regroupe une série de devoirs pratiques en Traitement Automatique du Langage Naturel (TALN/NLP), utilisant Python et des bibliothèques comme BeautifulSoup, Selenium, spaCy, etc.  
Chaque devoir correspond à une tâche ciblée pour manipuler, extraire, nettoyer ou analyser du texte provenant de diverses sources.

---

## 📚 Contenu des devoirs :

### 📄 DEVOIR 1 – Web Scraping (données statiques et dynamiques)
- Extraction de données depuis des pages web statiques avec **BeautifulSoup**
- Extraction depuis des pages dynamiques avec **Selenium**
- Comparaison des résultats des deux méthodes
- Fusion des données dans un **fichier CSV final**

---

### 📄 DEVOIR 2 – Extraction d’adresses emails depuis un PDF
- Extraction de toutes les adresses email contenues dans un fichier PDF
- Sauvegarde des résultats dans un **fichier CSV**

---

### 📄 DEVOIR 3 – Nettoyage, tokenisation et normalisation de texte médical

#### ✅ Exercice 1 – Nettoyage du texte :
- Suppression de :
  - Dates (`12/03/25`)
  - Valeurs avec unités (`125mg/L`)
  - Caractères spéciaux (`#`, `°`)
- Normalisation :
  - Abréviations (`Ttt` → `traitement`)
  - Fautes (`pat.` → `patient`)

#### ✅ Exercice 2 – Tokenisation médicale :
- Conserver les concepts composés (`COVID-19`)
- Séparer les doses et unités (`500mg/J` → `["500", "mg", "/", "J"]`)
- Utiliser un dictionnaire d’abréviations

#### ✅ Exercice 3 – Normalisation experte :
- Conversion de termes médicaux (`corticoïdes` → `glucocorticoïdes`)
- Traduction d'expressions spécifiques (`++fébrile` → `hyperthermique`)
- Correction de transcription (`hyp0glycémie` → `hypoglycémie`)

---

### 📄 DEVOIR 4 – Analyse syntaxique avec spaCy
- Analyse grammaticale d’une phrase en français
- Identification des catégories grammaticales (POS tagging)
- Analyse des dépendances (sujet, verbe, objet, compléments)
- Compréhension de la structure syntaxique et du **sens** de la phrase

---

### 📄 DEVOIR 5 – Analyse de comptes-rendus médicaux
- Extraction d’information à partir de textes médicaux non structurés
- Utilisation de techniques NLP pour :
  - Identifier relations patient–symptômes–traitements
  - POS tagging et dépendances grammaticales
  - Relations SVO (sujet-verbe-objet)
  - Détection de **négations**
- Structuration automatique des données cliniques pour des analyses ultérieures

---

## 🧰 Technologies utilisées

- Python
- BeautifulSoup, Requests
- Selenium
- spaCy
- re (expressions régulières)
- pandas
- PyMuPDF (pour les PDF)
- Jupyter Notebook

---

## 📂 Organisation

Chaque devoir est séparé dans un fichier `.ipynb`, nommé `DEVOIR_X.ipynb`.

---

## 📬 Contact

Réalisé par **Soumaya Laakel**  
📧 Email : soumayalaakel62@gmail.com 

---

