# Поиск дня в месяце
## Условия задачи
В организации часто планируют мероприятие на конкретные дни недели, относительно начала месяца. Например, на второй вторник или на первую среду.

Необходимо составить алгоритм, который по дню недели и порядковому номеру вычислит тот день, когда должно проходить мероприятие в этом месяце.

Алгоритм необходимо разместить в функции ЧислоМесяцаПоНомеру().

### Входные данные
НачалоМесяца - Дата - Дата начала месяца;

НомерДняНедели - Число - Порядковый номер дня недели. Отсчет начинается с понедельника (Понедельник - 1, Вторник - 2 и т.д.);

НомерВхождения - Число - В какой по порядку указанный день недели должно пройти мероприятие (Первый, Второй и т.д.)
### Результат
В результате работы метод должен вернуть Дату - день, в который должно пройти мероприятие в этом месяце.
### Примеры
Первый понедельник в декабре 2021 года - 6 декабря 2021 года.

Второе воскресенье в феврале 2022 года - 13 февраля 2022 года.

## Рекомандации к решению
Сначала проверьте НомерВхождения. Фактически он означает, какое количество недель месяца можно пропустить.

После этого в цикле переберите следующие 7 дней месяца и найдите нужный день недели. Для определения дня недели от указанной даты, воспользуйтесь функцией ДеньНедели() 
