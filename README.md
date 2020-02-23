# making pdf-to-text module

credit to article [dev.to article](https://dev.to/mustafaanaskh99/convert-any-pdf-file-into-an-audio-book-with-python-1gk4)

also, at time of writting (Sun 23 Feb 23:07:19 GMT 2020), issues were found with `pdftotext` module and `pip`

_pdftotext_

`pythontotext` needs dependencies on your machine, after making sure you have
the latest python and pip, follow the article [attached](https://pypi.org/project/pdftotext/)

or just type out the following 

```bash
sudo apt-get install build-essential libpoppler-cpp-dev pkg-config python-dev
```

> line is for ubuntu

_pip_
on **linux - ubuntu** you need to made sure you have the latest version of
python and pip installed (duh)
[pip](https://linuxize.com/post/how-to-install-pip-on-ubuntu-18.04/#installing-pip-for-python-3)

```bash
sudo apt-get install python3
```

i also found that my machine defaulted to later versions of pip and python, if
you're not using them it makes sense to remoev them but echoing the following
into your `bash.rc` file will achieve the same thing

```bash
echo alias ptyhon=<latest python version: i.e. python3> >> ~/.bashrc
echo alias pip=<latest python verion: i.e pip3>
source ~/.bashrc
```


