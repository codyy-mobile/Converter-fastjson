# Converter-fastjson[![](https://jitpack.io/v/CodyyAndroid/Converter-fastjson.svg)](https://jitpack.io/#CodyyAndroid/Converter-fastjson)
```
allprojects {
  repositories {
    ...
    maven { url 'https://jitpack.io' }
  }
}
```
```
dependencies {
        compile 'com.github.CodyyAndroid:Converter-fastjson:v0.0.1'
}
```
```
Retrofit...
.addConverterFactory(FastJsonConverterFactory.create())//设置FastJson转换工厂
```
