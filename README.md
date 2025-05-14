## Tutorial 9

> Apa itu _amqp_?

AMQP (Advanced Message Queuing Protocol) merupakan sejenis protokol yang digunakan sebagai platform komunikasi antar sistem aplikasi melalui sistem _message queuing_. Protokol ini biasanya digunakan bersama dengan platform _message broker_ seperti RabbitMQ, di mana AMQP berperan sebagai media pengiriman _message_ oleh RabbitMQ.

> Apa yang dimaksud ` guest:guest@localhost:5672`? apa yang dimaksud _guest_ pertama, _guest_ kedua, dan _localhost:5672_?

`guest` pertama merujuk pada _username_, sementara `guest` kedua merujuk pada _password_. Lalu, `localhost:5672` menunjukkan penggunaan server lokal dengan port 5672 yang merupakan port _default_ untuk AMQP.