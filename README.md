# lessonone15.02
Microsoft Windows [Version 10.0.19041.746]
(c) Корпорация Майкрософт (Microsoft Corporation), 2020. Все права защищены.

C:\Users\admin>g++ --version
g++ (GCC) 4.8.3
Copyright (C) 2013 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.


C:\Users\admin>cd ..

C:\Users>cd ..

C:\>cd lessons

C:\lessons>g++ newpro.cpp

C:\lessons>a
hello world!

C:\lessons>g++ -E newpro.cpp -o newpro.ii (Препроцессинг (page №1))

C:\lessons>a
hello world!

C:\lessons>newpro.ii

C:\lessons>g++ -S newpro.ii -o newpro.s (Компиляция (page №2))

C:\lessons>newpro.s

C:\lessons>newpro.s

C:\lessons>a
hello world!

C:\lessons>g++ newpro.cpp

C:\lessons>a
hello world!

C:\lessons>as newpro.s -o newpro.o (Ассемблирование (page №3))

C:\lessons>newpro.o

C:\lessons>newpro.o

C:\lessons>
(electron) Sending uncompressed crash reports is deprecated and will be removed in a future version of Electron. Set { compress: true } to opt-in to the new behavior. Crash reports will be uploaded gzipped, which most crash reporting servers support.
g++ newpro.o -o programm (Линковка (page №3))

C:\lessons>programm
Hello,GeekbrainsP§@ (не могу понять почему данные символы появились P§@)

C:\lessons>
