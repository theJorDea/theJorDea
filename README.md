# Кирилл Левин

ML / Quant-разработчик. Студент ИТМО. Занимаюсь машинным обучением, финансовым риск-менеджментом и full-stack разработкой.

**Сейчас:** финансовый ML — рыночный риск (VaR/ES, GARCH), кредитный скоринг, алгоритмическая торговля.

## Проекты

### [Riskforge](https://github.com/theJorDea/Riskforge) — рыночный риск
Библиотека для оценки рыночного риска портфеля: VaR и Expected Shortfall (исторический, параметрический, Monte Carlo на нормальном и Student-t распределениях), волатильность EWMA (RiskMetrics) и GARCH(1,1) с оценкой через MLE, бэктестинг по Kupiec и Christoffersen, LSTM-прогноз волатильности в сравнении с GARCH. Исследовательские ноутбуки на данных SPY/QQQ/TLT/GLD за 2015–2025.

`Python` `NumPy` `pandas` `SciPy` `PyTorch` `pytest` `GitHub Actions`

### [Credit-Scoring](https://github.com/theJorDea/Credit-Scoring) — кредитный скоринг
PD-модель на датасете UCI Default of Credit Card Clients: логистическая регрессия и LightGBM с изотонической калибровкой вероятностей, WoE/IV-анализ признаков, скоркарта в формате PDO, интерпретация через SHAP. AUC 0.779, KS 0.42.

`Python` `scikit-learn` `LightGBM` `SHAP`

### QuantForge — ИИ-агент для торговли на MOEX
Автономный торговый агент для чемпионата ArenaGo: рыночные данные MOEX ISS, feature store с техническими индикаторами, классификатор рыночного режима, alpha-engine (правила + LightGBM/CatBoost), backtest с walk-forward валидацией, risk engine (kill-switch, лимиты экспозиции, drawdown), исполнение заявок через ArenaGo API и объяснение решений через LLM. *(приватный репозиторий)*

`Python` `FastAPI` `Next.js` `PostgreSQL/TimescaleDB` `Redis` `Docker` `LightGBM` `CatBoost`

### [JorDea-Website](https://github.com/theJorDea/JorDea-Website) — личный сайт
Персональный сайт-портфолио: монохромный дизайн, плавный скролл и анимации. Деплой на Vercel.

`TypeScript` `Next.js` `Motion` `Lenis` `Tailwind CSS`

## Стек

- **Языки:** Python, TypeScript, SQL
- **ML/DS:** PyTorch, scikit-learn, LightGBM, pandas, NumPy
- **Backend:** FastAPI, PostgreSQL, Redis, Docker
- **Финансы:** VaR/ES, EWMA/GARCH, бэктестинг, кредитный скоринг, алготрейдинг

## Контакты

- GitHub: [@theJorDea](https://github.com/theJorDea)
- Email: klevin3701@gmail.com
