# Hi, I'm Umut Boran Kaygün 👋

4th-year computer engineering student from Türkiye, focused on **machine learning** and **computer vision**, and on bringing AI models onto real hardware.

- 🎓 Graduation project: **Dermatrix**, a skin disease pre-assessment system comparing 5 deep learning models
- 🏆 TEKNOFEST 2025 finalist, **13th in Türkiye** with an AI-assisted skin condition pre-detection app
- 💼 Computer vision intern at Ayvos (2026): people counting, pose estimation and retail video analytics
- 🔭 Building AI systems that run outside the notebook: on mobile devices and embedded boards like Raspberry Pi
- 🌱 Currently improving my skills in deep learning, model optimization and clean software engineering

---

### 🧠 Computer Vision & Deep Learning

| Project | Description | Stack |
|---|---|---|
| [**Dermatrix**](https://github.com/UBKc/dermatrix) | Graduation project: compared 5 deep learning models on 20,213 skin images (EfficientNetB0 best at 97.87%), validated with Friedman/Nemenyi tests, explained with Grad-CAM, and fused with a 12-question symptom survey. | TensorFlow · PyTorch · Flask |
| [**Ayvos Internship – Retail Video Analytics**](https://github.com/UBKc/ayvos-staj-goruntu-isleme) | Computer vision internship code: people counting with tracking, pose-based standing / sitting / walking detection with duration logging, shop-window dwell time, checkout queue counting and table cleanliness monitoring. Faces are blurred for privacy. | Python · YOLOv8 · OpenCV |
| [**BioPredict – DeriTanı**](https://github.com/UBKc/biopredict-deritani) | Detection of 4 skin conditions from images (TEKNOFEST 2025 finalist). I was responsible for the AI side: dataset preparation, labeling, training and validation. | Python · YOLO |
| [**License Plate Recognition & Parking System**](https://github.com/UBKc/plaka-okuma-otopark) | Detects and reads Turkish license plates, matches each car's entry and exit, and calculates parking time and fee. Compared 3 OCR engines; fast-plate-ocr read 100% of 50 real plates. | Python · YOLO · OpenCV · OCR |
| [**Brain Tumor Detection on MRI**](https://github.com/UBKc/beyin-tumoru-tespiti) | YOLO11n trained on my own GPU with a patient-grouped split. On a held-out test set: mAP50 0.976, mAP50-95 0.708, 116 of 123 tumors found. A static INT8 ONNX version keeps accuracy at 3 MB and runs 2x faster on CPU. | YOLO11 · PyTorch · ONNX Runtime |

### ♻️ Smart Recycling Bin

| Project | Description | Stack |
|---|---|---|
| [**Smart Recycling Bin**](https://github.com/UBKc/akilli-atik-ayristirma) | Raspberry Pi system that classifies waste from a camera image and sorts it into 5 bins with two servo motors. Team project, I am the team captain. | Python · Raspberry Pi · Gemini API |
| [**Waste Classification Model**](https://github.com/UBKc/atik-siniflandirma-modeli) | Offline model for the bin: YOLOv8n-cls fine-tuned on TrashNet, 89.97% test accuracy (91.56% on the bin's 5 compartments). A statically quantized INT8 ONNX version is 1.6 MB and 1.5x faster, at 86.81%. | YOLOv8 · ONNX Runtime · scikit-learn |
| [**Zero-Shot Waste Classification with CLIP**](https://github.com/UBKc/clip-atik-siniflandirma) | How far can you get without training? CLIP zero-shot reaches 71.77%, a linear probe on CLIP features 88.92%, close to the fine-tuned YOLO. Turkish prompts collapse to 24%. | PyTorch · CLIP · scikit-learn |

### 📈 Optimization & Reinforcement Learning

| Project | Description | Stack |
|---|---|---|
| [**Genetic Algorithm for TSP**](https://github.com/UBKc/genetik-algoritma-tsp) | GA benchmarked on 4 TSPLIB instances against nearest neighbour and 2-opt; a memetic GA (GA + 2-opt) finds the known optimum of berlin52 and kroA100 in 10/10 runs. | Python · NumPy |
| [**Taxi-v3 Q-Learning**](https://github.com/UBKc/taxi-v3-q-learning) | A tabular Q-Learning agent for Gymnasium Taxi-v3; solves 100% of 1000 unseen test episodes in 13 steps on average. | Python · Gymnasium |

### 💻 Software Engineering

| Project | Description | Stack |
|---|---|---|
| [**TaskFlow**](https://github.com/UBKc/taskflow) | Full-stack Kanban app with JWT auth, role-based access and drag & drop; security-tested with OWASP ZAP. | React · Node.js · PostgreSQL |
| [**Randevu**](https://github.com/UBKc/randevu) | Appointment booking system: available-slot calculation, double-booking prevented by a PostgreSQL exclusion constraint, tested under concurrent requests. | TypeScript · Prisma · PostgreSQL |

---

### 🛠️ Tech Stack

| | |
|---|---|
| **AI / ML** | Python · TensorFlow · Keras · PyTorch · scikit-learn · YOLO · OpenCV · CLIP · Hugging Face Transformers |
| **Deployment** | ONNX Runtime · INT8 quantization · Flask · Raspberry Pi |
| **Languages** | Python · Java · C# · C · SQL · MATLAB · JavaScript / TypeScript |
| **Tools** | Git · Google Colab · VS Code · PyCharm · Android Studio · Microsoft SQL Server |

---

### 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/umut-boran-kayg%C3%BCn-85a009164/)
