# Лекция

## Про PostgreSQL
1. Структура сообщения в Postgres
   
   ![image](https://github.com/Flict-dev/Handbook/assets/76905733/db7a3fe3-765b-4757-9f65-9581ecf8c4bf)
2. Фазы клиент-серверного протокола в Postgres
 
   ![image](https://github.com/Flict-dev/Handbook/assets/76905733/620b44c8-c952-4427-af9e-fdbfd3a8a3e4)
3. Есть 2 протокола для выполнения запросов
   <details open>
   <summary>Протокол простых запросов (Simple Query)</summary>
      
      #### Особенности протокола
      ![image](https://github.com/Flict-dev/Handbook/assets/76905733/423bcdf1-a119-4856-ae43-885bbb74f06b)
      #### Устройство протокола
      ![image](https://github.com/Flict-dev/Handbook/assets/76905733/1a97de76-3852-4476-9bc5-67e923740d79)
      - RowDescription - Описание строк, которые последуют в ответе
      - DataRow - Сами данные
      - CommandComplete - Означает, что завршена обработка одного запроса (SELECT 1;SELECT 2;SELECT 3;)
      - ReadyForQuery -  Означает, что завршена обработка всей sql строки
      
      
   </details>
   <details open>
   <summary>Протокол расширенных запросов (Extended Query)</summary>
   this one starts expanded because of the "open"
   </details>
6. 
---

## Про коды ответов сервера
---
