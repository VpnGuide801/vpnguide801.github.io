[Краткое описание]

{% include-markdown "setup/install_keenetic.md" %}

{% include-markdown "setup/wireguard_connection.md" %}

## Этап 3: Загрузка маршрутов

!!! abstract "Альтернативная инструкция "Этапа 3""

    Если у вас возникнут какие-то сложности на текущем этапе, читайте эту [инструкцию от Blackrock](https://rockblack.su/vpn/dopolnitelno/diapazon-ip-adresov).

<span class="h3">Шаг 1</span>

Скачайте файлы с маршрутами для тех сервисов, которыми пользуетесь. 

Маршруты: 

- [ChatGPT(OpenAI)_0.0.5.bat](../files/ip_subnets/ChatGPT(OpenAI)_0.0.5.bat) - обновлено 09.09.2024
- [Discord_0.0.1.bat](../files/ip_subnets/Discord_0.0.1.bat) - обновлено 08.10.2024
- [Facebook_0.0.2.bat](../files/ip_subnets/Facebook_0.0.2.bat) - обновлено 19.08.2024
- [Instagram_0.0.6.bat](../files/ip_subnets/Instagram_0.0.6.bat) - обновлено 24.08.2024
- [Netflix_0.0.5.bat](../files/ip_subnets/Netflix_0.0.5.bat) - обновлено 09.09.2024
- [Notion_0.0.1.bat](../files/ip_subnets/Notion_0.0.1.bat) - обновлено 09.09.2024
- [TikTok_0.0.3.bat](../files/ip_subnets/TikTok_0.0.3.bat) - обновлено 19.08.2024
- [Twitter_0.0.6.bat](../files/ip_subnets/Twitter_0.0.6.bat) - обновлено 21.09.2024
- [YouTube_0.2.bat](../files/ip_subnets/YouTube_0.2.bat) - обновлено 14.10.2024

<span class="h3">Шаг 2</span>

Перейдите в раздел "Сетевые правила", далее "Маршрутизация". Нажмите на кнопку "Загрузить из файла".

![img.png](../images/img_50.png)

<span class="h3">Шаг 3</span>

Выберите в выпадающем меню настроенный ранее интерфейс Wireguard. 

![img.png](../images/img_51.png)

<span class="h3" id="step_3_4">Шаг 4</span>

Нажмите на кнопку загрузки файла, которая находится под выпадающим списком.

![img.png](../images/img_52.png)

<span class="h3" id="step_3_5">Шаг 5</span>

Выберите один из скачанных файлов с маршрутами сервиса, который хотите разблокировать и нажмите кнопку "Открыть". Если вы скачали несколько файлов с маршрутами, повторите [Шаг 4](#step_3_4) и [Шаг 5](#step_3_5) для каждого файла. 

![img.png](../images/img_53.png)