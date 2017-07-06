# Easy Installation of dlib python in Windows

Bored of trying to compile things manually in Windows? Bored of downloading 12GB of Visual Studio just to get a decent windows C compatible compiler? I know :/

I know how complicated/annoying it is to compile dlib, then compile Boost (with python bindings) and then compile it again to get the python api. I lost valuable hours trying to do that and at the end it didnt compile for python because it didnt recognize my Boost installation!!

**The easy way:** Just dowload from the [this page](https://pypi.python.org/pypi/dlib/18.17.100) the Python Wheel file and just `pip install` it ->
```
pip install dlib-file.whl
```

For python 2.7 and win32 just download this [file](https://pypi.python.org/packages/76/44/d5ea0c2cfbbce3c12841de8e29ba97e305c585b98c70f8e8f1cb69855f1f/dlib-18.17.100-cp27-none-win32.whl) and `pip install it`.
