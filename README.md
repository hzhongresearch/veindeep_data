# Description of VeinDeep data

This data was used to test the VeinDeep system. A system designed to compute a score of similarity between 2 vein patterns. The data was recorded using a Kinect V2. The data is an infrared (IR) and depth image of the back of a participant's hand. The hand is made into a fist to expose vein patterns.

VeinDeep was created during my PhD. The research paper "VeinDeep: Smartphone unlock using vein patterns" was presented at PerCom 2017. My research is in Ubiquitous Computing and Computer Vision. If you use this work please consider citing our paper.

```
@inproceedings{zhong2017veindeep,
  title={VeinDeep: Smartphone unlock using vein patterns},
  author={Zhong, Henry and Kanhere, Salil S and Chou, Chun Tung},
  booktitle={Pervasive Computing and Communications (PerCom), 2017 IEEE International Conference on},
  pages={2--10},
  year={2017},
  organization={IEEE}
}
```

The code, data and paper can be downloaded at the following link.

```
https://hzhongresearch.github.io/
```

### Licence
Copyright 2017 HENRY ZHONG. The data is released under Creative Commons Attribution 3.0 Unported Licence. See LICENCE.txt for details.

### Description of data
There were 20 participants. 12 males and 8 females. 17 were graduate students aged between 20 to 35 years. One individual aged 18, 2 aged between 50 - 60. The recordings were conducted in an office environment. There are a total of 240 recorded instances. 20 participants, 40 hands, 6 recording per hand.

Each file is 16 bits per pixel, named ```p<number>_<l|r>_<timestamp>_ir_raw.png``` or ```p<number>_<l|r>_<timestamp>_depth_raw.png```. ```ir_raw``` indicates an IR image. ```depth_raw``` indicates a depth image.

* ```<number>``` is the participant number.
* ```<l|r>``` indicates left or right hand.
* ```<timestamp>``` is a unix epoch timestamp.
