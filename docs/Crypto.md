# Crypto osztály használata

```java
String key = "343834839224af82";

Crypto c = new Crypto();
String cryptText = c.encrypt("titok", key);
System.out.println(cryptText);
String plainText = c.decrypt(cryptText, key);
System.out.println(plainText);
```
