# ispure
a function that checks whether an expression is pure (has no side effects). returns `t` if it's pure and the reason why it *isn't* otherwise. it cannot check for external functions, so you must define them yourself.
yes, it's a repository for a single function. I spent my whole afternoon writing it to prove myself it was possible and I'm not getting rid of it now.

## dependencies
- [rxi/fe](https://github.com/rxi/fe)
- a host application that embeds fe, reads the function somehow and provides a `type` function/primitive.

## faq

### who needs this?
idk, functional programmers I guess?

### why should I use it?
idk either

### ...why did you do this again?
kasjdlaskjdlksajdlsajdlaskdjlaskjdlaskdjalskdjalskjdalskdjaslkdjalskdjalskdjaslkdjasldkjasldakjsldkjaslkdjalsdjlaskjdakasjdlaskjdlksajdlsajdlaskdjlaskjdlaskdjalskdjalskjdalskdjaslkdjalskdjalskdjaslkdjasldkjasldakjsldkjaslkdjalsdjlaskjdakasjdlaskjdlksajdlsajdlaskdjlaskjdlaskdjalskdjalskjdalskdjaslkdjalskdjalskdjaslkdjasldkjasldakjsldkjaslkdjalsdjlaskjda
