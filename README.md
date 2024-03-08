Логика кода:

Создание класса PhoneBook, который хранит телефонную книгу в виде Map, где ключом является имя абонента, а значением список его телефонных номеров.
В конструкторе PhoneBook инициализируется пустая телефонная книга в виде HashMap.
Метод add(name, phoneNum) добавляет телефонный номер phoneNum для абонента с именем name. Если абонент с таким именем уже существует, то номер добавляется в его список номеров, иначе создается новая запись в книге.
Метод find(name) возвращает список телефонных номеров для абонента с именем name, либо пустой список, если такого абонента нет.
Метод getPhoneBook() возвращает отсортированную по количеству номеров телефонную книгу в виде Map, где ключами являются имена абонентов, а значениями списки их номеров. Используется Stream API для сортировки и преобразования.
В методе main создается экземпляр PhoneBook, добавляются телефонные номера для абонентов "Alice" и "Bob", а также повторно добавляется номер для "Alice".
Выводятся номера телефона для абонента "Alice" с помощью метода find().
Выводятся все записи в телефонной книге с помощью метода getPhoneBook(), итерируя по каждой записи и выводя имя абонента и список его номеров.
