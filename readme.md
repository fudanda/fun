# Introduction 简介 #
1. Use Golang implement the commonly used built-in PHP functions. 使用Golang实现PHP的内置函数。
2. Similar to php2go | php2golang | go2php | golang2php and other projects. 类似于 php2go | php2golang | go2php | golang2php 等项目
3. Welcome all friends who are familiar with or recognize PHP built-in functions to use and improve this project. 欢迎所有熟悉或者认可 php 内置函数的朋友们一起使用并完善本项目
4. It is not recommended for formal use in this project. 本项目仅供学习用，不建议在正式项目中使用。
5. This project is not updated. After go 2.0, it will appear as a new project. 本项目停止更新。等go 2.0 提供泛型之后以新项目形式出现。

## Wiki
All document entries for this project 本项目所有文档入口

https://github.com/yioio/fun/blob/master/docs/wiki.md

# Instructions 使用说明 

## Download and install & 下载安装 

    go get -u github.com/yioio/fun
    go get -u github.com/smartystreets/goconvey/convey 

## Example 示例 

    package main

    import (
        "github.com/yioio/fun/funArray"
        "log"
    )

    func main() {

        ret1 := funArray.In_array("cat", []interface{}{"cat", "dog"})
        ret2 := funArray.In_array_string("cat", []string{"cat", "dog"})
        log.Println(ret1)
        log.Println(ret2) 
    }

# Other 其它

## LICENSE 

Released under <a href="https://github.com/yioio/fun/blob/master/LICENSE">MIT</a> LICENSE
