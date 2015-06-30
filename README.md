#totoridipjp4J

##なにこれ

totori.dip.jp のトップ画像取得 API を呼び出すライブラリです。

http://totori.dip.jp/api_doc.txt

##使用例

```java
TotoriDipJPFactory factory = new TotoriDipJPFactory();
TotoriDipJP totori = factory.getInstance();

TopImg topImg = totori.getTopImg();
String url = topImg.getUrl();

System.out.println(url);
```

## Gradleから参照する

```groovy
repositories {
    maven {
        url 'http://shibafu528.github.io/totoridipjp4J/build/repo'
    }
}

dependencies {
    compile 'jp.dip.totori:totoridipjp4J:1.0'
}
```
