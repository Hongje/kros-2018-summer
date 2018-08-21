## 제 3회 인공지능 및 로보틱스 여름학교 (8/22,수)

### Codes
- [Lab-01: MLP](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-01-MLP)
- [Lab-02: SVM](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-02-SVM)
- [Lab-03: MLP-tf](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-03-MLP-tf)
- [Lab-04: CNN](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-04-CNN)
- [Lab-05: CNN-tf](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-05-CNN-tf.nn)
- [Lab-06: CNN-tf.layers](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-05-CNN-tf.nn)
- [Lab-07: CNN-tf-slim](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-07-CNN-slim)
- [Lab-08: Object Detection: YOLO](https://github.com/yonsei-cilab/yolo-tensorflow)

### Requirements
- tensorflow
- numpy
- matplotlib
- cvxopt
- scipy
- sklearn 
- opencv-python

### Packge download for Windows + python 3.6
[여기](https://drive.google.com/open?id=1k707gyg--Lb_0uTTmBp7_BsllWR8gofH) 에서 .whl 파일 5개 다운로드
win+R -> cmd 를 입력하여 명령 프롬프트 창을 연다.
$ pip install ".whl파일 복사한 경로"
ex) pip install "C:\1_numpy-1.15.0+mkl-cp36-cp36m-win_amd64.whl"
위 명령어를 사용하여 1번부터 5번까지 설치

$ pip install scipy
$ pip install sklearn
추가로 위의 2개의 pakage도 설치

### Packge download for Windows + python 3.XX
https://www.lfd.uci.edu/~gohlke/pythonlibs/#numpy
위 주소에서 자신에게 맞는 python 버전으로 numpy+mkl 설치
https://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv
위 주소에서 자신에게 맞는 python 버전으로 opencv 설치
$ pip install scipy
$ pip install sklearn
$ pip install cvxopt
$ pip install tensorflow

### Package download for Ubuntu 16.04
$ sudo apt-get install python3-pip python3-dev python-virtualenv python3-numpy python3-tk
$ sudo pip3 install matplotlib cvxopt scipy sklearn
$ sudo pip3 install opencv-python tensorflow

### Note
YOLO implementation are simple refactoring of [Peng Zhang's implementation](https://github.com/hizhangp/yolo_tensorflow) for lab.

