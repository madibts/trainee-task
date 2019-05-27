# Тестовое задание для потенциальных стажеров

### Требования к заданию и рекомендации по выполнению

При разработки UI нет ограничений на выбор библиотек или фреймворков. Но будет плюсом, если воспользуетесь на выбор: библиотекой [React](https://reactjs.org/), фреймворками [Vuejs](https://vuejs.org/) или [Angular](https://angular.io/).

Для разработки можете создать проект в онлайн редакторе [Stackblitz](https://stackblitz.com/) и присоединить репозиторий с [Github](https://github.com/).

**Запрещается** использовать библиотеки для построения интерактивных таблиц.

### Условие задачи 

#### Шаг №1

Необходимо реализовать отображение таблицы, данные для которой подгружаются и выводятся из файла [data.json](https://github.com/madibts/trainee-task/blob/master/data.json) как показано в примере №1.

***Пример №1***

| Rank| Employer | Employees count | Median salary | 
| ------ | ------ | ------ | ------ |
| 1 | Walmart | 2,300,000 | $19,177 |
| 2 | Amazon | 566,000 | $38,466 |
| 3 | Yum China | 450,000 | $9,111 |
| 4 | Kroger | 449,000 | $21,075 |
| 5 | Home Depot | 413,000 | $20,095 |
| ... | ... | ... | ... |

#### Шаг №2

Необходимо реализовать пагинацию, так чтобы в таблице выводилось по 5 записей как показано в примере №2.

***Пример №2***

| Rank| Employer | Employees count | Median salary | 
| ------ | ------ | ------ | ------ |
| 1 | Walmart | 2,300,000 | $19,177 |
| 2 | Amazon | 566,000 | $38,466 |
| 3 | Yum China | 450,000 | $9,111 |
| 4 | Kroger | 449,000 | $21,075 |
| 5 | Home Depot | 413,000 | $20,095 |

| 1 | 2 | 3 | 4 | 5 |
| - | - | - | - | - |

#### Шаг №3

Необходимо реализовать сортировку в таблице по возрастанию и убыванию как показано в примере №3. 
Сортировка должна быть реализована для всех столбцов.

***Пример №3***

| Rank ▼ | Employer | Employees count | Median salary | 
| ------ | ------ | ------ | ------ |
| 25 | Aramark | 215,000 | $13,373 |
| 24 | HCA Healthcare | 221,491 | $55,354 |
| 23 | McDonald's | 235,000 | $7,017 |
| 22 | TJX | 249,000 | $11,243 |
| 21 | J.P. Morgan Chase | 252,539 | $77,799 |

| 1 | 2 | 3 | 4 | 5 |
| - | - | - | - | - |


##### Дополнительное задание (необязательное)

Необходимо реализовать кнопки для экспорта таблицы в файловую систему в форматах csv, tsv как показано в примере №4.

| CSV | TSV |
| - | - |

| Rank| Employer | Employees count | Median salary | 
| ------ | ------ | ------ | ------ |
| 1 | Walmart | 2,300,000 | $19,177 |
| 2 | Amazon | 566,000 | $38,466 |
| 3 | Yum China | 450,000 | $9,111 |
| 4 | Kroger | 449,000 | $21,075 |
| 5 | Home Depot | 413,000 | $20,095 |

| 1 | 2 | 3 | 4 | 5 |
| - | - | - | - | - |

