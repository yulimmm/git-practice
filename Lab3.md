# My Project Plan (Level 1 Heading)
_**Note:**_ Thie document is written merely as an illustrative example, and does not provide any working guide to an actual project. 
### Proposal (Level 3 Heading)
---
I am planning to make a computer vision software that detects objects in images.
In order to build it, I will use opencv, deep learning libraries, such as [TensorFlow](https://www.tensorflow.org/?hl=ko)
or [PyTorch](https://pytorch.org), and other open source softwares.

For example, the objects in the following images were detected using [mmdetection](https://github.com/open-mmlab/mmdetection):
![lab3_image](https://user-images.githubusercontent.com/12907710/137271636-56ba1cd2-b110-4812-8221-b4c120320aa9.png)

---

### Dependencies (Level 3 Heading)
- python
- opencv-python
- tensorflow
- openmmlab
- package manager

### Installation
In a bash terminal, run the following commands (_Do Not actually run these commands in your computer_):
```sh
$ sudo apt update
$ conda create -n cv_detection
$ conda activate cv_detection
$ python --version
$ python example.py
```
