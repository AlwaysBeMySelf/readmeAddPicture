# README.md添加图片
github 图片链接格式：

(http://github.com/yourname/your-repository/raw/master/images-folder/xxx.png)

要自己设定的：yourname, your-repository, your-folder, xxx.png。

    yourname            --- 你的帐号
    your-respository --- 你的 project 名
    images-folder      --- 你存放图片的文件夹，如果是直接放在 project 的项目根目录的話，就可以省略這個
    xxx.png                --- 你的图片名


举例：

(https://github.com/AlwaysBeMySelf/MultiApi/raw/master/picture/result_3.png)
左括号前添加![image]就是如下效果

![image](https://github.com/AlwaysBeMySelf/MultiApi/raw/master/picture/result_3.png)


# README.mdjava代码高亮

以 ```java 开始
  
//这里放你的代码
  
以 ``` 结束

原始效果如下

![image](https://github.com/AlwaysBeMySelf/MultiApi/raw/master/picture/code.png)

举例：

原始：
productFlavors {
    myrelease {
        applicationId 'com.nht.multiapi'
        versionName '1.0-release'
    }
}

高亮：
```java 
productFlavors {
    myrelease {
        applicationId 'com.nht.multiapi'
        versionName '1.0-release'
    }
}
```
