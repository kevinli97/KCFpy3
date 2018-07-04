# KCF tracker in Python3

Python3 implementation of
> [High-Speed Tracking with Kernelized Correlation Filters](http://www.robots.ox.ac.uk/~joao/publications/henriques_tpami2015.pdf)<br>
> J. F. Henriques, R. Caseiro, P. Martins, J. Batista<br>
> TPAMI 2015

It is modified from [KCFpy](https://github.com/uoip/KCFpy) 

### Use
Download the sources and execute
```shell
git clone https://github.com/kevinli97/KCFpy3.git
cd KCFpy3
python3 run.py
```
It will open the default camera of your computer, you can also open a different camera or a video
```shell
python3 run.py 2
```
```shell
python3 run.py ./test.avi  
```
Try different options (hog/gray, fixed/flexible window, singlescale/multiscale) of KCF tracker by modifying the arguments in line `tracker = kcftracker.KCFTracker(False, True, False)  # hog, fixed_window, multiscale` in run.py.


### Problem
See [KCFpy](https://github.com/uoip/KCFpy)
