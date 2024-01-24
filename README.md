# Hikaru Translator

## What is Hikaru Translator?
The Hikaru Translator Project is an on-going project by themirrazz to create an accurate Japanese-to-English (and eventually, English-to-Japanese) translator. While this doesn't seem like news, there's something unique about this: it aims to be written in JavaScript, meaning it can run directly in your browser. How will it translate on low end devices? Good question. While most translators for any language use AI and machine learning, we plan on implementing an already-programmed system for finding grammar instead of using AI and ML. Meaning that, yes, it will indeed run fine on low-end devices (eg smartphones, tablets, ~~the GameBoy Advance~~)

## Okay, why is this better than Google Translate?
While Google Translate is good *sometimes*, it also is not always accurate, specifically when it comes to slang. There are also many different ways you can use Japanese words and slang. Take the word `野郎` (`yarou`) - you probably here it in anime a lot, usually as `この野郎` (`kono yarou`). This literally means `this guy` (gender, not as in "hey guys")... and Google Translate says `this bastard`. This is because when this word is used as an insult, it becomes derogatory. Google Translate, however, says that `バカ野郎` (`baka yarou`) is... "you idiot"... and the reason this makes no sense... well, let's break it down for you.<br/>
They're saying the words `バカ` and `野郎`, which in Latin/Roman characters are `baka` and `yarou`. Most people know that baka means `fool` or `idiot`, and from above, we know that `yarou` is derogatory in this context. So basically, while `baka` is a noun, it's being used as an adjective.
So the true meaning would of `バカ野郎` here would be `a derogatory word for a stupid guy` - and `idiot` is *not* that word. I feel like a proper translation would be something like `stupid bastard` or maybe something people would actually say in English; `dumbass`. But I feel like `you idiot` isn't strong enough. And Google Translating `へんたい野郎` (`hentai yarou`)? Hentai means `weird(o)` or `pervert`, but if you use the kana for `hentai` instead of the kanji, Google will tell you it means... "hentai bastard". So in other words... I best not say it here.
<br/>
So with our translator, we aim to make these kinds of slang translate properly, and we actually have specific maps for adjectives used on `yarou`.
We also translate other slang properly, like `くそ` (`kuso`), which Google Translates as the f-word. (Spoiler alert - the f-word does not exist in Japanese!)

## How can I type in it?
So, it will only support input of Japanese characters, BUT, you *don't* need a Japanese keyboard! It has a built-in o
