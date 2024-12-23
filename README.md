# Инжиниринг управления данными

## Анализ частоты и интенсивности погодных явлений, ведущих к экономическим потерям в различных регионах РФ

### Описание проекта
Данный проект направлен на анализ данных о погодных явлениях в России с целью выявления их влияния на экономические потери в различных федеральных округах. В проекте используются данные о погоде, которые позволяют оценить частоту и интенсивность различных явлений, а также выявить регионы и временные периоды, подверженные наибольшим рискам экономических убытков.

### Структура проекта
```
DME_2024_ITMO/
├── images/                     # Папка с графиками
├── └── ...
├── dataset_input.xlsx          # Исходный файл с данными о погодных явлениях
├── dataset_output.csv          # Выходной файл с обработанными данными
├── dme_backup.sql              # База данных PostgreSQL
└── dme_project.ipynb           # Jupyter Notebook с кодом обработки и анализа данных
```

### Основные этапы работы
1. **Загрузка данных**: Данные загружаются из файла `dataset_input.xlsx`.
2. **Обработка данных**: 
   - Фильтрация и группировка данных по федеральным округам и годам.
   - Вычисление средней интенсивности и продолжительности погодных явлений.
3. **Визуализация данных**: 
   - Построение графиков распределения погодных явлений по федеральным округам.
   - Анализ пар явлений, наблюдаемых одновременно.
4. **Экспорт данных**: Обработанные данные сохраняются в файл `dataset_output.csv`.

### Планы до конца семестра
- **Интеграция с базой данных PostgreSQL**: Данные будут загружены в базу данных для дальнейшего хранения и обработки.
- **Подключение BI-системы**: Планируется подключение инструментов бизнес-аналитики (BI) для создания дэшбордов, которые будут отображать графики и визуализации на основе проанализированных данных.
