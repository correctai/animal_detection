Animal Detection in Man-made Environments using Deep Learning
-------------------------------------------------------------

This repository provides python code for all experiments reported in this paper:

Animal Detection in Man-made Environments
[[arxiv]](https://arxiv.org/abs/1901.04412).

Labeling tool demo:

[![Labeling Tool Demo](images/vid_thumbnail.png)](https://youtu.be/ZkjcP8s0QVQ "Labeling Tool Demo")

It contains modified versions of several open source repositories that were used for experimentation though not all of these were reported in the paper.
These are the reported models and their corresponding folders:
1. YOLOv3: [[yolov3]](yolov3)
2. All other tested detectors and Mask RCNN: [[tf_api]](tf_api)
3. Evaluation tools: [[mAP]](mAP)
4. Labeling tool and scripts: [[labelling_tool]](labelling_tool)

The commands for running each model are provided in a .md file in the corresponding folder.
For example, commands for RetinaNet and YOLOv3 are in [tf_api/retinanet.md](tf_api/retinanet.md) and [yolov3/yolov3.md](yolov3/yolov3.md).
The commands are organized hierarchically into categories of experiments and a table of contents is included for easier navigation.

If a command does not work,  the command corresponding to some experiment cannot be found or the meaning of some command is not clear, please create an issue and we will do our best to address it.

All commands assume that the data is present under _/data/acamp/acamp20k_.

The code and data are released under [creative commons attribution license](https://creativecommons.org/licenses/by/4.0/) and are free for research and commercial applications. 
Also, individual repositories used here might have their own licenses that might be more restrictive so please refer to them as well.

If you find this work useful, please consider citing [this paper](https://arxiv.org/abs/1901.04412) [[bibtex](misc/bibtex.txt)].






