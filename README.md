Vanitas
=======
A Bitcoin vanity address generator that leverages the Java 8 streams API

Prerequisites:
-------------------------

* JDK 1.8 or higher
* Maven
* For additional dependency information refer to pom.xml

Build Instructions:
-------------------------

Building an executable jar:
> mvn package

The standalone executable jar can be found at: ./target/vanitas-1.0-SNAPSHOT-jar-with-dependencies.jar

Usage:
-------------------------

Running as an executable jar:

> java -jar target/vanitas-1.0-SNAPSHOT-jar-with-dependencies.jar 1Love

Log information will be output to ./logs/error.log

Example Output:
-------------------------

```
Searching for a bitcoin address that contains: 1Love  
Status is available at: ./logs/error.log  
Found in 1 min, 26 sec
Address: 1LoveJQWA5myfRJTKCzUcuahB9LGTaJHeY   
Private Key: 47310361300386867319958211412465237243746476090561242137932936363091835794229   
Private Key (HEX): 6898b72f443236a9ef6250750e83e57a159dd40769555d15a88cc3640358b335   
Private Key (WIF): Kzj2rvFzgjPVoYUhT7zBaVzvzEtUrDqT5esSnnum32nupTaNQzet   
```

Test Execution:
-------------------------

Execute all unit tests:
> mvn test

Limitations:
-------------------------

* It's slow. Ideally this type of work would be performed on a GPU.

License
-------------------------

The MIT License (MIT)

Copyright (c) 2015 com.gmail.lifeofreilly

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


