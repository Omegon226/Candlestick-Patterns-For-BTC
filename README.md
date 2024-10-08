# Candlestick-Pattern-For-BTC

В данном репозитории расписано создание стратегии, предварительное исследование актива (BTC/USDT) на котором эта стратегия будет работать и оптимизации параметров стратегии для увеличении её эффективности. 

В Jupyter Notebook ```research.ipynb``` расписаны этапы: 
- Получение данных и их обработка для стратегии;
- Анализ инструмента на котором будет работать стратегия и сигнала, с помощью которого работает стратегия;
- Реализована простейшая версия стратегии и проанализирована её результативность;

В Jupyter Notebook ```strategy_optimization.ipynb``` расписаны этапы: 
- Перенос наработок из ```research.ipynb``` в формат функций и создание стратегии для её подробного тестирования и оптимизации;
- Оптимизация параметров стретегии на исторических данных до 01.03.2024;
- Тестирование стратегии на подобранных параметрах на данных с 01.03.2024 по 10.09.2024;

Чтобы запустить проект воспользуйтесь коммандой ```docker-compose up -d``` . Если вы работаете на Windows, то запустите файл ```start.bat```.

В проекте используются: Python (Jupyter Lab), InfluxDB.

После запуска проекта переходите по адресу: ```http://localhost:8888/``` или ```http://localhost:8888/lab/tree/market_data.ipynb``` чтобы начать работу с Jupyter Notebook, который представлен в работе.
