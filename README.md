# Golang for bioinformatics

## About Golang

[Wikipedia](https://en.wikipedia.org/wiki/Go_(programming_language))

> Open source programming language created at Google in 2007 by Robert Griesemer,
 Rob Pike, and Ken Thompson.
 It is a compiled, statically typed language in the tradition of Algol and C,
 with garbage collection, limited structural typing, memory safety features
 and CSP-style concurrent programming features added

Official site: [https://golang.org/](https://golang.org/)

### Advantages

- Easy to deploy, surports cross-compilation.

  部署简单，跨平台编译。Go编译生成各流行操作系统的二进制文件，直接运行即可，无依赖。

- High performance.

  高性能。

- Statically Typeed.

  静态类型语言。

- Concurrency of language level.

  语言级别的并发支持。

- Good language design, full tool-chains.

  关键字少，语法简单，工具链完善。

- Embedded runtime, has Garbage Collection.

  内置runtime，支持GC。

### Disadvantages

- Lacking of bioinformatical libraries, you may reinvent the wheels.
- To be added.

### Should I use

You should try if you

- Want to write some high-performance tools in short time.
- Want to protect your source code.
- Tired of complicated installation, deployment and configuration process.
- Tired of bewildering symbols of Perl, and slow speed of Python.
- Tired of the long compilation time and complication of C++.

You may think carefully if you

- Have no programming experience.
- Want to write tools with GUI.

## Try

- [A Tour of Go](https://tour.golang.org/)

## Discussions

Golang in Bioinformatcis

- [Why are 'Cool Kids' at Github Moving to GO Language?](http://homolog.us/blogs/blog/2014/01/16/golang/)
- [Learning golang for bioinformatics](https://www.reddit.com/r/golang/comments/3y1tvh/learning_golang_for_bioinformatics/)
- [Question: Bioinformatics Tutorials Utilizing The Go ( Of Google Fame ) Programming Language](https://www.biostars.org/p/14964/)

Golang

- [What are the advantages and disadvantages of Go programming language?](http://stackoverflow.com/questions/2198529/what-are-the-advantages-and-disadvantages-of-go-programming-language)
- [A Closer Look at Golang From an Architect’s Perspective](http://thenewstack.io/a-closer-look-at-golang-from-an-architects-perspective/)
- [为什么要使用 Go 语言？Go 语言的优势在哪里？](https://www.zhihu.com/question/21409296)

## Books

- [GoBooks](https://github.com/dariubs/GoBooks) - List of Golang books
- [An Introduction to Programming in Go](https://www.golang-book.com/books/intro)

## Talks

- [GoTalks](https://github.com/golang/go/wiki/GoTalks)
- [Go talks](https://talks.golang.org/)

## Tools

Libraries

- [biogo](https://github.com/biogo/biogo) - biogo is a bioinformatics library for Go
- [go](https://github.com/shenwei356/bio) - A lightweight and high-performance bioinformatics package in Go
- [irelate](https://github.com/brentp/irelate) - Streaming relation (overlap, distance, KNN) of (any number of) sorted genomic interval sets. #golang
- [hts](https://github.com/biogo/hts) - biogo high throughput sequencing repository
- [cfgo](https://github.com/brentp/vcfgo) - a golang library to read, write and manipulate files in the variant call format.

Tools

- [vcfanno](https://github.com/brentp/vcfanno) - annotate a VCF with other VCFs/BEDs/tabixed files
- [SeqKit](https://github.com/shenwei356/seqkit) - A cross-platform and ultrafast toolkit for FASTA/Q file manipulation in Golang http://shenwei356.github.io/seqkit
- [gsort](https://github.com/brentp/gsort) - sort genomic data
- [fastcov](http://yanlilab.github.io/fastcov/) - A novel algorithm for detecting multiple covariance and clustering of biological sequences
