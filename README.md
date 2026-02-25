# Practical lesson pz-MQTT MAZUR
# Розгортання та налаштування MQTT-брокера  

---

## Виконано:
* Розгорнуто MQTT-брокер (EMQX)
* Налаштувано базову конфігурацію сервісу  
* Ознайомлено із принципами роботи MQTT-протоколу  
* Виконано публікацію та підписку на MQTT-топіки через Postman та вебінтерфейс EMQX  

---

## Getting started

В практичній роботі реалізовано публікацію та підписку за допомогою брокера EMQX та Postman.

```bash
docker-compose up -d

```

```
├── stt-pz-3
│   ├── broker
│   │   ├── docker-compose.yml # варіант розгортання брокера
│   ├── screenshots            # докази роботи Publish/Subscribe у Postman, вебкліенті, вебінтерфейсі EMQX
│   ├── .editorconfig
│   ├── .gitignore
│   ├── README.md
└──

```
## Usfull links

[MQTT Essentials](https://www.hivemq.com/mqtt-essentials/)

[EMQX Documentation](https://www.emqx.io/docs/en/latest/)

[Eclipse Mosquitto](https://mosquitto.org/)

[MQTT with Postman](https://learning.postman.com/docs/sending-mqtt-messages/intro-to-mqtt/)

[NGINX API Gateway](https://docs.nginx.com/nginx/admin-guide/api-gateway/)
