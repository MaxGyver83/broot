
**broot** is developed by [Denys Séguret](https://twitter.com/DenysSeguret), also known as [Canop](https://github.com/Canop) or [dystroy](https://dystroy.org).

# Discuss Broot in a chat room

The best place to chat about broot, to talk about features or bugs, is the Miaou chat.

There's a dedicated room:

[![Chat on Miaou](https://miaou.dystroy.org/static/shields/room-en.svg?v=1)](https://miaou.dystroy.org/3490?broot) **broot**

If you're French speaking, you might prefer to directly come where other French speaking programmers hang:

[![Chat on Miaou](https://miaou.dystroy.org/static/shields/room-fr.svg?v=1)](https://miaou.dystroy.org/3) **Code & Croissants**

Don't hesitate to come if you have a question.

# Issues

We use [GitHub's issue manager](https://github.com/Canop/broot/issues).

Before posting a new issue, check your problem hasn't already been raised and in case of doubt **please come first discuss it on the chat**.

# Your wishes

[Issues](https://github.com/Canop/broot/issues) is also where I test new ideas. If you're interested in the directions broot takes, **please come and vote on issues**, or maybe comment. This would help me prioritize developments: if nobody's interested in a feature I'm not sure I want, I'll do something else.

# Log

When something looks like a bug, especially keyboard problems, we need both to know the exact configuration (OS, terminal program, mainly) and to have the log. The log can be obtained this way:

1. start broot with `BROOT_LOG=debug br`
2. do the action which seems not to properly work, and nothing else
3. quit broot
4. go to the chat (or the GitHub issue if you already made one) and paste the content of the `broot.log` file

# Benchmark

To get a precise idea of the time taken by operations in real broot use, it's often a good idea to run them with `--cmd`.

For example full text search performances can be measured (and compared to other tools) with

```
time broot -c "c/memmap;:pt" ~/code
```

# Contribute

**Broot** is written in [Rust](https://www.rust-lang.org/). The current focus is linux+mac but we try to support Windows too (use PowerShell instead of the old cmd).

Before starting working on a Pull Request, please join the Miaou room to coordinate the development. There are frequently several feature branches waiting to be merged and adding some wild ones may make the process painful.

A PR must be also be *focused*. Don't touch other code and don't refactor or reformat without discussion.

If you think you might help, as a tester or coder, you're welcome.

# This documentation...

... needs your help too.

Tell us what seems to be unclear or missing, what tricks should be added.

And if you have interesting screenshots telling a story, they might find their way into a new page too.
