# www.pycon.jp

:GitHub: https://github.com/pyconjp/www.pycon.jp
:URL: http://www.pycon.jp/
:URL(RTD): http://wwwpyconjp.readthedocs.org/

## how to build

```
$ virtualenv env
$ . env/bin/activate
(env)$ pip install -r requirements.txt
(env)$ make html
(env)$ open _build/html/index.html
```