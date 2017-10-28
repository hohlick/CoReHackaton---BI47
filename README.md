# Команда BI47

## Примерный функционал
1.	BI-система получает данные из папки, которая указывается в параметре “Path”
2.	В системе задействованы данные по сессиям, целям, звонкам и затратам на рекламные кампании Яндекс.Директ
3.	Система умеет выдавать отчеты со сквозной аналитикой в разрезе рекламных кампаний, ключевых слов и объявлений и указывать на проблемные элементы, а также давать краткие рекомендации по действиям с ними.
4.	Система считает атрибуцию по первому и последнему клику, а также по когортам
5.	Данные по хитам мы не стали использовать? Nfr rfr 

## Участники команды
1.	Александр Налётов (eLama)
2.	Никита Голубцов (eLama)
3.	Максим Зеленский (Excel-Inside.Pro)
4.	Алексей Марков (ФактРоста)
## Выявленные проблемы
Обнаружили несколько рекламных кампаний с признаками скликивания. У них очень большие расходы и очень маленькая доля сессий по отношению к кликам. Система позволяет быстро определять такие кампании.

Найдена цель с очень высокими показателями достижения в первые несколько дней, затем она обнулилась.

Не проблема, но почти все звонки имеют очень маленькое количество сессий в предыстории, что намекает на то, что нет необходимости использовать какие-то сложные модели атрибуции.

## Выдуманные типы анализа данных
Нет

## Выдуманные веб-аналитические метрики и измерения (свойства)
Число кликов, необходимое для получения конверсии (в разрезе кампаний)
## Пример BI-системы в облаке
https://app.powerbi.com/view?r=eyJrIjoiYmE0ZTE4YzYtNGYzNC00OTJmLThhNDEtZGY0Y2NiM2JjMWUzIiwidCI6ImIyZTVmYWU2LTNlNmQtNDYxOS1iODlhLTcxZDVhYzhkODhlYiIsImMiOjl9
## Файл PBIX для скачивания
[Ссылка](https://github.com/hohlick/CoReHackaton---BI47/releases/download/0.1/BI47-P.pbix)
