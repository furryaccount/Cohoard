# Cohoard - Post formatted chatlogs to Cohost!

Cohoard is a tool for turning chatlogs into formatted posts on Cohost. You can use Cohoard to easily format your silly conversations like a Discord channel, an MSPA chatlog, and so on.

## Discord Template

Currently the only option available is the Discord template, which stylizes conversation as Discord chatlogs.

```
@ Today at 4:13 PM
AARON: you can write messages in play-script style
AARON: each line is considered it's own "message"
AARON: by default, messages are collapsed together, and the avatar + username only shows up once
@
AARON: however, the @ symbol, when used by itself on a newline, will break up a sequence of messages and force the avatar + username to display again.
@ Tomorrow at 6:12 AM
AARON: you can also use the @ symbol to set the timestamp of the message. This will also make the avatar + username show up again.
AARON: the timestamp text is freeform--feel free to write any time you like.
CASSIE: Also, other people can be mixed into the chat log seemlessly.
CASSIE: Finally, if you have a multi-line message
(That is to say, a single message that itself contains newlines),
you can simply write those out on their own line, with the "USERNAME:" header at the start.
Note that multi-line messages are rendered slightly closer together than seperate messages.
CASSIE: For example
CASSIE: these are farther apart
CASSIE: since these are seperate messages
CASSIE: While these lines
are closer together
since they're in the same message.
AARON: oh yeah! you can also *use normal markdown* ~~like you do in discord~~ **and it should hopefully just work**
CASSIE: (Right now, <u>Discord-style underlines</u> don't quite work yet, but you can use normal HTML tags instead.)
CASSIE: (The above line is written as `<u>underlines</u>`.)
```

This produces the following result:

![The rendered result of the above chatlog, which is stylized as a Discord conversation](readme-images/discord_template.png)