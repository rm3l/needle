Needle
=======

Multithreading library for Android.

```java
Needle.onMainThread().execute(new Runnable() {
    @Override
    public void run() {
        // e.g. change one of the views
    }
});
```
For documentation and additional information see [the website][1].


Download
--------

Download [the latest JAR][2] or grab via Gradle:
```groovy
compile 'com.zsoltsafrany:needle:1.0.0'
```
or Maven:
```xml
<dependency>
    <groupId>com.zsoltsafrany</groupId>
    <artifactId>needle</artifactId>
    <version>1.0.0</version>
</dependency>
```


License
--------

    The MIT License (MIT)

    Copyright (c) 2014 Zsolt Safrany

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.


 [1]: https://zsoltsafrany.github.io/needle
 [2]: http://repository.sonatype.org/service/local/artifact/maven/redirect?r=central-proxy&g=com.zsoltsafrany&a=needle&v=LATEST
