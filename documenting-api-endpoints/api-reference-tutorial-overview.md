# Обзор пошагового описания API ссылки

В это обзоре мы поработаем над созданием 5 общих разделов документации API ссылки:

- описание ресурса;
- конечные точки и методы;
- параметры;
- примеры запроса;
- примеры и схема ответа

Чтобы обеспечить некоторый контекст (и продолжить наш пример сценария документации), мы разберем информацию из раздела [Документирование новой конечной точки ](https://github.com/Starkovden/Documenting_APIs/blob/master/3.%20Documenting%20API%20endpoints/3.1.%20A%20new%20endpoint%20to%20document.md) по этим пяти разделам.

[5 Общих разделов в документации API](#commonSection)

[Карта рабочего процесса описания](#map)

[После описания](#afterTutorial)

[Дальнейшие шаги](#nextSteps)

<a name="commonSection"></a>
## 5 Общих разделов в документации API

Почти все API содержат описание пяти разделов:

[1. Описание ресурса](https://github.com/Starkovden/Documenting_APIs/blob/master/3.%20Documenting%20API%20endpoints/3.3.%20Step%201%20Resourse%20description.md)

В данном случае «Ресурсы» относятся к информации, возвращаемой API.

[2. Конечные точки и методы](https://github.com/Starkovden/Documenting_APIs/blob/master/3.%20Documenting%20API%20endpoints/3.4.%20Step%202%20Endpoints%20and%20methods.md)

Конечные точки указывают, как получить доступ к ресурсу, а метод указывает разрешенные взаимодействия (такие как GET, POST или DELETE) с ресурсом.

[3. Параметры](https://github.com/Starkovden/Documenting_APIs/blob/master/3.%20Documenting%20API%20endpoints/3.5.%20Step%203%20Parameters.md)

Параметрами являются данные, которые можно передать конечной точке (например, указать формат ответа или возвращаемую сумму), чтобы повлиять на ответ.

[4. Пример запроса](https://github.com/Starkovden/Documenting_APIs/blob/master/3.%20Documenting%20API%20endpoints/3.6.%20Step%204%20Request%20example.md)

Пример запроса включает в себя простой пример использования конечной точки, показывающий какие-то настроенные параметры.

[5. Пример и схема ответа](https://github.com/Starkovden/Documenting_APIs/blob/master/3.%20Documenting%20API%20endpoints/3.7.%20Step%205%20Response%20example%20and%20schema.md)

Пример ответа показывает простой пример ответа из примера запроса; Схема ответа определяет все возможные элементы в ответе.

<a name="map"></a>
## Карта рабочего процесса описания

Ниже наскоро сделанная карта рабочего процесса, чтобы помочь сориентироваться на каждом шаге.

| [Шаг 1. Описание ресурса](https://github.com/Starkovden/Documenting_APIs/blob/master/3.%20Documenting%20API%20endpoints/3.3.%20Step%201%20Resourse%20description.md) |-->| [Шаг 2. Конечные точки и методы](https://github.com/Starkovden/Documenting_APIs/blob/master/3.%20Documenting%20API%20endpoints/3.4.%20Step%202%20Endpoints%20and%20methods.md) |-->| [Шаг 3. Параметры](https://github.com/Starkovden/Documenting_APIs/blob/master/3.%20Documenting%20API%20endpoints/3.5.%20Step%203%20Parameters.md) |-->| [Шаг 4. Пример запроса](https://github.com/Starkovden/Documenting_APIs/blob/master/3.%20Documenting%20API%20endpoints/3.6.%20Step%204%20Request%20example.md)|-->| [Шаг 5. Пример и схема ответа](https://github.com/Starkovden/Documenting_APIs/blob/master/3.%20Documenting%20API%20endpoints/3.7.%20Step%205%20Response%20example%20and%20schema.md) |

<a name="afterTutorial"></a>
## После описания

Когда мы закончим, конечный результат будет выглядеть как настоящее описание раздела API (см. Готовый результат в разделе [Собираем все вместе](https://github.com/Starkovden/Documenting_APIs/blob/master/3.%20Documenting%20API%20endpoints/3.8.%20Putting%20it%20all%20together.md)). На практических занятиях у нас будет возможность [редактировать или создавать описание API](https://github.com/Starkovden/Documenting_APIs/blob/master/3.%20Documenting%20API%20endpoints/3.10.%20Activity%20Evaluate%20API%20referense%20docs%20for%20core%20elements.md) в выбранном [опен-сорс проекте](https://github.com/Starkovden/Documenting_APIs/blob/master/3.%20Documenting%20API%20endpoints/3.9.%20Activity%20Find%20an%20open%20source%20project.md).

> Хотя существуют автоматические способы публикации документов API, в этой главе мы сосредоточимся на содержании, а не на инструментах. В следующей главе, [Спецификация OpenAPI и Swagger](https://github.com/Starkovden/Documenting_APIs/tree/master/4.%20OpenAPI%20specification%20and%20Swagger), мы рассмотрим, как описать те же самые компоненты, используя спецификацию OpenAPI. В главе [Публикация документации по API](https://github.com/Starkovden/Documenting_APIs/tree/master/7.%20Publishing%20your%20API%20documentation) мы рассмотрим способы публикации информации.

<a name="nextSteps"></a>
## Дальнейшие шаги

Теперь, поскольку идея описания у нас есть, Вперед! к [Шагу 1. Описание ресурса](https://github.com/Starkovden/Documenting_APIs/blob/master/3.%20Documenting%20API%20endpoints/3.3.%20Step%201%20Resourse%20description.md)