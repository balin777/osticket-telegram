osTicket-telegram
==============
An plugin for [osTicket](https://osticket.com) which posts notifications to a [Telegram](https://telegram.org) channel/chat/group.
Мне понадобилась оповещалка для телеги, и я форкнул этот плагин. 
Дописал чуть более продвинутый дебаг, и возможность гнать трафик через SOCKS5 proxy.


## Note
This project is no longer maintained.

Install
--------
Clone this repo or download the zip file and place the contents into your `include/plugins` folder.
Insert Telegrams Bot URL for your bot (ex. `https://api.telegram.org/bot<token>/`) and Chat ID.

For more information about Telegram Bot, see: https://core.telegram.org/bots/api

Info
------
This plugin uses CURL and tested on osTicket-1.10.1

Based on [thammanna/osticket-slack](https://github.com/thammanna/osticket-slack)
