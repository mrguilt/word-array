# Word-Array.bas

This was a programming exercise based on a [Reddit Thread](https://www.reddit.com/r/c64/comments/tweec8/how_to_format/). Basically, it was a way to demonstrate how to write something in Commodore 64 BASIC. Really, it reminded me how a modern(ish) language like Perl or JavaScript can make a task like this even simpler. 

This will take a user-input word and print it repeatedly on an array so-many characters wide and so-many rows tall:

```
Input Target Word: ? word-array.bas

How many columns? ? 7

How many rows? ? 15


word-ar
ray.bas
word-ar
ray.bas
word-ar
ray.bas
word-ar
ray.bas
word-ar
ray.bas
word-ar
ray.bas
word-ar
ray.bas
word-ar
```

I think the original poster wanted it to be word-based (so-many iterations of the word wide), but I took it to an extreme. The key lesson for me was that cbmbasic is a bit more challenging to divide a word up by characters. 

