<div align="center">

# Kirill Levin

### Machine Learning · Deep Learning · Computer Vision

**AI Engineering student at ITMO University**

[Email](mailto:klevin3701@gmail.com) · [GitHub](https://github.com/theJorDea)

</div>

## About me

I work on applied machine learning and deep learning: preparing datasets, training models, analysing errors, and turning experiments into working software. I have a particular interest in computer vision, including object detection and image classification.

My projects also include AI agents and tools for reproducible model evaluation. I care about data quality, meaningful baselines, and understanding where a model works — and where it fails.

## Applied computer vision

Worked on fruit and vegetable quality assessment for **VkusVill**, using detection and classification models to identify defects and assess freshness.

The work involved YOLO model training and tuning, annotation review, class-imbalance handling, and error analysis. I evaluated precision, recall, and F1 by class to guide experiments and improve performance on underrepresented categories.

*Project code and datasets are private.*

`Python` `PyTorch` `YOLO` `Object Detection` `Image Classification`

## Selected projects

### [OpenCanvas](https://github.com/theJorDea/OpenCanvas) — gesture-controlled 3D graphs

An interactive graph visualisation tool with camera control through hand tracking. Combines MediaPipe gesture recognition, a FastAPI backend, WebSocket updates, and a browser-based 3D renderer. Supports graph generation from text prompts and Mermaid import.

`Python` `MediaPipe` `OpenCV` `FastAPI` `WebSockets` `Three.js`

### [Jevio Fuse](https://github.com/theJorDea/JevioFuseHack) — coding agents with project memory

A local multi-agent coding system that explores repositories, plans changes, and reviews generated code. Preserves project context between sessions through semantic memory, vector retrieval, and a knowledge graph, with MCP tool integrations and execution tracing.

`TypeScript` `Node.js` `LLM Agents` `Vector Search` `MCP`

### [DPD](https://github.com/theJorDea/DPD) — efficient digital predistortion

A research project on reducing power-amplifier distortion with a compact spline model. Includes reproducible evaluation, streaming inference, and fixed-point software implementations. Current results are evaluated against a software amplifier model; physical hardware validation remains future work.

`Python` `Numerical Modelling` `Signal Processing`

### [Credit Scoring](https://github.com/theJorDea/Credit-Scoring) — classification and probability calibration

A default-probability modelling pipeline on the UCI credit-card dataset: feature engineering, logistic regression and LightGBM baselines, isotonic calibration, and SHAP interpretation. The calibrated model achieves a test ROC-AUC of **0.779**.

`Python` `scikit-learn` `LightGBM` `SHAP` `pandas`

**Also:** [Riskforge](https://github.com/theJorDea/Riskforge) — a Python library for volatility modelling and risk estimation, with statistical backtests and experiments comparing LSTM forecasts with GARCH baselines.

## Technical toolkit

| Area | Tools and methods |
| --- | --- |
| Languages | Python, TypeScript, SQL |
| ML & deep learning | PyTorch, scikit-learn, LightGBM; training, feature engineering, model evaluation |
| Computer vision | YOLO, OpenCV, MediaPipe; object detection, image classification |
| Data & experiments | NumPy, pandas, SciPy, Jupyter; error analysis, class imbalance, probability calibration |
| AI systems | LLM agents, embeddings, vector retrieval, semantic memory, MCP |
| Engineering | FastAPI, Node.js, Git, Docker, pytest, GitHub Actions |

## Get in touch

Open to collaboration on applied ML, deep learning, and computer vision projects — especially model development, experimentation, and evaluation.

[klevin3701@gmail.com](mailto:klevin3701@gmail.com)

---

<details>
<summary><strong>На русском</strong></summary>

## Кирилл Левин

**Студент ИТМО, программа AI Engineering.**

Занимаюсь прикладным машинным обучением и deep learning: готовлю данные, обучаю модели, анализирую ошибки и превращаю эксперименты в работающие приложения. Особенно интересуюсь компьютерным зрением — детекцией объектов и классификацией изображений.

Также разрабатываю AI-агентов и инструменты для воспроизводимой оценки моделей. В работе уделяю внимание качеству данных, сравнению с базовыми решениями и пониманию ограничений моделей.

### Опыт в компьютерном зрении

Работал над оценкой качества фруктов и овощей для **ВкусВилла**: детекцией дефектов и определением свежести с помощью моделей детекции и классификации.

Обучал и настраивал YOLO-модели, проверял разметку, работал с дисбалансом классов и анализировал ошибки. Оценивал precision, recall и F1 по отдельным классам, чтобы выбирать направления экспериментов и улучшать качество на малочисленных категориях.

*Код проекта и датасеты находятся в закрытом доступе.*

`Python` `PyTorch` `YOLO` `Детекция объектов` `Классификация изображений`

### Избранные проекты

#### [OpenCanvas](https://github.com/theJorDea/OpenCanvas) — 3D-графы с управлением жестами

Инструмент для интерактивной визуализации графов с управлением камерой через отслеживание рук. Объединяет MediaPipe, FastAPI, обмен событиями по WebSocket и 3D-визуализацию в браузере. Поддерживает генерацию графов по текстовому запросу и импорт Mermaid.

`Python` `MediaPipe` `OpenCV` `FastAPI` `WebSockets` `Three.js`

#### [Jevio Fuse](https://github.com/theJorDea/JevioFuseHack) — coding-агенты с памятью проекта

Локальная мультиагентная система, которая исследует репозитории, планирует изменения и проверяет сгенерированный код. Сохраняет контекст между сессиями через семантическую память, векторный поиск и граф знаний. Включает MCP-интеграции и трассировку выполнения.

`TypeScript` `Node.js` `LLM Agents` `Vector Search` `MCP`

#### [DPD](https://github.com/theJorDea/DPD) — цифровое предыскажение с низкой вычислительной сложностью

Исследовательский проект по компенсации искажений усилителя мощности с помощью компактной сплайновой модели. Реализованы воспроизводимая оценка, потоковое вычисление и программные версии с фиксированной точкой. Текущие результаты получены на программной модели усилителя; проверка на физическом оборудовании ещё предстоит.

`Python` `Численное моделирование` `Обработка сигналов`

#### [Credit Scoring](https://github.com/theJorDea/Credit-Scoring) — классификация и калибровка вероятностей

Пайплайн оценки вероятности дефолта на датасете UCI: подготовка признаков, логистическая регрессия и LightGBM, изотоническая калибровка и интерпретация через SHAP. ROC-AUC калиброванной модели на тестовой выборке — **0.779**.

`Python` `scikit-learn` `LightGBM` `SHAP` `pandas`

**Также:** [Riskforge](https://github.com/theJorDea/Riskforge) — Python-библиотека для моделирования волатильности и оценки рисков со статистическими бэктестами и сравнением прогнозов LSTM с GARCH.

### Технический стек

| Направление | Инструменты и методы |
| --- | --- |
| Языки | Python, TypeScript, SQL |
| ML и deep learning | PyTorch, scikit-learn, LightGBM; обучение, подготовка признаков, оценка моделей |
| Компьютерное зрение | YOLO, OpenCV, MediaPipe; детекция объектов, классификация изображений |
| Данные и эксперименты | NumPy, pandas, SciPy, Jupyter; анализ ошибок, дисбаланс классов, калибровка вероятностей |
| AI-системы | LLM-агенты, эмбеддинги, векторный поиск, семантическая память, MCP |
| Разработка | FastAPI, Node.js, Git, Docker, pytest, GitHub Actions |

### Связаться со мной

Открыт к совместным проектам по прикладному ML, deep learning и компьютерному зрению: разработке моделей, экспериментам и оценке качества.

[klevin3701@gmail.com](mailto:klevin3701@gmail.com)

</details>
