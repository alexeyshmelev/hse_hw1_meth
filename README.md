# Домашнее задание №1 (метилирование)

Задание было сделано на локальном компьютере, соответствующий .ipynb файл загружен в репозиторий.

## №1

Главная особенность, которую можно выделить из отчётов FastQC - это высокое содержание C и G нуклеотидов. Так как у млекопитающих метилирование происходит в основном в CpG-динуклеотидах, то это косвенно может свидетельствовать о возможном наличии большого процента метилирования.

## №2
### a)
Количество ридов, которое пришлось на целевые регионы:

| | 11347700-11367700 | 40185800-40195800 |
| :-----------: | :-----------: | :-----------: |
| SRR5836473 | 1090 | 464 |
| SRR5836475 | 1456 | 630 |
| SRR3824222 | 2328 | 1062 |

### b)
Статистика по дедупликации (из отчёта Bismark). Скрипт для параллельного выполнения написал в Jupyter Notebook.

| | Процент дедуплицированных прочтений |
| :-----------: | :-----------: |
| SRR5836473 | 18.3% |
| SRR5836475 | 9.08% |
| SRR3824222 | 2.92% |
