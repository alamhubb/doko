# doko
Overwrite your source code anywhere

doko, named after the Doraemon Anywhere Door.

It means that you can freely travel to any position in the program.

The idea comes from spring ioc, aop, js proxy, but it is different from these. The principle of doko is like reverse proxy.

It is the first time to apply reverse proxy in the business field. This is an innovative technology.

Let's take a look at its magic.

We can arbitrarily expand the existing program without modifying the source code of the existing program. This sounds a bit confusing. Let's take a look at the specifics.

hello={hello}
newhello={newhello}

doko(hello，newhello)

hello.hello//newhello
