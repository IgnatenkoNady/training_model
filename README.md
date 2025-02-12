Проект: Линейные модели в машинном обучении
Описание проекта
Интернет-магазин «В один клик» продаёт разные товары: для детей, для дома, мелкую бытовую технику, косметику и даже продукты. Отчёт магазина за прошлый период показал, что активность покупателей начала снижаться. Привлекать новых клиентов уже не так эффективно: о магазине и так знает большая часть целевой аудитории. Возможный выход — удерживать активность постоянных клиентов. Сделать это можно с помощью персонализированных предложений. Необходимо разработать решение, которое позволит персонализировать предложения постоянным клиентам, чтобы увеличить их покупательскую активность.

Цель проекта:
Построить модель, которая предскажет вероятность снижения покупательской активности клиента в следующие три месяца. В исследование нужно включить дополнительные данные финансового департамента о прибыльности клиента: какой доход каждый покупатель приносил компании за последние три месяца. Используя данные модели и данные о прибыльности клиентов, нужно выделить сегменты покупателей и разработать для них персонализированные предложения.

Использованные модели и результат:
В проекте были использованы следующие модели: KNeighborsClassifier(), DecisionTreeClassifier(), LogisticRegression() и SVC(). Наилучшей моделью оказалась LogisticRegression(). На основе результатов этой модели была предсказана вероятность снижения активности в последующие три месяца. Также на основе полученных данных предложены некоторые рекоммендации по поддержанию активности клиентов.
