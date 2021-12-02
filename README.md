# Autonomy-of-L4-Trucking
This is the summary on public resources, such as industry solutions, academic papers and youtube talks. I collected them during my work and hope the sharing can help you:-)

## 1. Main Player
- Aurora, [intro](https://www.youtube.com/watch?v=EOhR_RIKmEI)
- TuSimple, [intro](https://www.youtube.com/watch?v=zM7oGhEq2Jo)
- Torc.ai, [homepage](https://torc.ai)
- Embark, [homepage](https://embarktrucks.com)
- Waymo, [intro](https://www.youtube.com/watch?v=oJ96bgmSaW0)

Other L4 related, such as RoboTaxi:
- Cruise,  [intro](https://www.youtube.com/watch?v=uJWN0K26NxQ)

## 2. Main Researcher institution
- Prof. Raquel Urtasun, http://www.cs.toronto.edu/~urtasun/
- Bin Yang, Waabi, http://www.cs.toronto.edu/~byang/

## 3. System Architeture (training -> validation -> deploy)
- Motional, https://motional.com/news/technically-speaking-learning-with-every-mile-driven

## 4. Algorithm of Autonomy
#### Perception
- FIERY: Future Instance Prediction in Bird's-Eye View from Surround Monocular Cameras, 2021 [link](https://arxiv.org/abs/2104.10490)
- RadarNet: Exploiting Radar for Robust Perception of Dynamic Objects, [link](https://arxiv.org/pdf/2007.14366.pdf)
- Fast and furious: Real time end-to-end 3d detection, tracking and motion forecasting with a single convolutional net, 2018 [link](https://openaccess.thecvf.com/content_cvpr_2018/papers/Luo_Fast_and_Furious_CVPR_2018_paper.pdf)

#### Fusion
- Cross-Modal 3D Object Detection and Tracking for Auto-Driving, 2021 [link](https://vision.sjtu.edu.cn/files/iros2021_alphatrack.pdf)

#### DL Tracker
- End-to-End Perception and Prediction with Tracking in the Loop, 2020 [link](https://arxiv.org/pdf/2005.14711.pdf)
- How To Train Your Deep Multi-Object Tracker, 2020 [link](https://arxiv.org/abs/1906.06618)
- Learning a Neural Solver for Multiple Object Tracking, 2020 [link](https://arxiv.org/abs/1912.07515)
- Spatial-Temporal Relation Networks for Multi-Object Tracking, 2019 [link](https://arxiv.org/pdf/1904.11489.pdf)
- FANTrack: 3D Multi-Object Tracking with Feature Association Network, 2019 [link](https://arxiv.org/abs/1905.02843)

#### Prediction
- MultiPath++, Waymo, [link](https://arxiv.org/abs/1910.05449)
- Data Driven Prediction Architecture for Autonomous Driving and its Application on Apollo Platform, Baidu Apollo, [link](https://arxiv.org/abs/2006.06715)
- Overview : https://kargarisaac.medium.com/behavior-prediction-and-decision-making-in-self-driving-cars-using-deep-learning-784761ed34af

#### Motion Planning
- Overview (zhihu), https://zhuanlan.zhihu.com/p/59089908

#### Vision Lidar (Vidar)
- MobileEye, Stereo Camera, [link](https://s21.q4cdn.com/600692695/files/doc_presentations/2020/1/Mobileye-CES-2020-presentation.pdf)
- Waymo, Multiple Monocular Camera, [link](https://youtu.be/rbDuK5e1bWw?t=555)
- Tesla, Multiple Monocular Cameras, [link](https://www.youtube.com/watch?v=NSDTZQdo6H8)

#### Offline Perception/Auto-labeling
- Offboard 3D Object Detection from Point Cloud Sequences, 2021 [link](https://arxiv.org/abs/2103.05073)
- Auto4D: Learning to Label 4D Objects from Sequential Point Clouds, 2021 [link](https://arxiv.org/pdf/2101.06586.pdf)

## 5. Simulation
#### Carla, https://github.com/carla-simulator/carla
#### LGSVL, https://github.com/lgsvl/simulator
#### Simulation City, Waymo, https://blog.waymo.com/2021/06/SimulationCity.html
#### Research paper
- SurfelGAN, [link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_SurfelGAN_Synthesizing_Realistic_Sensor_Data_for_Autonomous_Driving_CVPR_2020_paper.pdf)
- GeoSim, [link](https://openaccess.thecvf.com/content/CVPR2021/papers/Chen_GeoSim_Realistic_Video_Simulation_via_Geometry-Aware_Composition_for_Self-Driving_CVPR_2021_paper.pdf)
- Towards Optimal Strategies for Training Self-Driving Perception Models in Simulation, [link](https://arxiv.org/pdf/2111.07971.pdf)

## 6. OpenSource code/dataset
#### Code implementation
- Camera based dense object tracking : https://github.com/SysCV/qd-3dt

#### Dataset
- https://www.siasearch.io/blog/best-open-source-autonomous-driving-datasets

## 7. Main Challenge
