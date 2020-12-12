&emsp;&emsp;这是从[Awesome Compilers](https://github.com/aalhour/awesome-compilers) fork下来的，它是编译器、解释器、虚拟机和语言运行时方面的学习资料清单，在我第一次看到该仓库时就深深吸引了我——编译器这些，是最酷的东西。考虑到这个仓库是面向国人的，因此只留下来了部分内容，方便起见，中译版放到了前面。其余内容请移步[原仓库](https://github.com/aalhour/awesome-compilers) 。

&emsp;&emsp;可以按照下面格式提交Pull Request，完善它们:

&emsp;&emsp;Pull Request包括如下内容：

1. 这是什么？（课程/书...）
2. 为什么推荐它
3. 购买/查看链接，以及原始链接（如果是中文版的）
4. 一个精简的标题

&emsp;&emsp;我尽可能找了它们的中译版。但是看起来这是个困难的活（才发现中译版是如此的少...）。

&emsp;&emsp;走，一起学它\*\*的！

## 目录

  * [书](#books)
    + [Easy - 概述级](#Overview)
    + [Normal - 介绍级](#introductory)
    + [Hard - 专业级](#advanced)
    + [Lunatic - 论文](#papers)

## Books

### Overview

  * [深入理解计算机系统](http://product.dangdang.com/1694404652.html)
    + 计算机的一般性介绍，包括编译过程、解释过程和运行时。
    + 原书：[Computer Systems: A Programmer’s Perspective](https://www.amazon.com/dp/9332573905)。
  * [计算机程序 - 构造与解释](http://product.dangdang.com/27900704.html)
    + 在Scheme语言里面写一个Scheme解释器来学习计算机程序的知识。
    + 原书：[Structure and Interpretation of Computer Programs](https://mitpress.mit.edu/sicp/full-text/book/book.html)
      * 在线阅读:  [HTML5/EPUB version](https://sarabander.github.io/sicp/).

### Introductory

  * [编译原理](http://product.dangdang.com/20427584.html)     
    + 即很多人所说的“龙书”，编译原理的经典教程。    
    + 原书：[Compilers: Principles, Techniques and Tools](https://www.amazon.com/dp/0321486811)
    
  * [编译器设计](http://product.dangdang.com/22938487.html)    
    + 内容现代化的编译原理教科书，内容覆盖面广，涉及SSA等内容。   
    + 原书：[Engineering a Compiler](https://www.amazon.com/dp/012088478X)
    
  * [现代编译原理(C语言版)](http://product.dangdang.com/25260085.html)     
    + 即我们所说的“虎书”，这本书的覆盖面非常全面，而且有代码示例。作者写了好几个个版本。
    + "原"书(ML版)：[Modern Compiler Implementation in ML](https://www.cs.princeton.edu/~appel/modern/ml/)
      * 在线阅读: [C语言版](https://www.cs.princeton.edu/~appel/modern/c/)
      * 在线阅读: [ Java版](https://www.cs.princeton.edu/~appel/modern/java/).
    
  * [自己动手实现Lua](http://product.dangdang.com/25479678.html)
    + 用Go写一个Lua的编译器和解释器，以及虚拟机。建议至少看完一本编译器相关内容的书再阅读，会更有深度。

  * [Basics of Compiler Design](http://www.diku.dk/hjemmesider/ansatte/torbenm/Basics/)
    + 介绍编译器相关的基本概念，没有中译版。
  
  * [Beautiful Racket](http://beautifulracket.com)
    
    + 如何用Racket制作自己的编程语言。没有中译版。
  
  * [Build Your Own Lisp](http://www.buildyourownlisp.com)
    
    + 用1000行C代码编写一个你自己的Lisp。没有中译版。
  
  * [Crafting Interpreters](http://www.craftinginterpreters.com/)
    + 一个内容全面，讲述如何构建一个解释，功能齐全，高效的脚本语言的书籍。本书没有中译版，在下面可以在线阅读：
       * [GitHub Repo](https://github.com/munificent/craftinginterpreters).
       * Discussions: [HN](https://news.ycombinator.com/item?id=13406081).
    
  * [Create Your Own Programming Languauge](http://createyourproglang.com/)
    + 构建你自己的编程语言~本书没有中译版。
       * Discussions: [HN](https://news.ycombinator.com/item?id=813133).
    
  * [Essentials of Programming Languages](https://www.amazon.com/dp/0262062798)
    + 编程语言的基本概念，比较侧重于语义、可解释性、CPS等等。本书没有中译版。

  * [Language Implementation Patterns](https://www.amazon.com/dp/193435645X)  
    + 学习编程语言背后的细节，并使用ANTLR写一个自己的解释器

  * [Programming Language Pragmatics](https://www.amazon.com/dp/0123745144)
    + Integrated treatement of language design and implementation, the examples feature famous architectures like ARM and x86 64-bit.

  * [Programming Languages: Application and Interpretation](http://cs.brown.edu/courses/cs173/2012/book/)
     + Excellent introduction to the subject that uses an incremental approach to building programs. The mistakes are included too to highlight key concepts.
       * [PDF](http://cs.brown.edu/courses/cs173/2012/book/book.pdf).
    
  * [Programming Languages: Theory and Practice](http://people.cs.uchicago.edu/~blume/classes/aut2008/proglang/text/offline.pdf)
    + Collected lecture notes for the _Programming Languages_ course taught at Carnegie Mellon University, most suitable as an introductory text on the subject.

  * [Project Oberon](http://people.inf.ethz.ch/wirth/ProjectOberon1992.pdf)
     + The design of an operating system and compiler.
       * Other editions: [2013 Edition](http://www.cs.cmu.edu/~fp/courses/15312-f04/handouts/).
    
  * [The BEAM Book](https://github.com/happi/theBeamBook)
     + Description of the ERTS (Erlang Runtime System) and the BEAM Virtual Machine.

  * [Virtual Machines](https://www.amazon.com/dp/1852339691)
     + Good book on how to build Virtual Machines especially tailored for the topic of building Programming Languages.

  * [Virtual Machines: Versatile Platforms for Systems and Processes](https://www.amazon.com/dp/1558609105)
     + Key textbook on the subject of Virtual Machines which examines virtual machine technologies across the disciplines that use them, e.g.: OS and Programming Languages.

  * [Write a Compiler in Go](https://compilerbook.com/)
     + Well-known introduction to the Go programming language and its ecosystem through building a Compiler project.

  * [Write an Interpreter in Go](https://interpreterbook.com/)
     + Successor of the "Write a Compiler in Go" book, but this one builds an interpreter project instead.

  * [Writing Compilers and Interpreters: A Software Engineering Approach](https://www.amazon.com/dp/0470177071)
     + How to build Compilers using Java, this book is tailored for the working Software Engineer.
      * Other editions: [Using C++](https://www.amazon.com/dp/0471113530), [Using C](https://www.amazon.com/dp/0471555800).
    
  * [Writing Interpreters and Compilers for the Raspberry Pi Using Python](https://www.amazon.de/gp/product/1977509207)
     + If you want to learn how to write interpreters and compilers, and at the same time learn how Python, Python bytecode, assembly language, and dynamic typing work, this is the book for you.

### Advanced

  * [高级编译器设计与实现](https://detail.tmall.com/item.htm?spm=a230r.1.14.20.6f4b456bH5Z05X&id=589508694688&ns=1&abbucket=11)
    + 即我们所说的“鲸书”，范围包括编译器后端的很多技术——别名分析、SSA、中间表示等等。
    + 原书：[Advanced Compiler Design and Implementation](https://www.amazon.com/dp/1558603204)
  * 链接器与加载器
    + 这本是链接和加载过程的权威作品。但很遗憾中译版已经绝版，原中译版为 北京航空航天大学出版社 出版的。
    + 原书：[Linkers and Loaders](https://www.amazon.com/dp/1558604960)
  * [垃圾回收算法手册](http://product.dangdang.com/1733827635.html)
    + 包括各种各样的垃圾回收算法的介绍、要处理的问题。还包括现代的并行垃圾回收。中译版并不是非常的好（个人观点），但是可以看。
    + 原书：[The Garbage Collection Handbook: The Art of Automatic Memory Management](https://www.amazon.com/dp/1420082795)
  * 类型和程序语言
    + 关于类型系统的经典书籍。很遗憾，中译版已经绝版，原出版社为 电子工业出版社。
    + 原书：[Types and Programming Languages](https://www.amazon.com/dp/0262162091)
  * [Advanced Design and Implementation of Virtual Machines](https://www.amazon.com/dp/146658260X)
    + Step-by-step hollistic introduction to the design of Virtual Machine architectures, topics and algorithms. Contains illustrated figures and implementations for the algorithms in the book.
  * [Advanced Topics in Types and Programming Languages](https://www.amazon.com/dp/0262162288)
    + Intensive study of Type Systems, covering topics such as, but not limited to: Precise Type Analyses; Type Systems for Low-Level Languages and Advanced Techniques in ML-style Type Inference..
  * [A Retargetable C Compiler: Design and Implementation](https://www.amazon.com/dp/0805316701)
    + Examines the design and implementation of Icc, a production-quality, retargetable compiler, designed at AT&T Bell Labs for the ANSI C programming language.
  * [Building an Optimizing Compiler](https://www.amazon.com/dp/155558179X)
    + Fills the gap in the domain of code optimization. This book provides a high level design for a thorough optimizer, code generator, scheduler and register allocator for a generic modern RISC processor.
  * [Compiling with Continuations](https://www.amazon.com/dp/052103311X)
    + Introduction to CPS (Continuation-Passing Style) as an Intermediate Representation in Compiler for doing optimizations and program transformations.
  * [Design Concepts in Programming Languages](https://www.amazon.com/dp/0262201755)
    + Systematic exploration of techniques and ideas used in Programming Language Design, covers topics such as: Operational and Denotational Semantic techniques, Dynamic Semantic techniques and Static Semantic techniques.
  * [Instruction Level Parallelism](https://www.amazon.com/dp/1489977953)
    + This book precisely formulates and simplifies the presentation of Instruction Level Parallelism (ILP) compilation techniques.
  * [Optimizing Compilers for Modern Architectures](https://www.amazon.com/dp/1558602860/)
    + Optimizing program generation based on recent gains and breakthroughs in modern high-performance CPU architectures.
  * [Parsing Techniques: A Practical Guide](https://www.amazon.com/dp/038720248X)
    + Definitive guide on parsing algorithms and techniques, also contains an introduction to Formal Grammar and Parsing Theory.
      * [1st Edition, PDF](https://dickgrune.com/Books/PTAPG_1st_Edition/).
  * [The Implementation of Functional Programming Languages](https://www.microsoft.com/en-us/research/wp-content/uploads/1987/01/slpj-book-1987-small.pdf)
    + Classic textbook on implementing Functional Languages, covers Structured Types, Pattern Matching Semantics, Lambda Calculus Transformation, Polymorphic Type Checking and many other topics.
  * [The SSA Book](http://ssabook.gforge.inria.fr/latest/book.pdf)
    + The only in-depth study of SSA-form (Static Single Assignment Form) in book format.
  * [Warren's Abstract Machine: Prolog in Haskell](https://mitpress.mit.edu/books/warrens-abstract-machine)
    + Introduction to WAM from Logic Programming in Prolog.

### Papers

  * [A Brief History of JIT Compilation, J. Aycock](http://eecs.ucf.edu/~dcm/Teaching/COT4810-Spring2011/Literature/JustInTimeCompilation.pdf).
  * [A Flexible Prolog Interpreter in Python, C. Bolz & M. Leuschel](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.103.1886&rep=rep1&type=pdf).
  * [A Graph Higher-Order IR, R. Leißa, M. Koster & S. Hack](http://compilers.cs.uni-saarland.de/papers/lkh15_cgo.pdf).
  * [A Micro-Manual for LISP - Not the Whole Truth, J. McCarthy](https://www.uraimo.com/files/MicroManual-LISP.pdf).
    + Other editions: [Neat and nice typeset](https://github.com/jaseemabid/micromanual).
  * [A Prolog Interpreter in Python, C. Bolz](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.121.8625&rep=rep1&type=pdf).
  * [A Simple Multi-Processor Computer Based on Subleq, O. Mazonka, A. Kolodin](https://arxiv.org/abs/1106.2593).
  * [An Evil Copy: How the Loader Betrays You](http://www.cse.psu.edu/~trj1/papers/ndss17.pdf)
    + About security issues related to Dynamic Loading.
  * [An Incremental Approach to Compiler Construction](http://scheme2006.cs.uchicago.edu/11-ghuloum.pdf).
  * [Compiler Construction Using Scheme, E. Hilsdale, J. Ashley, R. Dybvig & D. Friedman](https://www.cs.indiana.edu/~dyb/pubs/fple95.pdf).
  * [Compiling with Continuations: Continued, A. Kennedy](https://www.microsoft.com/en-us/research/wp-content/uploads/2007/10/compilingwithcontinuationscontinued.pdf).
  * [Definitional Interpreters for Higher-Order Programming Languages, J. Reynolds](http://www.cs.uml.edu/~giam/91.531/Textbooks/definterp.pdf).
  * [Draining the Swamp: Micro Virtual Machines as Solid Foundation for Languauage Development, K. Wang, Y. Lin, S. Blackburn, M. Norrish & A. Hosking](http://drops.dagstuhl.de/opus/volltexte/2015/5034/pdf/24.pdf).
  * [Engineering Definitional Interpreters, J. Midtgaard, N. Ramsey, B. Larsen](https://www.cs.tufts.edu/~nr/pubs/interps.pdf).
  * [Garbage Collection in an Uncooperative Environment, H. Boehm, M. Weiser](https://pdfs.semanticscholar.org/6434/aa10f3745dcf959cfca9c379aae120396724.pdf?_ga=2.133026126.1710272003.1495044697-300816831.1495044697).
  * [Machine Code Obfuscation via Instruction Set Reduction and CFG Linearization, C. Jonischkeit](https://kirschju.re/static/ba_jonischkeit_2016.pdf).
  * [`MOV` is Turing-Complete, S. Dolan](https://www.cl.cam.ac.uk/~sd601/papers/mov.pdf).
    + Discussions: [HN](https://news.ycombinator.com/item?id=6309631), [Reddit](https://redd.it/1nft0x).
  * [Nanopass Framework for Commercial Compiler Development, A. Keep & R. Dybvig](https://www.cs.indiana.edu/~dyb/pubs/commercial-nanopass.pdf).
  * [Nanopass Framework for Compiler Education, D. Sarkar, O. Waddell & R. Dybvig](https://www.cs.indiana.edu/~dyb/pubs/nano-jfp.pdf).
  * [Notes on Graph Algorithms Used in Optimizing Compilers, C. Offner](http://www.cs.umb.edu/%7Eoffner/files/flow_graph.pdf).
  * [Packrat Parsing Thesis on PEG, B. Ford](https://pdos.csail.mit.edu/~baford/packrat/thesis/).
  * [PEG-based transformer provides front-end, middle-end and back-end stages in a simple Compiler, I. Piumarta](http://www.vpri.org/pdf/tr2010003_PEG.pdf).
  * [Pycket: A Tracing JIT for a Functional Language](http://homes.soic.indiana.edu/samth/pycket-draft.pdf).
  * [PyPy’s Approach to VM Construction, A. Rigo & S. Pedroni](http://www.csc.lsu.edu/~gb/csc7700/Reading/pypy-vm-construction.pdf).
  * [RABBIT: A Compiler for SCHEME, G. Steele](http://repository.readscheme.org/ftp/papers/ai-lab-pubs/AITR-474.pdf).
  * [Simple and Efficient Construction of SSA Form](http://compilers.cs.uni-saarland.de/projects/ssaconstr/).
  * [SSA-based Register Allocation, S. Hack & G. Goos](http://compilers.cs.uni-saarland.de/projects/ssara/).
  * [The Essence of Compiling with Continuations, C. Flanagan, A. Sabry, B. Duba & M. Felleisen](https://users.soe.ucsc.edu/~cormac/papers/pldi93.pdf).
  * [The Page-Faults Weird Machine: Lessons in Instruction-less Computation, J. Bangert, S. Bratus, R. Shapiro, S. Smith](https://www.usenix.org/system/files/conference/woot13/woot13-bangert.pdf).
  * [Trace-based JIT Compilation for Lazy Functional Languages, T. Schilling](http://files.catwell.info/misc/mirror/tracing-jit-haskell-schilling.pdf).
  * [Using Datalog with Binary Decision Diagrams for Program Analysis, J. Whaley, D. Avots, M. Carbin & M. Lam](https://people.csail.mit.edu/mcarbin/papers/aplas05.pdf).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Ahmad Alhour](http://aalhour.com) has waived all copyright and related or neighboring rights to this work.

The logo was designed using [TextCraft](https://textcraft.net).
