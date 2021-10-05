<h1 align="center"> PyCalc</h1>

A simple calculator follow along. Bugs were left intentionally which I fixed. <br>
Originally made with Qt5, but I tinkered with some code to make Qt6 work.<br><br>

`app.setStyle(qtw.QStyleFactory.create('Fusion'))` on line 90 may not be cross platform.<br>
Use `qtw.QStyleFactory.keys()` in the python terminal to list what styles are available on your system.<br>
If `Fusion` is not listed then you will need to pick another style in the list to replace it with


**Written by**: Drew<br>
**Written in** Python 3.9.7<br>
**Libraries used**: PyQt6<br>