# Telegram OpenCart
API : [![Build Status](https://travis-ci.com/Indeoo/telegram-opencart-api.svg?branch=master)](https://travis-ci.com/Indeoo/telegram-opencart-api)
Bot: [![Build Status](https://travis-ci.com/onidoru/telegram-opencart-bot.svg?branch=master)](https://travis-ci.com/onidoru/telegram-opencart-bot)

This project aims to build an open-source platform for building own Telegram-based
bot-driven shop with rich support of microtransactions. Being a platform that provides
an opinionated way of building an e-commerce platform, it is yet flexible and 
customizable.

Future plans and main directions of development include developing a predefined 
generalized DB schema, integrate Privat24 bot and transactions, 
interactive communication and easy-to-use Admin/Seller functionality via app bot.

## Prerequisites:
- Docker

## Start up guide:
```` 
$ git clone --recurse-submodules -j8 git://github.com/indeoo/telegram-opencart.git
$ cd telegram-opencart
$ docker-compose up
