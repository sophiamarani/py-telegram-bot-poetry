# py-telegram-bot-poetry

(Last Updated: 6 December 2020)

Using Python to create a Telegram bot that generates simple (and sappy) poetry based on name inputted by the user. You can try my Telegram bot @ohayopoetry_bot.

Where do I host my Python codes? https://www.pythonanywhere.com/ 
1) Create a free account.
2) Upload your Python codes as a File.
3) Create a Bash Console.
4) Wait for Bash Console to load. Then, type "python your_python_file_name.py" and run.

Resource: https://www.youtube.com/watch?v=jhFsFZXZbu4&t=1s

There are 4 poetry templates that are hard-coded:

TEMPLATE 1: SHAKESPEARE SONNET 14 WANNABE
- luckyName oh luckyName
- you are so very luckyAdj (fine)
- comparativeAdj (finer) than the luckySS luckyNoun (wine)
- and thus, of you this i prognosticate:
- your end is truth and beauty's doom and date!
- humbly i pray that you take my hand
- and walk with me in this beloved fate

 *(fine), (finer), (wine) > IF nounList is empty
 
 *IF adjList is empty > adjList = [… positive adj…]

TEMPLATE 2: DR SEUSS MAKING MOVES
- you have brains in your head, feet in your shoes,
- and you can steer yourself any direction you choose!
- but i would still like to offer you, my most luckySS muse,
- a promise of affection that you may refuse:
- i seek to undo all of your innate, luckyAdj blues
- and will i succeed? an honest man does not mislead
- so, it is 98 and 3/4 percent guaranteed

*IF adjList is empty > adjList = [… negative adj…]

TEMPLATE 3:  SHAKESPEARE SONNET 57 WANNABE
- wherefore do you imprison my heart, oh luckyName?
- ever since my unassuming gaze met yours,
- my soul has been luckyAdj (flummoxed) like a cursed luckyNoun (pandora’s box)
- and only you can disentangle these dreadful locks… 
- the despair! as i have turned into a fool for you and
- so true a fool is love that in your will
- though you do anything, i think no ill
*IF adjList is empty > adjList = [… negative adj…] #same list as template 2

*(flummoxed), (pandora’s box) > IF nounList is empty


TEMPLATE 4: GOLDILOCKS IN LOVE

- oh bollocks, how fast time ticks and tocks…
- where have you been all this while?
- it feels like my whole life as giddy goldilocks,
- i finally found you, the luckyAdj luckyName,
- who give me “just right” vibes and “just right” smiles/butterflies/joys/pillow talks,
- and have the absolute “just right” style/eyes/voice/body clock!

*IF adjList is empty > adjList = [… positive adj..] #same list as template 1

There are 4 Commands:
- /hello - a warm greeting for you <3
- /start - dunno what to do?
- /thingstonote - how to submit the name?
- /hug - i love you too

Other notable resources:
- Shakespearean words: https://www.litcharts.com/blog/shakespeare/words-shakespeare-invented/
- Shakespeare's sonnets: http://triggs.djvu.org/djvueditions.com/SHAKESPEARE/SONNETS/Download.pdf
- Robotic pick-up lines: http://www.jokes4us.com/pickuplines/robotpickuplines.html
- Wordnet: https://wordnet.princeton.edu/documentation/wndb5wn, https://www.geeksforgeeks.org/nlp-synsets-for-a-word-in-wordnet/
- English adjectives: https://justenglish.me/2014/03/17/positive-personality-adjectives-list/
- Japanese characters in Unicode: https://www.key-shortcut.com/en/writing-systems/%E3%81%B2%E3%82%89%E3%81%8C%E3%81%AA-japanese
- Telegram-Bot-Python Guide: https://readthedocs.org/projects/python-telegram-bot/downloads/pdf/latest/, https://github.com/eternnoir/pyTelegramBotAPI#callback-query-handler
- Reply Markup: https://pypi.org/project/pyTelegramBotAPI/, https://readthedocs.org/projects/python-telegram-bot/downloads/pdf/latest/
- Send animation (gif): https://python-telegram-bot.readthedocs.io/en/stable/telegram.bot.html#telegram.Bot.send_animation
