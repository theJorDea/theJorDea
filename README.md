<div align="center">

# Kirill Levin

### Machine Learning · Deep Learning · Quantitative Research

ITMO University student building machine learning systems, deep learning models, AI agents, and quantitative research tools.

[GitHub](https://github.com/theJorDea) · [Portfolio](https://jordea.vercel.app) · [Email](mailto:klevin3701@gmail.com)

</div>

## About me

I am interested in building and training machine learning models rather than only integrating existing AI APIs.

My current interests include:

* transformer-based models and representation learning;
* embeddings, semantic search, and retrieval systems;
* multi-agent AI systems and long-term memory;
* computer vision, object detection, and classification;
* financial risk modelling, credit scoring, and algorithmic trading.

I enjoy reading research papers, reproducing ideas in PyTorch, running controlled experiments, and turning research prototypes into usable software.

## Selected projects

### [Jevio Fuse](https://github.com/theJorDea/JevioFuseHack) — local multi-agent coding system

Open-source coding agent that explores software repositories, delegates work between specialised agents, reviews generated changes, and preserves relevant project context between sessions.

The system includes Architect, Coder, Reviewer, Judge, and Orchestrator roles, semantic memory with vector retrieval and a knowledge graph, MCP integrations, permission-controlled tools, and OpenTelemetry tracing.

The project currently includes 152 automated tests and a dedicated memory benchmark.

`TypeScript` `Node.js` `AI Agents` `LLM` `Vector Search` `Knowledge Graph` `MCP` `OpenTelemetry`

### [Riskforge](https://github.com/theJorDea/Riskforge) — market risk research library

Library for portfolio market-risk estimation and volatility modelling.

Implemented historical, parametric, and Monte Carlo Value at Risk and Expected Shortfall using normal and Student-t distributions, EWMA volatility, GARCH(1,1) estimation with maximum likelihood, and Kupiec and Christoffersen backtesting.

The project also contains research notebooks comparing LSTM-based volatility forecasting with GARCH on SPY, QQQ, TLT, and GLD market data from 2015–2025.

`Python` `NumPy` `pandas` `SciPy` `PyTorch` `pytest` `GitHub Actions`

### [Credit Scoring](https://github.com/theJorDea/Credit-Scoring) — probability of default modelling

Credit-risk modelling pipeline based on the UCI Default of Credit Card Clients dataset.

Implemented logistic regression and LightGBM models, isotonic probability calibration, Weight of Evidence and Information Value analysis, PDO-based scorecard construction, and SHAP model interpretation.

Model performance: ROC AUC 0.779 and KS statistic 0.42.

`Python` `scikit-learn` `LightGBM` `SHAP` `pandas`

### QuantForge — autonomous trading agent for MOEX

Developed an autonomous trading system for the ArenaGo competition.

The system included MOEX ISS market-data ingestion, a feature store with technical indicators, market-regime classification, an alpha engine based on rules and gradient boosting, walk-forward backtesting, portfolio-risk controls, order execution through the ArenaGo API, and LLM-generated explanations of trading decisions.

Private repository.

`Python` `FastAPI` `LightGBM` `CatBoost` `PostgreSQL` `TimescaleDB` `Redis` `Docker` `Next.js`

### [JorDea Website](https://github.com/theJorDea/JorDea-Website) — [portfolio website](https://jordea.vercel.app)

Personal portfolio website with a monochrome interface, smooth scrolling, page transitions, and interactive animations. Deployed on Vercel.

`TypeScript` `Next.js` `Tailwind CSS` `Motion` `Lenis` `Vercel`

## Applied computer vision experience

Worked on fruit and vegetable defect and freshness detection for VkusVill.

Improved object detection and classification models through dataset analysis, annotation review, class-imbalance handling, model tuning, and detailed evaluation of per-class precision and recall.

The work included experiments with YOLO-based detection models, freshness classification, error analysis, and development of approaches for improving weak and underrepresented classes.

## Technical skills

* **Languages:** Python, TypeScript, SQL
* **Deep learning:** PyTorch, Transformers, representation learning, contrastive learning
* **Machine learning:** scikit-learn, LightGBM, CatBoost, feature engineering, model evaluation
* **Computer vision:** object detection, image classification, YOLO, dataset analysis
* **AI systems:** LLM agents, semantic memory, embeddings, vector retrieval, RAG, MCP
* **Backend and infrastructure:** FastAPI, Node.js, PostgreSQL, Redis, Docker, GitHub Actions
* **Quantitative finance:** VaR, Expected Shortfall, EWMA, GARCH, credit scoring, backtesting

## Collaboration

I am interested in collaborating on focused research and engineering projects involving:

* deep learning and transformer architectures;
* representation learning and multimodal models;
* AI agents, RAG, and long-term memory;
* computer vision;
* ML evaluation and reproducible experimentation;
* quantitative machine learning.

Contact me if you are working on a technically challenging project and need help with model development, experimentation, evaluation, or ML engineering.

---

<div align="center">

# Кирилл Левин

### Machine Learning · Deep Learning · Quantitative Research

Студент ИТМО. Разрабатываю ML-системы, обучаю deep learning модели, создаю AI-агентов и инструменты для количественных исследований.

[GitHub](https://github.com/theJorDea) · [Портфолио](https://jordea.vercel.app) · [Email](mailto:klevin3701@gmail.com)

</div>

## Обо мне

Мне интересно самостоятельно разрабатывать и обучать модели машинного обучения, а не только подключать готовые AI API.

Основные направления моих интересов:

* трансформеры и representation learning;
* эмбеддинги, семантический поиск и retrieval-системы;
* мультиагентные AI-системы и долговременная память;
* computer vision, детекция объектов и классификация;
* моделирование финансовых рисков, кредитный скоринг и алгоритмическая торговля.

Я читаю научные статьи, воспроизвожу исследовательские идеи в PyTorch, провожу контролируемые эксперименты и превращаю исследовательские прототипы в работающие программные системы.

## Основные проекты

### [Jevio Fuse](https://github.com/theJorDea/JevioFuseHack) — локальная мультиагентная система для программирования

Open-source coding-агент, который исследует программные репозитории, распределяет задачи между специализированными агентами, проверяет внесённые изменения и переносит релевантный контекст между рабочими сессиями.

Система включает роли Architect, Coder, Reviewer, Judge и Orchestrator, семантическую память с векторным поиском и графом знаний, MCP-интеграции, контролируемый доступ к инструментам и трассировку через OpenTelemetry.

Проект содержит 152 автоматических теста и отдельный benchmark для проверки работы памяти.

`TypeScript` `Node.js` `AI Agents` `LLM` `Vector Search` `Knowledge Graph` `MCP` `OpenTelemetry`

### [Riskforge](https://github.com/theJorDea/Riskforge) — библиотека для исследования рыночного риска

Библиотека для оценки рыночного риска портфеля и моделирования волатильности.

Реализованы исторический, параметрический и Monte Carlo Value at Risk и Expected Shortfall с нормальным распределением и распределением Стьюдента, волатильность EWMA, модель GARCH(1,1) с оценкой параметров методом максимального правдоподобия, а также бэктесты Купица и Кристофферсена.

Проект также содержит исследовательские ноутбуки со сравнением прогнозирования волатильности через LSTM и GARCH на данных SPY, QQQ, TLT и GLD за 2015–2025 годы.

`Python` `NumPy` `pandas` `SciPy` `PyTorch` `pytest` `GitHub Actions`

### [Credit Scoring](https://github.com/theJorDea/Credit-Scoring) — моделирование вероятности дефолта

Пайплайн кредитного скоринга на основе датасета UCI Default of Credit Card Clients.

Реализованы логистическая регрессия и LightGBM, изотоническая калибровка вероятностей, анализ Weight of Evidence и Information Value, построение скоркарты в формате PDO и интерпретация модели через SHAP.

Качество модели: ROC AUC 0.779 и KS 0.42.

`Python` `scikit-learn` `LightGBM` `SHAP` `pandas`

### QuantForge — автономный торговый агент для MOEX

Разработал автономную торговую систему для соревнования ArenaGo.

Система включала загрузку рыночных данных через MOEX ISS, feature store с техническими индикаторами, классификацию рыночного режима, alpha-engine на основе правил и градиентного бустинга, walk-forward бэктестинг, управление портфельными рисками, исполнение заявок через ArenaGo API и объяснение торговых решений через LLM.

Приватный репозиторий.

`Python` `FastAPI` `LightGBM` `CatBoost` `PostgreSQL` `TimescaleDB` `Redis` `Docker` `Next.js`

### [JorDea Website](https://github.com/theJorDea/JorDea-Website) — [сайт-портфолио](https://jordea.vercel.app)

Персональный сайт-портфолио с монохромным интерфейсом, плавным скроллом, переходами между страницами и интерактивными анимациями. Развёрнут на Vercel.

`TypeScript` `Next.js` `Tailwind CSS` `Motion` `Lenis` `Vercel`

## Опыт в computer vision

Работал над системой детекции дефектов и определения свежести фруктов и овощей для ВкусВилла.

Улучшал модели детекции и классификации через анализ датасета, проверку разметки, работу с дисбалансом классов, настройку моделей и детальный анализ precision и recall по отдельным категориям.

Работа включала эксперименты с YOLO-моделями, классификацию свежести продуктов, анализ ошибок и разработку подходов для улучшения качества на слабых и малочисленных классах.

## Технический стек

* **Языки:** Python, TypeScript, SQL
* **Deep learning:** PyTorch, Transformers, representation learning, contrastive learning
* **Machine learning:** scikit-learn, LightGBM, CatBoost, feature engineering, оценка моделей
* **Computer vision:** детекция объектов, классификация изображений, YOLO, анализ датасетов
* **AI-системы:** LLM-агенты, семантическая память, эмбеддинги, vector retrieval, RAG, MCP
* **Backend и инфраструктура:** FastAPI, Node.js, PostgreSQL, Redis, Docker, GitHub Actions
* **Количественные финансы:** VaR, Expected Shortfall, EWMA, GARCH, кредитный скоринг, бэктестинг

## Коллаборации

Мне интересны совместные исследовательские и инженерные проекты в следующих областях:

* deep learning и архитектуры трансформеров;
* representation learning и мультимодальные модели;
* AI-агенты, RAG и долговременная память;
* computer vision;
* оценка ML-моделей и воспроизводимые эксперименты;
* количественное машинное обучение.

Можно написать мне, если вы работаете над технически сложным проектом и вам нужна помощь с разработкой моделей, проведением экспериментов, оценкой качества или ML-инженерией.
