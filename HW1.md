ДЗ 1

1.Приведите примеры:

- пример интеграционного теста приложения электронной почты 
Открытие вложений: пользователь открывает письмо с вложением (например, с документом или изображением) и пытается его открыть. Тест проверяет, что вложение открывается без ошибок.
- пример дымового теста приложения электронной почты 
Создание подписи к письмам и ее добавление в каждое сообщение.
- пример ре-теста приложения электронной почты 
Повторно протестировать (в процессе тестирования были выявлены и устранены все проблемы, которые мешали корректной работе приложения. Теперь приложение готово к использованию и не содержит никаких ошибок или недочетов.)
- пример нефункционального теста приложения электронной почты 
Проверка работы кнопки "отправить" или тестирование работы функции "пометить как прочитанное/непрочитанное"
2. Необходимо ли провести регрессионное тестирование приложения электронной почты в случае если (ответить отдельно для каждого случая, мотивируя свой ответ):

- добавлен раздел Спам

Добавление раздела “Спам” может повлиять на работу других функций приложения, таких как удаление или архивирование писем.

- раздел “Удаленные” переименован в раздел “Корзина” 
Переименование раздела “Удаленные” в “Корзина” может привести к изменению логики работы с письмами, находящимися в этом разделе (не возможность восстановления или очистки)
- на «Странице входа» устранен ранее обнаруженный дефект
 Устранение дефекта на “Странице входа” может отразиться на работе других страниц и функций приложения. 
Итог: Регрессионное тестирование необходимо провести в каждом из перечисленных случаев
3. Какой вид тестирования желательно провести в первую очередь на новом билде(релизе) приложения?
Функциональное тестирование, убедиться что новый билд не нарушает работу основных процессов и позволяет выполнять основные задачи
4. В результате добавления раздела “Черновик” перестала корректно работать кнопка “Удалить письмо”. Какой вид тестирования позволит обнаружить нам данный дефект?
Функциональное тестирование” , позволит совершить проверку корректности работы всех основных функций и возможностей приложения 
