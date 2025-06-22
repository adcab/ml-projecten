# 🧠 Simpele Machine Learning Projecten met Uitleg

Welkom! Deze repository bevat een reeks **interactieve Jupyter Notebooks** met eenvoudige maar leerzame Machine Learning-projecten. Elk project is zorgvuldig opgebouwd en bevat **uitgebreide uitleg bij elke stap**, zodat ook beginners makkelijk kunnen volgen.

## 📚 Wat vind je hier?

### 1. **Productiviteit Voorspellen**
> Voorspel je productiviteit op basis van factoren zoals slaap, schermtijd en focus.
- Type: Regressie
- Model: RandomForestRegressor
- Data: Gesimuleerde dagelijkse gewoontes

### 2. **Handgeschreven Cijfers Herkennen – MNIST**
> Een klassiek beeldherkenningsproject met cijfers (0–9).
- Type: Classificatie
- Model: Support Vector Machine (SVM)
- Dataset: `sklearn.datasets.load_digits`

### 3. **CIFAR-10 – Deep Learning (CNN)**
> Herken objecten (hond, kat, vliegtuig...) in kleurafbeeldingen met een neuraal netwerk.
- Type: Beeldclassificatie
- Model: Convolutional Neural Network (CNN)
- Framework: TensorFlow / Keras

### 4. **CIFAR-10 – Klassiek ML (SVM + PCA)**
> Zelfde dataset als hierboven, maar met klassieke Machine Learning (zonder deep learning).
- Type: Classificatie
- Model: Support Vector Machine
- Voorbewerking: PCA-dimensiereductie

### 5. **Logistische Regressie met Epochs**
> Classificatieprobleem met logistische regressie waarbij het leerproces per iteratie zichtbaar is.
- Model: LogisticRegression / SGDClassifier
- Doel: Leren begrijpen van iteratief leren

---

## 🔍 Doel van deze repo

Deze notebooks zijn bedoeld voor:
- Beginners in Machine Learning
- Educatieve workshops of presentaties
- Iedereen die wil begrijpen **wat er onder de motorkap gebeurt**

Elke notebook bevat:
- Heldere uitleg in Markdown
- Uitvoerbare Python-code
- Visualisaties & interpretaties

---

## ▶️ Gebruik

Je kunt de notebooks openen in:
- [Google Colab](https://colab.research.google.com)
- Jupyter Notebook / JupyterLab
- VSCode met Python-extension

---

## 📥 Installatie

Zorg dat je Python 3 en de volgende libraries hebt geïnstalleerd:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn tensorflow
