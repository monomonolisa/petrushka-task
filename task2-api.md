**#Задание 2: Проектирование API**

**Цель:**
Спроектировать REST API для получения списка магазинов-партнёров с информацией о времени доставки и ссылками для перехода, необходимых 
для отображения нового экрана в мобильном приложении.

**Пример REST API запроса**
```GET /api/v1/stores```

**Пример ответа REST API**
```
[
    {
        "id": 1,
        "name": "METRO",
        "partner_link": "https://www.metro-cc.ru"
        "delivery_info": {
            "type": "scheduled",
            "date": "25-02-2026",
            "timefrom": "21:00",
            "timeTo": "23:00"
        }
    },
    {
        "id": 2,
        "name": "Ашан",
        "partner_link": "https://www.auchan.ru"
        "delivery_info": {
            "type": "scheduled",
            "date": "25-02-2026",
            "timefrom": "18:00",
            "timeTo": "20:00"
        }
    },
    {
        "id": 3,
        "name": "ВкусВилл",
        "partner_link": "https://vkusvill.ru"
        "delivery_info": {
            "type": "express",
            "date": "25-02-2026",
            "timefrom": "00:20",
            "timeTo": "01:00"
        }
    },
    {
        "id": 4,
        "name": "ВИКТОРИЯ",
        "partner_link": "https://victoria-group.ru/"
        "delivery_info": {
            "type": "scheduled",
            "date": "25-02-2026",
            "timefrom": "17:00",
            "timeTo": "19:00"
        }
    }
]```
