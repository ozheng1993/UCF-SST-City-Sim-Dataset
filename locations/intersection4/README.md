# UCF-SST-CitySim-Dataset


The UCF SST CitySim dataset contains vehicle trajectory data collected from drone videos captured at 30 frames per second. The dataset contains variuos location types including signalized intersections, non-signalized intersections, freeway basic segments, and freeway weaving segments. For each detected vehicle, the dataset includes frame number, unique car ID, bouding box X/Y, car center X/Y, bounding box latitude/longitude, car center latitude/longitude, speed, and heading.

## Trajectory Data

### University @ Alafaya (Signalized Intersection) (Sample Data [Google Drive Link](https://drive.google.com/drive/folders/1fHzmDxPHHofIBzQpx75Aol9pYCMX9gx7?usp=sharing) | [Baidu Yun Link](https://pan.baidu.com/s/1M6M7RlDwBUC-VoYVpcwpBQ?pwd=tfde))
:white_check_mark:  60 Mintues Trajectory

:white_check_mark:  60 Mintues Signal Timing

:white_check_mark:  Carla Base Map

:white_check_mark:  Sumo Base Map

The intersection of University Boulevard (9 lanes) and Alafaya Trail (9 lanes) is a large, signalized intersection at the entrance of the University of Central Florida in Orlando, Florida. Due to the large volume of serviced vehicles, the intersection contains numerous vehicle-to-vehicle traffic conflicts including merge conflicts and turning movement conflicts. Between 2011 – 2022, there was a total of 503 crashes in the intersection.

<img src="https://github.com/ozheng1993/UCF-SST-CitySim-Dataset/blob/main/asset/uni%40gemini030322E01stab-1_final.gif" width="1080">

### UCF Garage C (Consecutive Signalized Intersections) (Sample Data [Google Drive Link](https://drive.google.com/drive/folders/1m4eIq4dcbx5olBazagOXqvM6KBgXeCaT?usp=sharing) | [Baidu Yun Link]( https://pan.baidu.com/s/1M-MEC-DeHsBMW9OpltEwbQ?pwd=8eek))

:white_check_mark: 15 Mintues Trajectory

:white_check_mark: 15 Mintues Signal Timing

:white_check_mark: Carla Base Map

:white_check_mark: Sumo Base Map

This location contains two consecutive signalized intersections as well as their connecting road segment. The two intersections are positioned on both ends of a large student garage at the University of Central Florida in Orlando, Florida. Both intersections have permitted left-turn signal phases which lead to potential conflicts between southbound through traffic on the major road and left-turning vehicles heading for the garage. Furthermore, the connecting road segment contains the queue buildup for vehicles heading to the garage. Between 2011 – 2022, there was a total of 57 crashes in this location.

<img src="https://github.com/ozheng1993/UCF-SST-CitySim-Dataset/blob/main/asset/gargeC031622PM01-1_final.gif" width="1080">

### McCulloch @ Seminole (Non-Signalized Intersection) (Sample Data [Google Drive Link](https://drive.google.com/drive/folders/1DOPb_EqEwqPwFKlqL9XWoVZrJOqjsntE?usp=sharing) | [Baidu Yun Link]( https://pan.baidu.com/s/1rGTsQJwH-5LyT8I5GwtLCA?pwd=6ujc))

:white_check_mark: 60 Mintues Trajectory

:white_check_mark: Carla Base Map

:white_check_mark: Sumo Base Map

The intersection of McCulloch Road and Seminole Avenue is a non-signalized intersection with a mid-block near the University of Central Florida in Orlando, Florida. Due to the intersection’s non-signalized nature and reliance on driver visibility for movement decision making, the intersection contains numerous turning movement potential conflicts. Conflicts between westbound through traffic on the major road and left-turning vehicles from the minor road as well as left-turning vehicles from the major road are frequently observed, especially when students rush from Seminole Avenue to the major road during school time. Between 2011 – 2022, there was a total of 42 crashes in the intersection.

<img src="https://github.com/ozheng1993/UCF-SST-CitySim-Dataset/blob/main/asset/tivoli03302022A01sstabaliened-1_final.gif" width="1080">

### Freeway A (Weaving Segment) (Sample Data TBA)

:white_check_mark: 60 Mintues Trajectory

- [ ] Carla Base Map

- [ ] Sumo Base Map


<img src="https://github.com/ozheng1993/UCF-SST-CitySim-Dataset/blob/main/asset/tianfu031922AM02-5_final.gif" width="1080">

<hr> 

## Co-Simulation Base Map

### Carla Base Map（University @ Alafaya）

University @ Alafaya 3D base map. There are 91 buildings, 0.8 km2 area, and 15.53 m above sea level.

![carla](https://github.com/ozheng1993/UCF-SST-CitySim-Dataset/blob/main/asset/intersectionBasemap.png)


### Carla Base Map（UCF Garage C）

<img src="https://github.com/ozheng1993/UCF-SST-CitySim-Dataset/blob/main/asset/bandicam%202022-05-05%2021-35-41-187.gif" width="1080">

<hr> 

## Example Use Cases

### Co-Simulation Demo

The Unity simulator and SUMO simulation are connected through the TraCI portal provided by SUMO, and real-time co-simulation is achieved. In the co-simulation mode, the road network in SUMO and the map in Unity are matched, and all the vehicles and other traffic participants will be synchronized in both software. When conducting driving simulator experiments, the vehicle generated by SUMO act as background traffic which simulates the real- world traffic flow, and the vehicles spawned by Unity are operated by the drivers. Hence, the drivers are interacting with vehicles in the real-world traffic flow.

<img src="https://github.com/ozheng1993/UCF-SST-CitySim-Dataset/blob/main/asset/CoSim2.gif" width="1080">

### VR Co-Simulation

<img src="https://github.com/ozheng1993/UCF-SST-CitySim-Dataset/blob/main/asset/demo4.gif" width="1080">
<hr>


## Data Extraction Tool
[UCF-SST Automated Roadway Conflicts Identify System (A.R.C.I.S)](https://github.com/ozheng1993/A-R-C-I-S)


## Contributing

Contributions to this repository are welcome. Examples of things you can contribute:
-TBD

## Application for Access for Non-Commercial Use

To apply for access to the full dataset, please send us a request to this email: citysim.ucfsst@gmail.com 

Please tell us about yourself, your position, your current (research) project and what exactly you would like to use this dataset for. 

## Citation

If you use CitySim Dataset in your research , please use the following BibTeX entry.

      @article{,
        title={},
        author={},
        year={},
        publisher={}
      }