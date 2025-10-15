# Screen-Mate-A-Context-Aware-Intelligent-Screen-Assistant
Screen-Mate is an AI-powered desktop assistant that observes your screen, understands context, and provides real-time, proactive help using OCR, YOLO, and LLMs — offering smart suggestions and debugging support through a minimal floating overlay.

Screen-Mate: A Context-Aware Intelligent Screen Assistant**

Screen-Mate is an AI-powered digital companion that intelligently observes your desktop screen, understands your activity, and proactively provides real-time assistance — without interrupting your workflow.

Unlike traditional assistants that rely on manual commands, Screen-Mate uses OCR, YOLO-based object detection, and LLMs to analyze both textual and visual on-screen data. It then offers context-aware suggestions, task guidance, and debugging help through a minimal floating overlay interface.

---

Key Features

*  Context-Aware AI** — Understands user activity across applications in real time.
*  Multimodal Analysis** — Combines visual (UI detection via YOLO) and textual (OCR) inputs.
*  LLM Integration** — Uses large language models (Gemini) to generate intelligent responses.
*  Floating Overlay** — Provides unobtrusive, on-screen suggestions and quick actions.
*  Adaptive Prompting** — Auto-generates or refines prompts based on screen content and user behavior.
*  Privacy-Focused Design** — Processes screen content locally for user data security.

---

# System Architecture

The project follows a four-layer modular architecture:

1. **Input Layer:** Captures screenshots, extracts text (OCR), and detects UI elements.
2. **AI & Processing Layer:** Performs semantic analysis, intent recognition, and context fusion.
3. **Application Layer:** Generates recommendations based on task inference.
4. **Presentation Layer:** Displays suggestions through an interactive overlay.

---

# Tech Stack

* **Programming Language:** Python
* **Libraries:** OpenCV, PyWin32, mss, scikit-learn, PyTorch, TensorFlow, EasyOCR, Tesseract
* **LLM Models:** Gemini 2.5 Pro
* **UI Framework:** PyQt (for floating overlay)
* **Datasets:** Roboflow UI Dataset, HuggingFace UI Components, Custom Desktop Screens

---

# Evaluation Highlights

* **UI Detection Accuracy (YOLOv8):** 66.9% mAP
* **Average Response Latency:** ~1.3 seconds
* **User Studies:** Increased productivity and reduced task-switching fatigue

---

# Future Enhancements

* Cross-platform and mobile versions
* Reinforcement learning-based personalization
* Privacy-preserving local pipelines
* Multilingual OCR and accessibility features

---

# Authors

* Pranav Zaware
* Snehal Yelwande
* Tushar Patil
* Pranjal Pandit
* Anuradha Yenkikar
* Nilesh Sable

---

# Citation

If you use this work, please cite:
**Screen-Mate: A Context-Aware Intelligent Screen Assistant** — Department of Computer Science and Engineering (AI), Vishwakarma Institute of Information Technology, Pune, India (2025).
