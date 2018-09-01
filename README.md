Spring Boot AMQP Sample
=======================

SprinbBoot + RabbitMqのサンプルコードです。

環境設定
---------------------
RabbitMqにタグを作ります

- localhost:15762にアクセスし、RabbitMqを開く
- Ququesタブを開き、"messageQueue"　キューを作成します


起動
--------
> amqp-consumer mvn spring-boot:run // consumer起動
> amqp-producer mvn spring-boot:run // producer起動

ランダムなIdがconsumerに引き継がれます-。
RabbitMqのoverViewからもqueueの出入りが確認できるはずです。


