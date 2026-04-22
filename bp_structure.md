## BP-Varich Структура

## **1. Introduction**

(«что означает моя работа»)

* Контекст: роботика, рост вычислительных требований
* Проблема: bottlenecks в обработке данных
* Почему важна оптимизация (CPU vs GPU, real-time)
* Цель работы
* Задачи (можно прямо из твоего списка)
* Кратко: что ты сделал (Apriltag, DNN, VSLAM, Isaac ROS)

---

## **2. Background and Related Technologies**

### 2.1 NVIDIA Isaac ROS

* что это такое
* зачем нужен
* GPU acceleration, NITROS и т.д.

### 2.2 Роботические задачи
  * Те что в принципе имеются у Nvidia isaac ros,
  * Сопоставление с их аналогами.

---

## **3. Selection of Robotic Tasks**

* Почему выбраны:

  * Apriltag
  * DNN inference
  * Visual SLAM
  
* Критерии выбора:
  * разнообразие (Локализация, Перцепция)
  * нагрузка
  * применимость, лекгость в начинании)

---

## **4. Experimental Environment**

(мой environment)

* железо (GPU, CPU)
* софт (ROS2, Isaac ROS)
* контейнеры / Docker
* структура системы

---

## **5. Performance Metrics**

* FPS
* Latency
* Throughput
* CPU/GPU usage
* Memory

- объяснение:

* почему выбраны
* как измеряются
* ограничения

- упоминание:

* `ros2_benchmark`
* `isaac_ros_benchmark`

---

## **6. Experimental Methodology**

Сюда собрать:

* как устроены эксперименты
* что такое Node vs Graph
* pipeline структура
* конфигурации
* **fair comparison (очень важно)**
* повторяемость экспериментов

---

## **7. Experimental Results**

Разделить раздел по задачам

### **7.1 Apriltag Detection**

* теория
* пакеты
* датасеты
* метрики качества
* конфигурации
* результаты
* вывод

---

### **7.2 DNN Inference**

(то же самое)

---

### **7.3 Visual SLAM**

(то же самое)

---

## **8. Cross-Task Analysis**


* сравнение задач между собой
* где GPU дает больше выигрыша
* где bottlenecks
* общие закономерности

---

## **9. Conclusion**

* что получилось
* достиг ли цели
* ограничения
* future work

---

## **10. References**

(источники)

---

## **11. Appendices (Приложения)**


### 1. Конфигурации

* YAML файлы
* launch файлы
* benchmark configs

---

### 2. Скрипты

* my packages
*  automation scripts
* bash / python

---

### 3. Дополнительные результаты

* большие таблицы
* логи
* графики

---

### 4. Dataset info

* ссылки
* структура

---

### 5. GitHub

Вот как правильно:

> All source code and experiment configurations are available at:
> **GitHub repository: [link]**

👉 А в приложении:

* структура репозитория
* описание

---
