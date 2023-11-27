# Fortnightly Report 01

I have been working on my distributed system homework for most of the past two weeks. To finish the homework, I learned some basics about `HTTP` and `RPC` protocol and how to actually implement them in my `C++` code. I found two libraries on **Github** called `cpp-httplib` and `gRPC`, and part of my time is spent on understanding how they work.

In this process, I discovered that `CMake` is just as important as `C++` itself, especially if you want to import some open source libraries. Almost all `C++` open source libraries support building their code with `CMake`, and for some of them `CMake` is even the only way. So it's almost impossible for you to understand how these libraries work if you don't understand `CMake`. Therefore, I spent some time to learn the syntax of it, and tried to understand how the `CMakeLists.txt` is written in those large and standard projects, and how these projects organize their directories. Further, I tried to imitate them to organize my own directory and write `CMakeLists.txt` for my own project, even though my project is so simple, and think what is the most reasonable way to write it. I analyzed the `CMakeLists.txt` of the project `CMU-15445`, and the two libraries mentioned above.

I have put my homework on **Github** at:\
<https://github.com/DazeZzz/SDCS>

In addition, I always hear some unfamiliar names just like `template metaprogramming` and `functional programming` in my daily search for `C++`. I have tried to find some materials about them but so far have not found much help. Maybe I have found a few examples of them, but very few actually mention their ideas, such as why they exist and what kind of problems they can solve. My current image of them is probably just that the `template metaprogramming` is a way of programming that evolved during the development of `STL`, while the `functional programming` is something related to `Lambda Calculus`. Neither seems to have much value in `C++` engineering, so I didn't make much effort to understand them.

I also got the following things done during these two weeks:

* I  completed the `extensible hash table` part of the project of `CMU-15445`.
* I have read a small part of a book called `TCP/IP Internet Programming` for the distributed system homework.

Some helpful pages:\
[modern CMake](https://modern-cmake-cn.github.io/Modern-CMake-zh_CN/)\
[some knowledge about linker](https://blog.csdn.net/github_37382319/article/details/82749912)\
[C++ keyword inline](https://www.zhihu.com/question/24185638/answer/2404153835?utm_psn=1700993900313952256)\
[template metaprogramming](https://blog.csdn.net/fl2011sx/article/details/128077440)
