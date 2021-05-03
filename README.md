# NewRepo
What a repo?  
Error with Jetson Nano Ai-Thermometer

root@nanotermo-desktop:/home/nano-termo/ai-thermometer# python3 main.py
Traceback (most recent call last):
  File "main.py", line 13, in <module>
    from rgb import RGBThread
  File "/home/nano-termo/ai-thermometer/rgb/__init__.py", line 1, in <module>
    from .rgb_thread import *
  File "/home/nano-termo/ai-thermometer/rgb/rgb_thread.py", line 7, in <module>
    from .camera import make_imx219_capture
ImportError: cannot import name 'make_imx219_capture'
