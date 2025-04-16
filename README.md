# Description of VeinDeep data

VeinDeep is a system which uses an infrared (IR) depth sensor to extract vein patterns from a person’s hand. The idea is in the future smartphones will be equipped with Kinect V2 like IR depth sensors. Such sensors can be used to identify the smartphone owner using vein patterns and provide a way to unlock the phone. This project was created during my PhD. The associated research paper was presented at PerCom 2017.

This is the dataset for VeinDeep.

If you use this work please cite our paper.

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

The code, data and paper can be downloaded from the following page.

```
https://hzhongresearch.github.io/
```

### Licence
Copyright 2017 HENRY ZHONG. The data is released under Creative Commons Attribution 4.0 International Licence. See LICENCE.txt for details.

### Description of data
There were 20 participants. 12 males and 8 females. 17 were graduate students aged between 20 to 35 years. One individual aged 18, 2 aged between 50 - 60. The recordings were conducted in an office environment. There are a total of 240 recorded instances. 20 participants, 40 hands, 6 recording per hand.

Each file is 16 bits per pixel, named ```p<number>_<l|r>_<timestamp>_ir_raw.png``` or ```p<number>_<l|r>_<timestamp>_depth_raw.png```. ```ir_raw``` indicates an IR image. ```depth_raw``` indicates a depth image.

* ```<number>``` is the participant number.
* ```<l|r>``` indicates left or right hand.
* ```<timestamp>``` is a unix epoch timestamp.
