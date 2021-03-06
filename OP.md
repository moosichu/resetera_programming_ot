# Discord

Quote [the post linked here](https://www.resetera.com/posts/462255/) to reveal the link to the Discord.

# What is programming?

[quote] Computer programming (often shortened to programming) is a process that leads from an original formulation of a computing problem to executable computer programs. Programming involves activities such as analysis, developing understanding, generating algorithms, verification of requirements of algorithms including their correctness and resources consumption, and implementation (commonly referred to as coding) of algorithms in a target programming language. [/quote]


From Wikipedia.

Basically:

[quote] Write instructions for a computer. Computer then follows those instructions [/quote]

# Where do I start?

Here is a good place! Feel free to ask any questions, and we will gladly give advice.

It honestly depends what you are interested in, and what you intend to use the programming for. Programming as a skill is essentially the ability to use a wide range of tools adepts at completely different tasks - the skills are transferable, but the trains of thought can sometimes be completely different.

Python is great language to start with, and what I personally learnt first.

# What is a 'Programming Paradigm'

Thanks to the work of Turing, Church and others in the early 1900s, it was discovered that loads of different semantics (ways of doing things) for expressing algorithms ultimately could be used to express exactly the same set of computable programs - what we know call Turing completeness.

However, these different semantics have different tradeoffs in terms of *how easy* it is to express what you want, how is it is to *maintain* the code that you have written, and *how fast* that code runs on your actual machine. All depending on context as well.

Essentially, different paradigms are different styles of programming, which are better suited to different tasks (and also different people). A programming language will typically support one or more of these paradigms. The lines between them can get quite blurred as well.

To give you a better idea of what they are, here are some example paradigms:

## Imperative

One of the easiest to understand. Literally a sequence of instructions which do things. Most languages support this in some form - the most well known being C.

## OOP (Object Oriented Programming)

Maintaining code written in imperative languages can be hard. So the idea behind OOP languages is to provide the ability to represent programming data structures using something known as 'encapsulation' - the ability to hide the inner workings of something in order to expose a clean *interface* that can be used very easily. This, in theory, makes maintaining the code easier, as you can change the *implementation* of certain parts of your code base, without affecting other parts of your code base.

## Functional Programming

The idea behind functional languages is that *functions are pure*, that is, they cannot have any side-effects. Therefore, when you use a function, it doesn't have any effect except the computation it performs to calculate the value it returns - a function in a functional program won't suddenly start doing things you don't expect!

While this makes performance potentially worse than in imperative programs, and can be quite labourus to write, functional languages can also be very easy to read and made to run in parallel across many-core processors.

TODO: add more examples and better explanations to this list!

# What languages are there? What are they good for? How do I learn them?

## C

C is one of the oldest but most widely used languages out there. It's incredibly powerful and blindingly fast. Unfortunately, it can also be unwieldy, due to both being incredibly low-level, and having design that's decades old.

The Linux Kernel is written in C.

## C++

C++ is essentially C, but with loads of 'modern' (it started development in 1979) language features. It was originally designed to be compatible with C, but no longer strictly is.

Unfortunately, it suffers from a lot of the same problems that C does, design with, with a fair few problems of its own. But it's low level expressiveness, the power it provides, alongside the weird and wonderful/horrible template metaprogramming paradigm have made it the systems and applications programming language of choice for many people.

Oh, and most game engines are written in C++.

- [LearnCpp.com](http://www.learncpp.com/)

## JavaScript

Originally written in 10 days as a 'glue' language that would be used to connect 'serious' languages (like Java, and Flash) together, JavaScript has since become the back-bone of a lot of the internet (in NodeJS), and the front-bone of even more!

It's an incredibly rapidly evolving language - to such an extend the 'new' stuff you could be learning in one year could be out of date the next!

## Java/C#

These two languages have been lumped together as they are very similar. They are both Object Oriented languages that have been designed to be similar to C++ is an appearance. They steal some ideas from C++, but due to garbage collection, are much easier to use.

However, this also makes them slower.

## Haskell

Haskell is *the* functional language that Computer Scientists like to rave about. It takes the functional programming paradigm and *owns* it.

- Good things have been said by [Learn You a Haskell](http://learnyouahaskell.com/)

## PHP

This is a language that powers a lot of the web (including ResetEra!). It isn't going away anytime soon, but it has fallen by the wayside in favour of languages such as JavaScript.

## Python

A really cool language that can do pretty much everything you can think of, and quickly. A really good language for machine learning and writing quick scripts - it's a great place to start learning.

 - [python-course.eu](https://www.python-course.eu/) is a good starting resource.

## Rust

Rust is a low level language like C, but designed to not have a lot of the problems C in terms of legacy design and lack of safety. The primary goal of Rust is to be safe, by making sure the programmer doesn't have raw access to memory.

## Swift

Apple had a go at making a language for people to use when writing for their machines after they got bored of Objective-C. This is what they came up with.

# Development Environments (IDE)

An IDE (Short for "Integrated Development Environment") are tools that can be used to help you program. Beyond providing the basic text-editing features you need to edit source code, they can provide other tools to help you auto-complete, debug, inspect and otherwise play around with your code in manners which (ideally) improve your productivity.

## [Visual Studio](https://www.visualstudio.com/)

Use this to program in .NET, C, C++, F#, and so on. A powerful IDE, that can get a bit overwhelming at times. Let us take a moment to mourn the loss of project.json †

## [Rider](https://www.jetbrains.com/rider/)

A newcomer in the .NET sphere. Haven't tried this yet, but it's made by Jetbrains, who's other IDE IntelliJ IDEA, is one of the best Java IDE's. If anyone has tried it or is using it, be sure to post about it!

## [Visual Studio Code](https://code.visualstudio.com/), [Atom](https://atom.io/)

These are 'IDEs' that are based on extension. Starts out as a text editor with highlighting and some basic development features, but can be extended with plugins that enable you to program for all your favorite languages.

## [Sublime Text](http://www.sublimetext.com/)

Along the lines of VS Code and Atom, but even more basic. Don't think you can debug in here, but I just wanted to add it because it's just so fast, snappy, and extensible, making it perfect for scripting.

# Further Resources

This needs to be fleshed out, as I don't know what is good and what isn't!

Any recommendations  would be really appreciated!

- [this](https://www.cl.cam.ac.uk/teaching/1516/OOProg/handout.pdf) what I used to learn how to program.

- [Game Engine Architecture](http://gameenginebook.com/) by Jason Gregory, is a great book about how game engines work.

- [The Pragmatic Programmer](https://www.amazon.com/Pragmatic-Programmer-Journeyman-Master/dp/020161622X) as recommended by [Wollan](https://www.resetera.com/threads/programming-ot-functional-imperative-oop-cargo-cult-all-are-welcome.1335/#post-75972)

- [Learn X in Y Minutes](https://learnxinyminutes.com/), as useful resource for experienced programmers that want to learn about a new language. Recommended by [Code Artisan](https://www.resetera.com/threads/programming-ot-functional-imperative-oop-cargo-cult-all-are-welcome.1335/page-2#post-413998)

# Improving this post

There is a [GitHub Repo](https://github.com/moosichu/resetera_programming_ot) which contains this OP, please feel free to make any pull requests containing improvements to this!

Also feel free to create any [issues](https://github.com/moosichu/resetera_programming_ot/issues) for things you would like to see added to the OP!

# Special Thanks

To:

- phisheep for the Haskell and Python learning resources!

- emesve for the IDE section!

# Note

I will try to listen to any feedback to this OT, and add anything you feel is worthwhile! Especially with resources for learning programming languages, I really don't know what the best ones are!

[CURRENTLY ACCEPTING THREAD TITLE SUGGESTIONS](https://github.com/moosichu/resetera_programming_ot/issues/1)