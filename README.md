# UCI_credit_scoring
Модель оценки кредитного скоринга клиентов вероятности ухода в просрочку

В качестве датасета для обучения, на основе которого будет построена модель был выбран набор данных о платежах Тайваньских клиентов за прошлые периоды
https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients

Данный проект имеет цель создать модель, помогающую принимать решения в отншении выдачи банковского продукта - кредитной карты. Задача является бинарной классификацией - можно или нельзя выдавать кредитную карту. 

Датасет содержит следующие переменные:
Переменная Категория фичи	Тип данных	Социально-демографическое описание	описание	Юниты	Пропущенные значения\
ID	ID	Integer				no\
X1	Feature	Integer		LIMIT_BAL		no\
X2	Feature	Integer	Sex	SEX		no\
X3	Feature	Integer	Education Level	EDUCATION		no\
X4	Feature	Integer	Marital Status	MARRIAGE		no\
X5	Feature	Integer	Age	AGE		no\
X6	Feature	Integer		PAY_0		no\
X7	Feature	Integer		PAY_2		no\
X8	Feature	Integer		PAY_3		no\
X9	Feature	Integer		PAY_4		no\
X10	Feature	Integer		PAY_5		no\
X11	Feature	Integer		PAY_6		no\
X12	Feature	Integer		BILL_AMT1		no\
X13	Feature	Integer		BILL_AMT2		no\
X14	Feature	Integer		BILL_AMT3		no\
X15	Feature	Integer		BILL_AMT4		no\
X16	Feature	Integer		BILL_AMT5		no\
X17	Feature	Integer		BILL_AMT6		no\
X18	Feature	Integer		PAY_AMT1		no\
X19	Feature	Integer		PAY_AMT2		no\
X20	Feature	Integer		PAY_AMT3		no\
X21	Feature	Integer		PAY_AMT4		no\
X22	Feature	Integer		PAY_AMT5		no\
X23	Feature	Integer		PAY_AMT6		no\
Y	Target	Binary		default payment next month		no
