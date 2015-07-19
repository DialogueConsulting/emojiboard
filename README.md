# emojiboard
Adds an emoji keyboard to any text box. Requires jQuery and jMinEmoji.

This plugin is in use with Schedugram, an Instagram scheduling solution. Our customers post tons of Emoji and I couldn't find anything that would do this, so we built one.

# Demo

Link to web demo.

# Installation
## Dependencies
You need to have jQuery >1.10.2.

Emojiboard uses a modified version of [jMinEmoji by @rodrigopolo(https://github.com/rodrigopolo/minEmoji) so all credit to jMinEmoji for those parts!

## Usage
In your page header, add the emojiboard CSS (use the version in this repo!):
```
<link href="css/emojiboard.css" rel="stylesheet">
```

And before closing &lte;body&gte; add the two JS files – one is the list of Emoji and the other is the function itself (including jMinEmoji):
```
<!-- don't forget jQuery -->
<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<!-- List of emojis -->
<script src="js/emojis.js"></script>
<!-- emojiboard itself -->
<script src="js/emojiboard.js"></script>

```

Make sure you have put the images into an img/ folder too...

Add the class "emojiboard" (or whatever you want) to any &lte;textarea&gte;'s you want to append an emojiboard to:
`<textarea class="emojiboard"></textarea>`

And then initialise emojiboard on those areas:

`$(".emojiboard").emojiboard();`

# Roadmap
_Pull requests welcome!_

* only use 2x when required (currently it loads by default #lazy)
* ?mobile compatibility - needs to be checked and/or emojiboard only shown when not on iOS/Android...
* Re-order emojis so the layout/sequence is the same as iOS
* Update to add new iOS emoji


# License
MIT