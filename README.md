# EvangelistBot
A node-red flow, setting a bot for telegram's groups. The bot listen the chat content and when someone use a blasfemy increase a user's counter.  With the command /rank return the leader board of all eretics!

## Getting started

First of all install [Node-RED](http://nodered.org/docs/getting-started/installation)

```
$ sudo npm install -g node-red
```

Then open  the user data directory  `~/.node-red`  and install the package

```
$ cd ~/.node-red
$ npm install node-red-contrib-chatbot
```

Then run

```
node-red
```

The next step is to create a chat bot, I recommend to use **@BotFather** to create a chat bot, [follow instructions here](https://core.telegram.org/bots#botfather) then copy you access **token** inside telegram's receiver/ telegram sender.

![Example Simple](https://github.com/H-AlessioMurta/EvangelistBot/blob/main/Insert%20bot.JPG)

## PERSONALIZE THE LANGUAGE TRIGGERS
So if you are not Italian, or you want to personalize the list words a simple example
In the node NLP.Entity update the list of characters, deity, people what you want

![d1](https://github.com/H-AlessioMurta/EvangelistBot/blob/main/d1.JPG)

Now in the first NLP.intent you should define the proper way to activate the bot:

![d2](https://github.com/H-AlessioMurta/EvangelistBot/blob/main/d2.JPG)

Now in second NLP.intent you should define what shouldn't activate the bot:

![d3](https://github.com/H-AlessioMurta/EvangelistBot/blob/main/d3.JPG)

## PERSONALIZE THE ANSWERS

You can edit what your bot reply, remember each addition in a text node will randomly send back
![image](https://user-images.githubusercontent.com/78862054/117018601-ee9a0100-acf4-11eb-8e0d-613ed3b66ab1.png)
Of course you can change URL's image to change the meme.

## Credits
Mr Bellomo's RED BOT:
https://github.com/guidone/node-red-contrib-chatbot

Please consider to donate something for his amazing work!
Maintaining **RedBot** is very time-consuming, if you like it, please consider:

<a target="blank" href="https://www.paypal.me/guidone"><img src="https://img.shields.io/badge/Donate-PayPal-blue.svg"/></a>
<a target="blank" href="https://blockchain.info/payment_request?address=17tWsZgb8CsCVZ4ZWEqRz4ekz7KjUPVagz"><img src="https://img.shields.io/badge/Donate-Bitcoin-green.svg"/></a>


## The MIT License
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
