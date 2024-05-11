# Словари для языковых ботов

Каждая строка в словаре состоит из 5 колонок, разделённых **||**.
`Уникальный числовой идентификатор (целое положительное число) || Уровень сложности || Фраза на русском | Синоним фразы на русском || Фраза на иностранном языке | Синоним фразы на иностранном языке || Полезный комментарий. Может быть пустым.`

Идентификатор вводится вручную, чтобы сохранить возможность редактировать фразу без потери статистики по ней. Например, если там небольшая опечатка или нужно добавить синоним. Чтобы сбросить статистику по фразе, нужно сохранить её с новым уникальным идентификатором. После обновления словаря в боте свободные идентификаторы можно использовать снова.

В текущей версии бота используется только перевод с русского на иностранный язык и для русской фразы используется только первый синоним, если не включена опция использовать случайные фразы. Это сделано для простоты.

Фразы более высокого уровня сложности будут предложены пользователю после правильного ответа на все фразы предыдущего уровня сложности. Уровень пользователя только повышается и не может быть понижен. На каждом уровне пользователю доступны все фразы текущего уровня и всех предыдущих.

Комментарий будет показан после ответа на задание вне зависимости от того, был ли ответ правильным.