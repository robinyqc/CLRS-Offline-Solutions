<p align="center">
  <img src="./assets/cover.png" width="150" alt="CLRS">
</p>


# Solutions to **Introduction to Algorithms** _Third Edition_

###### *Off-line Edition*



*Author:  walkccc*

*Source website: [walkccc.me/CLRS](https://walkccc.me/CLRS)*

*Off-line edition author:  robinyqc*



## Why Off-line Edition?

*by robinyqc*

Without Internet I can't visit the website, but I some times can't connect to the Internet but work off-line, not able to read the solutions. 

It's pleasant that the author walkccc shared the Markdown documents on Github.  Now it's OK to read it off-line. So here comes the off-line edition.

It provides a site that can start both on-line and off-line. And it keeps the contents from the source website, with no changes.

The aim of this edition is: No Internet, no building, just local serve it.



## How to Start It?

*by robinyqc*

It's really easy! You just need to download Python. And then use the following command in folder `site` through terminal:

```
python -m http.server
```

It'll tell you the serving HTTP port (**normally 8000**). Then you can visit this site on your browser (replace "port" with the told port, normally 8000):

```
http://localhost:port
```




## Getting Started

This **[website](https://walkccc.github.io/CLRS/)** contains nearly complete solutions to the bible textbook - [**Introduction to Algorithms** _Third Edition_](https://mitpress.mit.edu/books/introduction-algorithms-third-edition), published by [Thomas H. Cormen](https://mitpress.mit.edu/contributors/thomas-h-cormen), [Charles E. Leiserson](https://mitpress.mit.edu/contributors/charles-e-leiserson), [Ronald L. Rivest](https://mitpress.mit.edu/contributors/ronald-l-rivest), and [Clifford Stein](https://mitpress.mit.edu/contributors/clifford-stein).

I hope to organize solutions to help people and myself study algorithms. By using [Markdown (.md)](https://en.wikipedia.org/wiki/Markdown) files and [KaTeX](https://katex.org) math library, this page is much more readable on portable devices.

_"Many a little makes a mickle."_

## Contributors

Thanks to the authors of [CLRS Solutions](https://sites.math.rutgers.edu/~ajl213/CLRS/CLRS.html), [Michelle Bodnar](mailto:chellebodnar@gmail.com) (who writes the even-numbered problems) and [Andrew Lohr](mailto:Andrew.Lohr@gmail.com) (who writes the odd-numbered problems), [@skanev](https://github.com/skanev), [@CyberZHG](https://github.com/CyberZHG), [@yinyanghu](https://github.com/yinyanghu), [@Gutdub](https://github.com/Gutdub), etc.

Thanks to [all contributors on GitHub](https://github.com/walkccc/CLRS/graphs/contributors), you guys make this repository a better reference!

Special thanks to [@JeffreyCA](https://github.com/JeffreyCA), who fixed math rendering on iOS Safari in [#26](https://github.com/walkccc/CLRS/pull/26).

If I miss your name here, please tell me!

## Motivation

I build this website since I want to help everyone learn algorithms by providing something easy to read on mobile devices.

Therefore, if any adjustment is needed or you have the same motivation to contribute to this work, please don't hesitate to give me your feedback. You can press the "pencil icon" in the upper right corner to edit the content or [open an issue](https://github.com/walkccc/CLRS/issues/new) in [this repository](https://github.com/walkccc/CLRS/). Your solution will be rebased after I review it and make some form modifications to your pull request.

There're lots of [issues](https://github.com/walkccc/CLRS/issues) regarding to solutions in this repository, if you have time, please take a look and try to help people on the internet :)

Thank you very much, and I hope that everyone will learn algorithms smoothly.

## How I Generate the Website?

I use the static site generator [MkDocs](http://www.mkdocs.org/) and the beautiful theme [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) to build this website.

As for rendering math equations, I use [KaTeX](https://katex.org/), which is fast and beautiful.

I also add `overflow-x: auto` to prevent the overflow issue on small screen devices so that you can scroll horizontally in the math display equations.

## More Information

For a clear commit history, I rebase my repository regularly. Therefore, if you have forked the repository before, consider re-forking it again.

For more information, please visit [**my GitHub**](https://github.com/walkccc).

Updated to this new page on April 13, 2018, at 04:48 [(GMT+8)](https://time.is/GMT+8).

Revised on July 21, 2019.

## License

Licensed under the MIT License.
