# ACID

ACID (Atomicity, Consistency, Isolation, Durability) — описание требований к СУБД, 
системе управления базами данных: атомарность, согласованность, изолированность и прочность.

Следование требованиям ACID обеспечивает надежную и предсказуемую работу транзакционных систем.

1) Атомарность — все изменения данных выполняются как единая операция, от начала и до конца.
2) Согласованность — после нормального завершения работы (EOT, End of transaction) транзакция фиксирует допустимые результаты.
3) Изолированность — параллельные транзакции не должны влиять друг на друга во время выполнения.
4) Прочность — пользователь может быть уверен, что после оповещение об успешной транзакции ничто не отменит результат.

-Транзакции получают доступ к данным через операции чтения и записи.

-Для обеспечения согласованности данных до и после транзакции соблюдаются свойства ACID.
