Title: Learning Haskell
Date:  2015-11-05 13:10
Modified:  2015-11-04 13:10
Category: Haskell
Tags: Programming, Haskell
Slug: learning-haskell
Authors: Guido Percú
Summary: Want to learn a new way to program? Learn functional programming.

[Haskell][22d3c8cd] will change the way you think.

> It gives you a new toolset with which to solve programming problems, often yielding very clean and elegant solutions to otherwise complex problems. - [Why Study Functional Programming?](https://acm.wustl.edu/functional/whyfp.php)

>  It is my belief that functional languages, almost by definition, are closer to the top of the power spectrum than imperative ones. So languages can actually limit a programmers frame of thought. - [Why Haskell Matters?](https://wiki.haskell.org/Why_Haskell_matters)

This is the most comprehensive guide I've ever found on [how to learn Haskell](http://stackoverflow.com/questions/1012573/getting-started-with-haskell). Enjoy.

## Instalation

To install the Haskell platform on Debian systems, install the haskell-platform package:

    sudo apt-get install haskell-platform

 For information about installing it in other systems, visit the [official documentation][5ad2a93d].

 ### Hello World!

    main = putStrLn "Hello World!"

 Read more about IO in Haskell: [Input and Output][457a6d0d] | [Print x PutStrLn][f3155ad0]

 ### Fibonnaci (recursive)

    fib 0 = 0
    fib 1 = 1
    fib n = fib (n - 2) + fib (n - 1)

 ### Fatorial

    fatorial n = product [1..n]

### Books:
- [Haskell road to logic math and programming](http://www.amazon.com/Haskell-Programming-Second-Edition-Computing/dp/0954300696)
- [Learn You a Haskell for Great Good](http://learnyouahaskell.com/)

### Tutorials
- [Haskell the Hard Way](http://yannesposito.com/Scratch/en/blog/Haskell-the-Hard-Way/)
- [Picnic App](http://lisperati.com/haskell/)
- [Write you a Haskell](http://dev.stephendiehl.com/fun/)
- [Git clone in Haskell](http://stefan.saasen.me/articles/git-clone-in-haskell-from-the-bottom-up/)

### Courses:
- [Introduction to Functional Programming](https://www.edx.org/course/introduction-functional-programming-delftx-fp101x-0)
- [Curso Haskell para iniciantes, por Marcos Castro (pt-BR)](https://www.youtube.com/playlist?list=PL8eBmR3QtPL3pDzQpwPYfWQ4NEPGu6j7z)
- [Haskell From Scratch](https://www.youtube.com/playlist?list=PLxj9UAX4Em-Ij4TKwKvo-SLp-Zbv-hB4B)
- [Introduction to Functional Programming - EDX](https://www.edx.org/course/introduction-functional-programming-delftx-fp101x#.VDWTHFRdUsp)

### Tools
 - [Hoogle](http://www.haskell.org/hoogle/)
 - [HUnit](https://hackage.haskell.org/package/HUnit)
 - [QucikCheck](http://hackage.haskell.org/package/QuickCheck)
 - [Cabal](http://www.haskell.org/cabal/)
 - [Hackage](http://hackage.haskell.org/)

### Awesome
 - [Awesome Haskell](https://github.com/krispo/awesome-haskell)

### Web Frameworks
 - [Happstack](http://happstack.com/page/view-page-slug/1/happstack)
 - [Snap](http://snapframework.com/) | [REST API with Haskell and Snap](https://robots.thoughtbot.com/a-rest-api-with-haskell-and-snap)
 - [Yesod](http://www.yesodweb.com/) | [Tutorial Yesod](http://yannesposito.com/Scratch/en/blog/Yesod-tutorial-for-newbies/)
 - [Official List of Frameworks](http://www.haskell.org/haskellwiki/Web/Frameworks)

### Exercises
 - [Hacker Rank](http://www.hackerrank.com/)
 - [Project Euler](https://projecteuler.net/) | [Euler 1-10 Solutions in Haskell](https://wiki.haskell.org/Euler_problems/1_to_10)

### More links
 - [FP Complete School of Haskell](https://www.fpcomplete.com/school)
 - [Functional Reactive Programming](https://wiki.haskell.org/Functional_Reactive_Programming)
 - [Evolution of a Haskell Programmer](http://www.willamette.edu/~fruehr/haskell/evolution.html)
 - [FP Complete School of Haskell](https://www.fpcomplete.com/school)
 - [C2 Wiki - Functional Programming Language](http://c2.com/cgi/wiki?FunctionalProgrammingLanguage)

  [22d3c8cd]: https://www.haskell.org/ "Haskell Language"
  [5ad2a93d]: http://www.haskell.org/platform/ "Haskell platform installation guide"

  [457a6d0d]: http://learnyouahaskell.com/input-and-output "Learn Yourself a Haskell - Input and Output"
  [f3155ad0]: https://stackoverflow.com/questions/19288652/difference-between-print-and-putstrln-in-haskell "Stackoverflow: Differences between Print and PutStrLn"
