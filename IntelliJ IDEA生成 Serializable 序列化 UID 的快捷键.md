首先创建一个类如Movie，让该类实现Serializable序列化接口。

![img](IntelliJ IDEA生成 Serializable 序列化 UID 的快捷键.assets/20180805204717425)

然后我们需要依次按照以下的方法找到 Settings

![img](IntelliJ IDEA生成 Serializable 序列化 UID 的快捷键.assets/20180805204903648)

之后我们需要以下几个操作，并找到 Serializable class without 'serialVersionUID'

![img](IntelliJ IDEA生成 Serializable 序列化 UID 的快捷键.assets/20180805205014357)

之后我们要将光标放到实体类的名字Movie上，然后 alt+enter(回车) 找到如下内容，然后直接回车即可

![img](IntelliJ IDEA生成 Serializable 序列化 UID 的快捷键.assets/20180805205344505)

之后我们就可以看到自动生成的UID了

![img](IntelliJ IDEA生成 Serializable 序列化 UID 的快捷键.assets/20180805205438563)

-------------------------------------------------- 华丽的分割线 --------------------------------------------------