---
title: Maven Nedir ?
date: '2022-07-28'
tags: ['maven', 'java','dependency']
draft: false
summary: 'Maven'nın ne olduğundan bahsedilmiştir.'
---

# Maven Nedir ?
Maven proje yönetim aracıdır. Proje oluşturma, bağımlılık(dependency) ve dokümantasyon için kullanılır. Maven dosyasına eklenen bağımlılıklar ile kolay bir şekilde indirmeyi ve proje yerleştirmeyi sağlar. Bağımlılıklar pom.xml dosyasına eklenir.

## Bağımlılık Ekleme
https://www.mvnrepository.com dan kütüphaneleri bulabilirsiniz. Öncelikli olarak hangi kütüphaneyi istediğiniz yazarsınız. Tıkladıktan sonra sürümünü seçmeniz gerekiyor. En son olarak Maven kısmından bağımlılığı göreceksiniz. Onu projenizdeki     pom.xml'e ekleyebilirisiniz.

## Örnek Bağımlılık
H2 Database için bağımlılık :
```
    <dependency>
        <groupId>com.h2database</groupId>
        <artifactId>h2</artifactId>
        <scope>runtime</scope>
    </dependency>
```

### Kaynakça:
- https://medium.com/yazilim-vip/bu-yaz%C4%B1n%C4%B1n-amac%C4%B1-maven-ile-siz-okurlar%C4%B1-tan%C4%B1%C5%9Ft%C4%B1rmakt%C4%B1r-aab0f6ff91f4

- https://www.yusufsezer.com.tr/maven/


