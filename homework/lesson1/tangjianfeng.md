##1、用开户流程来类比JS运行环境框架
用银行的开户流程来类比Js运行环境框架，JS代码类似对银行有服务需求的客户，以v8引擎对应业务核心（即预处理和执行），用内置服务对应内置库，用第三方服务对应第三方库。同时了解到运行环境包含浏览器运行环境和Nodejs运行环境，这两种运行环境分别对应前端和后端，分别在浏览器上或Node上运行，他们主要的共同点在于JS内置对象，两者有通用的命令，但各自主要运用的内置库和第三方库大多不同，某些命令如alert在浏览器环境中能跳出警告窗口，而在Node上却是运行错误，因此学习Js要分清在哪个环境中用，才能有的放矢。

##2、主要学习的方向
主要学习的方向应该是熟悉代码的写作和了解内置库和第三方库，按照我上课的理解就是好好了解内置库和第三方库的作用，按照项目的实际来通过代码调用这些库中的资源，以达到用合适的库来做相应的事情，打个比方就是要解直角三角形三边长的问题最好用勾股定理，而不是用微积分。

##3、运行环境
运行环境类似于一个婴儿或者小学生的生存生活的环境，由供他生存的生活的各种具体的环境来对他做各种服务
运行环境主要有浏览器环境和Nodejs环境，前端开发一般用浏览器运行环境，后端开发一般在Nodejs环境中用
运行环境中有内置库和v8引擎。


##4、V8引擎
对代码预处理和执行


##5、内置库
是运行环境提供给我们的一组服务。
内置库中有网络库，日志库，js内置对象等库。浏览器中包含很多内置库，例如js内置对象，WebAPI,WebGL,HTTP，WebRTC，canvas等
Nodejs的的内置库中有JS内置对象，Node API。

##6、第三方库
第三方的库是由各种个人或公司编写出来方便我们实现更好更优质的服务的工具。
浏览器运行环境的第三方库主要有jQuery,Vue,AngularJS,React等.
NodeJS的第三方库主要有：Express,Koa,Webpack,Promise等

##7、编译器／解释（执行）器
编译器的几个主要作用：1、分析词法；2、分析语法；3、分析语义；4、优化代码。
解释（执行）器的主要功能是：1、解释代码；2、执行代码。

代码输入编译器，通过编译器分析词法、语法、语义及优化代码后，输出编译好的代码送入执行器，让执行器解释代码和执行代码，从而输出结果

JS是一种解释型语言，直接将代码输入编译器／解释器，它就能边进行分析词法、语法、语义，优化代码，解释代码，执行代码，不会有一个明显的编译过程，边编译边执行。
和编译型语言的区别是开发效率高，但运行效率低，因为它是边翻译边执行的。
