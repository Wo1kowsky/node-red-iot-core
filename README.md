# node-red-iot-core

## Node-RED для Yandex IoT Core (рабочее название)


План статьи на базе так называемой техники STAR - начиная с описания ситуации и задачи (ST = Situation/Task), потом с действий, которые вы сделали (A = Actions) и заканчивая результатами (R = Results):

### <Вит> 1) Краткое описание про что такое Node-RED - изумительный инструмент для быстрого прототипирования на Node.JS

Как было отмечено ранее, одним из наиболее важных факторов ограничивающих развитие интернета вещей является отсутствие удобных средств разработки правил взаимодействия устройств IoT между собой. Для решения этой задачи был разработан Node-RED, позволяющий через браузер построить схему взаимодействия устройств между собой и внешними системами.

### <Вит> 2) Можно кратко написать про ключевого разработчика (Nicholas O'Leary/UK/IBM) и сообщество Node-RED

Node-RED is made available under the terms of the Apache 2 license. It's important to understand the terms of that license, but this provides a good summary - https://tldrlegal.com/license/apache-license-2.0-(apache-2.0) The license allows for commercial usage. The main restrictions are: they cannot misrepresent the Node-RED trademark (which belongs to the OpenJS Foundation) and they cannot hold the project liable for anything they chose to do with it.

### <Вит> 3) Постановка задачи - интеграция Node-RED c Yandex IoT Core для создания прототипа приложения "Умное ЖКХ" или "Самоуправляемые Автомобили" лизнуть Яндексу (вставить любое)

### <Макс> 4) Создание ВМ на CentOS и установка Node-RED и автоматический запуск сервиса (автозагрузка) через systemctl

### <Макс> 5) Детальная настройка Yandex IoT Core: создание реестра, устройста и id/логины/пароли

### <Макс> 6) Создание приложения в Node-Red (MQTT-nodes-out-in, function, dashboard)

### <Вит> 7) Краткое заключение / набор полезных материалов (ссылки)


На перспективу (Roadmap)
- Адаптировать коннектор NodeRED для Яндекс IoT Core (MQTT) чтобы было меньше полей
- Написать коннектор NodeRED для Яндекс ServerLess
