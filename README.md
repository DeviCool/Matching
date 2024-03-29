# Matching
<b>Цель проекта:</b> 
Разработать алгоритм, который предложит несколько вариантов наиболее похожих товаров и оценить качество алгоритма по метрике accuracy@5.

<b>Оценка качества модели</b>

-  метод calculate_accuracy для расчета метрики accuracy@5.
- Рассчитана метрика accuracy@5 для валидационных данных.
- Реализована модель FAISS с использованием различных метрик сходства (L2 distance и Inner product).
- Рассчитана метрика accuracy@5 для различных метрик сходства.
- Проведено тестирование модели с разным количеством кластеров.
- Рассчитаны метрики silhouette score, davies bouldin score и calinski harabasz score для разного количества кластеров.
- Проведено сравнение моделей FAISS, KNN и KMEANS.
- Рассчитана метрика accuracy@5 для моделей KNN и KMEANS.
- Сформирован итоговый отчет с результатами и метриками для каждой модели.

<b>Выводы</b>

- Модель FAISS показала хорошие результаты по метрике accuracy@5 для различных метрик сходства.
- Модель KNN также показала хорошие результаты по метрике accuracy@5.
- Модель KMEANS показала средние результаты по метрике accuracy@5, но имеет низкие значения silhouette score, davies bouldin score и calinski harabasz score.
- Модель FAISS с использованием L2 distance и Inner product является наиболее эффективной для данной задачи сравнения товаров
