# WhatsApp web php client

A client for WhatsApp web in PHP

## Run

```bash
docker-compose up
```

### Example of use

Run this command and read the content of file example.php:
```bash
docker-compose exec php7 php example.php
```

## Suggestions of new features

* Tests. Sugestions:
  * PHPUnit
  * PHPCS
  * PHPStan
  * Psalm
  * Phan
* Send qrcode to a Telegram bot
* Send message to person
* Hook to intercept all messages and send to Telegram Bot in conversation with predefined Telegram user
* Respond message in Telegram bot and forward the response to WhatsApp contact
* Define default reply message every time when receive new message in WhatsApp
* Identify when WhatsApp is offline and notify to user in Telegram Group to open the Whatsapp Client in cellphone