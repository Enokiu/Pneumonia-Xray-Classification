# 🧠 Pneumonia Xray Classification 

Dieses Projekt zielt darauf ab, **mithilfe von Röntgenaufnahmen der Brust Lungenentzündungen (Pneumonie) automatisch zu erkennen und korrekt zu klassifizieren**.

Die gesamte Pipeline umfasst:

- **Visuelle Analyse und Aufbereitung** des Datensatzes
- **Data Augmentation** zur Verbesserung der Klassenbalance
- Aufbau eines eigenen **Convolutional Neural Networks (CNN)**
- **Trainings- und Validierungsschritte**
- **Evaluation** der Modellleistung
- Eine **Live-Demo auf echten Testbildern**

## 📓 Jupyter Notebook

Alle Schritte sind ausführlich dokumentiert, visuell aufbereitet und mit Erklärungen versehen, einschließlich der Überlegungen hinter jedem Schritt.

&#8594; **Notebook öffnen:** [`Pneumonia_Xray_Classification.ipynb`](./Pneumonia_Xray_Classification.ipynb)

## 🛠 Voraussetzungen

- Python 3.8.20 (in dieser Umgebung entwickelt=
- PyTorch  
- torchvision  
- matplotlib  
- seaborn  
- Pillow  
- numpy  
- scikit-learn  
- tqdm  
- kagglehub  
- Jupyter Notebook

Alle Bibliotheken kannst du bequem mit der Datei `requirements.txt` installieren:

```bash
pip install -r requirements.txt
```
⚠️ Hinweis: Die `requirements.txt` enthält absichtlich keine festen Versionsnummern.  
Bitte stelle sicher, dass du die zu deinem System (z. B. CUDA-Version) passende PyTorch-Version installierst:  
&#8594; [PyTorch Get Started](https://pytorch.org/get-started/locally/)


## 📁 Daten

Die Daten stammen aus dem [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) Datensatz auf Kaggle. Bitte lade sie dort herunter und speichere sie im entsprechenden Verzeichnis (z. B. `../chest_xray/`).

## 🚀 Projekt starten

```bash
git clone https://github.com/dein-username/Pneumonia-Xray-Classification.git
cd Pneumonia-Xray-Classification
jupyter notebook Pneumonia_Xray_Classification.ipynb
```
