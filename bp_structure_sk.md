## BP-Varich Štruktúra

## **1. Introduction (Úvod)**

(„čo predstavuje moja práca“)

* Kontext: robotika, rastúce výpočtové požiadavky
* Problém: úzke miesta (bottlenecks) pri spracovaní dát
* Prečo je optimalizácia dôležitá (CPU vs GPU, real-time)
* Cieľ práce
* Úlohy (môžu byť prevzaté priamo zo zoznamu)
* Stručne: čo bolo vykonané (Apriltag, DNN, VSLAM, Isaac ROS)

---

## **2. Background and Related Technologies (Teoretické pozadie a súvisiace technológie)**

### 2.1 NVIDIA Isaac ROS

* čo to je
* na čo slúži
* GPU akcelerácia, NITROS a pod.

### 2.2 Robotické úlohy

* tie, ktoré sú dostupné v NVIDIA Isaac ROS
* porovnanie s ich analógmi

---

## **3. Selection of Robotic Tasks (Výber robotických úloh)**

* Prečo boli vybrané:

  * Apriltag
  * DNN inference
  * Visual SLAM

* Kritériá výberu:

  * rôznorodosť (lokalizácia, percepcia)
  * výpočtová náročnosť
  * použiteľnosť, jednoduchosť začiatku

---

## **4. Experimental Environment (Experimentálne prostredie)**

(moje prostredie)

* hardvér (GPU, CPU)
* softvér (ROS2, Isaac ROS)
* kontajnery / Docker
* štruktúra systému

---

## **5. Performance Metrics (Výkonnostné metriky)**

* FPS
* Latencia
* Priepustnosť (Throughput)
* Využitie CPU/GPU
* Pamäť

- vysvetlenie:

* prečo boli vybrané
* ako sa merajú
* obmedzenia

- zmienka:

* `ros2_benchmark`
* `isaac_ros_benchmark`

---

## **6. Experimental Methodology (Experimentálna metodológia)**

Zahrnúť:

* ako sú experimenty navrhnuté
* čo znamená Node vs Graph
* štruktúra pipeline
* konfigurácie
* **férové porovnanie (veľmi dôležité)**
* reprodukovateľnosť experimentov

---

## **7. Experimental Results (Experimentálne výsledky)**

Rozdeliť sekciu podľa úloh

### **7.1 Apriltag Detection**

* teória
* balíky
* datasety
* metriky kvality
* konfigurácie
* výsledky
* záver

---

### **7.2 DNN Inference**

(rovnaká štruktúra)

---

### **7.3 Visual SLAM**

(rovnaká štruktúra)

---

## **8. Cross-Task Analysis (Analýza naprieč úlohami)**

* porovnanie medzi úlohami
* kde GPU prináša najväčší prínos
* kde vznikajú úzke miesta
* všeobecné vzory

---

## **9. Conclusion (Záver)**

* čo bolo dosiahnuté
* či bol cieľ splnený
* obmedzenia
* budúca práca

---

## **10. References (Literatúra)**

(zdroje)

---

## **11. Appendices (Prílohy)**

### 1. Konfigurácie

* YAML súbory
* launch súbory
* benchmark konfigurácie

---

### 2. Skripty

* moje balíky
* automatizačné skripty
* bash / python

---

### 3. Dodatočné výsledky

* veľké tabuľky
* logy
* grafy

---

### 4. Informácie o datasetoch

* odkazy
* štruktúra

---

### 5. GitHub

Správny spôsob:

> All source code and experiment configurations are available at:
> **GitHub repository: [link]**

👉 V prílohe:

* štruktúra repozitára
* popis

---
