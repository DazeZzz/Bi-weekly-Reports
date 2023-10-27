# Fortnightly Report 01
I have been working on my distributed system homework for most of the past two weeks. For the homework, I learned some basics about `HTTP` and `RPC` protocol and how to actually implement them in my `C++` code. I found two libraries on **Github** called `cpp-httplib` and `gRPC`, and part of my time is spent on understanding how they work.

In the process, I discovered that `CMake` is just as important as `C++` itself, especially if you want to import some open source libraries. Almost all `C++` open source libraries support building their code with `CMake`, and for some of them `CMake` is even the only way. So it's almost impossible for you to understand how these libraries work if you don't understand `CMake`. Therefore, I spent some time to learn the syntax of it, and tried to understand how the `CMakeLists.txt` is written in those large and standard projects, and how these projects organize their directories. Further, I tried to imitate them to organize my own directory and write `CMakeLists.txt` for my own project, even though my project is so simple, and think what is the most reasonable way to write it. I analyzed the `CMakeLists.txt` of the project `CMU-15445`, and the two libraries mentioned above.

I have put my homework on **Github** at:\
<https://github.com/DazeZzz/SDCS>

In addition, I always hear some unfamiliar names just like `template metaprogramming` and `functional programming` in my daily search for `C++`. I have tried to find some materials about them but so far have not found much help. Maybe I have found a few examples of them, but very few actually mention their ideas, such as why they exist and what kind of problems they can sove. Maybe I should find some real masters' books about it when I have time.

Some useful pages:\
[modern CMake](https://modern-cmake-cn.github.io/Modern-CMake-zh_CN/)\
[some knowledge about linker](https://blog.csdn.net/github_37382319/article/details/82749912)\
[C++ keyword inline](https://www.zhihu.com/question/24185638/answer/2404153835?utm_psn=1700993900313952256)
