# LangyuyeMaven使用方法集合
maven　url配置
```java
allprojects {
    repositories {
        jcenter()
        maven{
            url "https://raw.githubusercontent.com/Langyuye/MavenRepository/master"
        }
    }
}
```
### MaterialDialog使用方法
build.gradle配置
```java
dependencies {
    compile 'com.langyuye.library:dialog:1.0.0'
}
```
