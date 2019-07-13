literature
----------

- [RGB Image Analysis with Python](http://marksolters.com/programming/2015/02/27/rgb-histograph.html)
- [The incredibly challenging task of sorting colours](https://www.alanzucconi.com/2015/09/30/colour-sorting/)

installation into a seperated python3 virtualenv (linux)
--------------------------------------------------------

Clone repository and changing into its directory

```console
foo@bar:~$ git clone https://github.com/s3h10r/rainbow-vision/tree/lab
foo@bar:~$ cd rainbow-vision
```

Create a virtualenv (here named `venv_rv`)

```console
foo@bar:~$ python3 -m venv venv_rv
```

Change into the previously created venv `venv_rv` by activating it
and install the dependencies via pip into it afterwards:

```console
foo@bar:~$ source venv_rv/bin/activate
(venv_rv) foo@bar:~$ pip install -r requirements.txt
```

No errors? YAI then, ready now :)

```console
(venv_rv) foo@bar:~$ ./visualize_color.py  
(venv_rv) foo@bar:~$
```

PS: Don't forget to leave the venv when you're done.

```console
(venv_rv) foo@bar:~$ deactivate

foo@bar:~$
```
