---
weight: 30
---

comments
========
comments are very important to makeing sure code is clear and readable.
Ig you're working on a project alone. don't comment, take a break, then come
back after even as soon as week later you maybe spend a hour or so trying to
figure out what you've already done if you don't use comments. Comments are even
more important if you are working with multiple programmers, if you can read
your own code without comments, then others certainly can't.  the following
outlines how to effectivly use comments.

how to comment
--------------


when and what to comment
------------------------
> in the below example there's to many comments and they all explain what's
already clear just by looking at the code.

```C
//infinite loop
while(1) {
    //loop 10 times
    for(int i = 0; i < 10; i++) {
        //run foo with i + x as the argument
        foo(i + x);

        //run bar
        bar();
    }

    //run barfoo
    barfoo(5);

}
```

> in this example instead of explaining each line of code and what it does,
comments just breifly expain why certain code is there.
comments just breifly expain why certain code is there.

```C
while(1) {
    //in order to obtain correct readings foo must be run 10 times
    for(int i = 0; i < 10; i++)
        foo(i + x);
        bar();
    }

    //make sure the retro encabulator is callibrated to 5
    barfoo(5);

}
```

When writing comments explain breifly what the code is for but don't go into
detail about how it works.  If a comment takes up for than 2 lines it's probally
to long (with the exception of headers and doxygen comments).
