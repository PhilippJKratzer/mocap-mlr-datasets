# mocap-mlr-datasets
Here we will maintain a list of motion files captured at the Machine Learning and Robotics Lab of the University of Stuttgart. Check [the humoro project](https://github.com/PhilippJKratzer/humoro) for displaying the data files.


## upper-body data
Used in our paper:
Kratzer, Philipp, Marc Toussaint, and Jim Mainprice. "Towards Combining Motion Optimization and Data Driven Dynamical Models for Human Motion Prediction." 2018 IEEE-RAS 18th International Conference on Humanoid Robots (Humanoids). IEEE, 2018.

Download using:
```bash
./upper-body.sh
```

Playback all reaching motions with humoro:
```bash
cp -R ./upper-body [path_to_humoro]/datasets/
python [path_to_humoro]/examples/play_reaching.py
```
