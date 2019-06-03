## BlinkBird

A very simple addon to [FlapPyBird](https://github.com/sourabhv/FlapPyBird) that adds eye blinking to controller the bird.

### Installation

Follow [How-To](https://github.com/sourabhv/FlapPyBird#how-to-as-tested-on-macos) from @sourabhv, and this addtional steps:

```shell
$ git clone https://github.com/Lucisu/BlinkBird.git
$ cd BlinkBird
$ pip3 install -r requirements.txt
```

### Method

Uses OpenCV and [shape_predictor_68_face_landmarks.dat](https://github.com/AKSHAYUBHAT/TensorFace/tree/master/openface/models/dlib) to find eyes and their points.

###### Thanks to [PySource](https://pysource.com/2019/01/10/eye-blinking-detection-gaze-controlled-keyboard-with-python-and-opencv-p-2/) and blink detection logic.
