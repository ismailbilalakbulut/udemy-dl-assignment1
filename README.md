# Derin Öğrenme 2026: 100 Günlük Kamp - Ödev 1: Doğrusal Olmayan Veri Sınıflandırması

[English](#english) | [Türkçe](#türkçe)

<a name="english"></a>
## English

This repository contains the first assignment (Task-1-NonLinear) of the **Deep Learning 2026: 100 Days of Code** course by Atıl Samancıoğlu.

### Table of Contents
- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Libraries Used](#libraries-used)
- [Model Architecture and Training](#model-architecture-and-training)
- [Visualizations](#visualizations)
- [Files](#files)

### About the Project
In this study, binary classification was performed using PyTorch on seismic activity data with a non-linear structure. The nature of the data was analyzed, and non-linear decision boundaries were plotted.

### Dataset
The dataset used in this project: `08-seismic_activity_svm.csv` consisting of 400 rows and 3 columns:
- `underground_wave_energy`: Underground wave energy (float)
- `vibration_axis_variation`: Vibration axis variation (float)
- `seismic_event_detected`: Seismic event detection (0 or 1) (int)

### Libraries Used
- `torch`
- `pandas`
- `matplotlib`
- `seaborn`
- `numpy`
- `mpl_toolkits.mplot3d`

### Model Architecture and Training
The PyTorch model was created with the following steps:
1. **Data Preparation:** Loading and splitting the dataset into training and test sets.
2. **Loss Function:** `BCEWithLogitsLoss` was used.
3. **Optimization:** Adam optimizer with a learning rate of 0.001.
4. **Training:** Trained for 401 epochs, achieving 100% accuracy.

### Visualizations
- 2D scatter plot of seismic activities.
- 3D data visualization.
- Decision boundary plots for the training and test sets.

### Files
- `Task-1-NonLinear.ipynb`: Jupyter Notebook containing all the project steps.
- `08-seismic_activity_svm.csv`: Dataset used in the assignment.

---

<a name="türkçe"></a>
## Türkçe

Bu depo, Atıl Samancıoğlu tarafından hazırlanan **Derin Öğrenme 2026: 100 Günlük Kamp** kursunun ilk ödevini (Task-1-NonLinear) içermektedir.

### İçindekiler
- [Proje Hakkında](#proje-hakkında)
- [Veri Seti](#veri-seti)
- [Kullanılan Kütüphaneler](#kullanılan-kütüphaneler)
- [Model Mimarisi ve Eğitim](#model-mimarisi-ve-eğitim)
- [Görselleştirmeler](#görselleştirmeler)
- [Dosyalar](#dosyalar)

### Proje Hakkında
Bu çalışmada, doğrusal olmayan (non-linear) bir yapıya sahip olan sismik aktivite verisi üzerinde PyTorch kullanılarak ikili sınıflandırma (binary classification) yapılmıştır. Verinin doğası incelenmiş ve doğrusal olmayan karar sınırları çizdirilmiştir.

### Veri Seti
Projede kullanılan veri seti: `08-seismic_activity_svm.csv` olup, 400 satırdan ve 3 sütundan oluşmaktadır:
- `underground_wave_energy`: Yeraltı dalga enerjisi (float)
- `vibration_axis_variation`: Titreşim ekseni değişimi (float)
- `seismic_event_detected`: Sismik olay tespiti (0 veya 1) (int)

### Kullanılan Kütüphaneler
- `torch`
- `pandas`
- `matplotlib`
- `seaborn`
- `numpy`
- `mpl_toolkits.mplot3d`

### Model Mimarisi ve Eğitim
Ödev kapsamında bir PyTorch modeli oluşturulmuş ve aşağıdaki adımlar izlenmiştir:
1. **Veri Hazırlığı:** Veri setinin yüklenmesi ve eğitim/test kümelerine ayrılması.
2. **Kayıp Fonksiyonu:** `BCEWithLogitsLoss` kullanılmıştır.
3. **Optimizasyon:** `Adam` optimizasyon algoritması (öğrenme oranı = 0.001) kullanılmıştır.
4. **Eğitim:** Model 401 epok boyunca eğitilmiş ve %100 doğruluk (accuracy) oranına ulaşılmıştır.

### Görselleştirmeler
- Sismik aktivitelerin 2 boyutlu saçılım grafiği (scatter plot).
- 3 boyutlu veri gösterimi.
- Eğitim ve test setleri için karar sınırı (decision boundary) grafikleri.

### Dosyalar
- `Task-1-NonLinear.ipynb`: Projenin tüm adımlarını içeren Jupyter Notebook dosyası.
- `08-seismic_activity_svm.csv`: Ödevde kullanılan veri seti.
