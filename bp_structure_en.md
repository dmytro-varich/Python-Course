## BP-Varich Structure

## **1. Introduction**

(“what my work represents”)

* Context: robotics, increasing computational requirements
* Problem: bottlenecks in data processing
* Why optimization is important (CPU vs GPU, real-time)
* Objective of the work
* Tasks (can be taken directly from your list)
* Briefly: what was done (Apriltag, DNN, VSLAM, Isaac ROS)

---

## **2. Background and Related Technologies**

### 2.1 NVIDIA Isaac ROS

* what it is
* why it is needed
* GPU acceleration, NITROS, etc.

### 2.2 Robotic Tasks

* those available in NVIDIA Isaac ROS
* comparison with their analogues

---

## **3. Selection of Robotic Tasks**

* Why selected:

  * Apriltag
  * DNN inference
  * Visual SLAM

* Selection criteria:

  * diversity (localization, perception)
  * computational load
  * applicability, ease of getting started

---

## **4. Experimental Environment**

(my environment)

* hardware (GPU, CPU)
* software (ROS2, Isaac ROS)
* containers / Docker
* system structure

---

## **5. Performance Metrics**

* FPS
* Latency
* Throughput
* CPU/GPU usage
* Memory

- explanation:

* why selected
* how they are measured
* limitations

- mention:

* `ros2_benchmark`
* `isaac_ros_benchmark`

---

## **6. Experimental Methodology**

Include here:

* how the experiments are organized
* what Node vs Graph means
* pipeline structure
* configurations
* **fair comparison (very important)**
* reproducibility of experiments

---

## **7. Experimental Results**

Divide the section by tasks

### **7.1 Apriltag Detection**

* theory
* packages
* datasets
* quality metrics
* configurations
* results
* conclusion

---

### **7.2 DNN Inference**

(same structure)

---

### **7.3 Visual SLAM**

(same structure)

---

## **8. Cross-Task Analysis**

* comparison between tasks
* where GPU provides the most benefit
* where bottlenecks occur
* general patterns

---

## **9. Conclusion**

* what was achieved
* whether the objective was reached
* limitations
* future work

---

## **10. References**

(sources)

---

## **11. Appendices**

### 1. Configurations

* YAML files
* launch files
* benchmark configs

---

### 2. Scripts

* my packages
* automation scripts
* bash / python

---

### 3. Additional Results

* large tables
* logs
* graphs

---

### 4. Dataset Info

* links
* structure

---

### 5. GitHub

Correct way:

> All source code and experiment configurations are available at:
> **GitHub repository: [link]**

👉 In the appendix:

* repository structure
* description

---
