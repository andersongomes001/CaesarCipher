# Caesar Cipher
### Installation
```sh
$ pip install rotcaesarcipher
```

### How to use
```sh
$ python
Python 2.7.15 (default, May  1 2018, 05:55:50) 
[GCC 7.3.0] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>> import RotCaesarCipher
>>> print RotCaesarCipher.encode(13,"Caesar Cipher")
PNRFNE PVCURE
>>> print RotCaesarCipher.decode(13,"PNRFNE PVCURE")
caesar cipher
>>> 

```
```sh
$ python3
Python 3.6.5 (default, May 11 2018, 13:30:17) 
[GCC 7.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import RotCaesarCipher
>>> print(RotCaesarCipher.encode(13,"Caesar Cipher"))
PNRFNE PVCURE
>>> print(RotCaesarCipher.decode(13,"PNRFNE PVCURE"))
caesar cipher
>>> 
```
test.py
```sh
import RotCaesarCipher
print(RotCaesarCipher.encode(13,"Caesar Cipher"))#PNRFNE PVCURE
print(RotCaesarCipher.decode(13, "PNRFNE PVCURE"))#caesar cipher

```

License
----

GNU GPL v3



[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
