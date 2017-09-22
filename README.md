# LangyuyeMaven使用方法集合
## maven配置
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
### １、MaterialDialog
build.gradle配置
```java
dependencies {
    compile 'com.langyuye.library:dialog:1.0.0'
}
```
