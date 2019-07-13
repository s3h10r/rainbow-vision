literature
----------

- [RGB Image Analysis with Python](http://marksolters.com/programming/2015/02/27/rgb-histograph.html)
- [The incredibly challenging task of sorting colours](https://www.alanzucconi.com/2015/09/30/colour-sorting/)

installation
------------

installing the software into a seperated virtual-environment under linux can
be done like:

```console

foo@bar:~$ git clone https://github.com/s3h10r/rainbow-vision/tree/feature
foo@bar:~$ cd rainbow-vision
foo@bar:~$ python3 -m venv venv_rv # --- create a venv
foo@bar:~$ source venv_rv/bin/activate # --- activate venv
(venv_rv) foo@bar:~$ pip install -r requirements.txt # --- install dependencies into it

# --- yai, ready now...

(venv_rv) foo@bar:~$ ./visualize_color.py  
(venv_rv) foo@bar:~$

# --- don't forget to leave the venv when you're done
(venv_rv) foo@bar:~$ deactivate
foo@bar:~$
```
