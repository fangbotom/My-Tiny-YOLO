# Optimized Tiny YOLO for inland ship detection

Implementation of tiny-YOLOv2 with depthwise conv layer. The network was slightly changed for faster detection speed.

For network, see cfg/my-yolov2-tiny.cfg.

For data generating, see my_script. The dataset I used to train this network is 13000 inland ship images.

# How to run it

1. Git clone this repo.

2. Open Makefile and set GPU & CUDNN=1. Then make compile. (It needs CUDA & CUDNN dependencies to compile)
   
