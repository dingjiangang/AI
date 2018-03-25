# AI
人工智能学习之路  
2014年进入长城汽车技术中心从事CAE工作  
2016年进入上汽商用车技术中心从事CAE工作  
2015年开始因工作原因开始学习Tcl/Tk和Python语言，主要用于CAE应用软件的二次开发工作，CAE软件有HyperMesh和Ansa  
2016年开始接触人工智能，2017年决定转行进入无人驾驶人工智能领域  
http://www.imorpheus.ai/journalClub    Journal club介绍与自动驾驶中定位方案相关的论文。 主要关注的方向有：SLAM算法、点云数据的处理和压缩、 特征地图、传感器数据处理和融合、 GNSS信号处理等。我们一直关注领域前沿技术， 选取得到广泛认可的、或者是在我们的实际使用中结果比较好的论文， 与大家分享，共同学习成长。   
##################在这里我会记录学习的方式及学习资源################################  
1.udacity学习git&github网址  https://cn.udacity.com/course/how-to-use-git-and-github--ud775  
2.相关的udacity的一些项目已上传到github  
3.如何安装ros系统，请参照网站https://www.cnblogs.com/liu-fa/p/5779206.html   
4.数据结构学习课程，清华大学邓俊辉：http://www.xuetangx.com/courses/course-v1:TsinghuaX+30240184+sp/about    
5.无人驾驶模拟环境Autoware安装方法：https://github.com/CPFL/Autoware/wiki/Generic-x86-Docker   
6.Eigen学习知识：http://eigen.tuxfamily.org/dox-devel/modules.html  关于几何模块请参考：http://eigen.tuxfamily.org/dox/group__TutorialGeometry.html   
7.学习无人驾驶应知应会#######################################################################  
1）课程  2）论文  3）实验室  4）数据集  5）开源项目  
一：课程  
    [Udacity] Self-Driving Car Nanodegree Program - teaches the skills and techniques used by self-driving car teams. Program syllabus can be found here.  
    [University of Toronto] CSC2541 Visual Perception for Autonomous Driving - A graduate course in visual perception for autonomous driving. The class briefly covers topics in localization, ego-motion estimaton, free-space estimation, visual recognition (classification, detection, segmentation).  
    [INRIA] Mobile Robots and Autonomous Vehicles - Introduces the key concepts required to program mobile robots and autonomous vehicles. The course presents both formal and algorithmic tools, and for its last week's topics (behavior modeling and learning), it will also provide realistic examples and programming exercises in Python.  
    [Universty of Glasgow] ENG5017 Autonomous Vehicle Guidance Systems - Introduces the concepts behind autonomous vehicle guidance and coordination and enables students to design and implement guidance strategies for vehicles incorporating planning, optimising and reacting elements.  
    [David Silver - Udacity] How to Land An Autonomous Vehicle Job: CourseworkDavid Silver, from Udacity, reviews his coursework for landing a job in self-driving cars coming from a Software Engineering background.  
    [Stanford] CS221 Artificial Intelligence: Principles and Techniques - Contains a simple self-driving project and simulator.  
    [MIT] 6.S094: Deep Learning for Self-Driving Cars - an introduction to the practice of deep learning through the applied theme of building a self-driving car.  
    [MIT] 2.166 Duckietown - Class about the science of autonomy at the graduate level. This is a hands-on, project-focused course focusing on self-driving vehicles and high-level autonomy. The problem: Design the Autonomous Robo-Taxis System for the City of Duckietown.  
二：论文  
综合  
    [2016] Combining Deep Reinforcement Learning and Safety Based Control for Autonomous Driving. [ref]  
    [2015] An Empirical Evaluation of Deep Learning on Highway Driving. [ref]  
    [2015] Self-Driving Vehicles: The Challenges and Opportunities Ahead. [ref]  
    [2014] Making Bertha Drive - An Autonomous Journey on a Historic Route. [ref]  
    [2014] Towards Autonomous Vehicles. [ref]  
    [2013] Towards a viable autonomous driving research platform. [ref]  
    [2013] An ontology-based model to determine the automation level of an automated vehicle for co-driving. [ref]  
    [2013] Autonomous Vehicle Navigation by Building 3d Map and by Detecting Human Trajectory Using Lidar. [ref]  
    [2012] Autonomous Ground Vehicles - Concepts and a Path to the Future. [ref]  
    [2011] Experimental Evaluation of Autonomous Driving Based on Visual Memory and Image-Based Visual Servoing. [ref]  
    [2011] Learning to Drive: Perception for Autonomous Cars. [ref]  
    [2010] Toward robotic cars. [ref]  
    [2009] Autonomous Driving in Traffic: Boss and the Urban Challenge. [ref]  
    [2009] Mapping, navigation, and learning for off-road traversal. [ref]  
    [2008] Autonomous Driving in Urban Environments: Boss and the Urban Challenge. [ref]  
    [2008] Caroline: An autonomously driving vehicle for urban environments. [ref]  
    [2008] Design of an Urban Driverless Ground Vehicle. [ref]  
    [2008] Little Ben: The Ben Franklin Racing Team's Entry in the 2007 DARPA Urban Challenge. [ref]  
    [2008] Odin: Team VictorTango's Entry in the DARPA Urban Challenge. [ref]  
    [2008] Robosemantics: How Stanley the Volkswagen Represents the World. [ref]  
    [2008] Team AnnieWAY's autonomous system for the 2007 DARPA Urban Challenge. [ref]  
    [2008] The MIT-Cornell collision and why it happened. [ref]  
    [2007] Self-Driving Cars - An AI-Robotics Challenge. [ref]  
    [2007] 2007 DARPA Urban Challenge: The Ben Franklin Racing Team Team B156 Technical Paper. [ref]  
    [2007] Team Mit Urban Challenge Technical Report. [ref]  
    [2007] DARPA Urban Challenge Technical Report Austin Robot Technology [ref]  
    [2007] Spirit of Berlin: an Autonomous Car for the Darpa Urban Challenge Hardware and Software Architecture. [ref]  
    [2007] Team Case and the 2007 Darpa Urban Challenge. [ref]  
    [2006] A Personal Account of the Development of Stanley, the Robot That Won the DARPA Grand Challenge. [ref]  
    [2006] Stanley: The robot that won the DARPA Grand Challenge. [ref]   
激光雷达与点云  
    [2017] PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation. [ref][github]  
    [2017] VoxelNet: End-to-End Learning for Point Cloud Based 3D Object Detection  
    [2017] [1611.08069] 3D Fully Convolutional Network for Vehicle Detection in Point Cloud  
    [2017] [1703.03613] Fast LIDAR-based Road Detection Using Fully Convolutional Neural Networks  
    [2016] Motion-based Detection and Tracking in 3D LiDAR Scans [ref][youtube]  
    [2016] Lidar-based Methods for Tracking and Identification [ref][youtube]  
    [2015] Efficient L-shape fitting of laser scanner data for vehicle pose estimation [ref]  
    [2014] Road Detection Using High Resolution LIDAR  
    [2012] LIDAR-based 3D Object Perception [ref]  
    [2011] Radar/Lidar sensor fusion for car-following on highways [ref]  
    [2009] Real-time road detection in 3d point clouds using four directions scan line gradient criterion  
    [2006] Real-time Pedestrian Detection Using LIDAR and Convolutional Neural Networks [ref]  
定位与测绘  
    [2016] MultiCol-SLAM - A Modular Real-Time Multi-Camera SLAM System. [ref]  
    [2016] Image Based Camera Localization: an Overview. [ref]  
    [2016] Ubiquitous real-time geo-spatial localization [ref]  
    [2016] Robust multimodal sequence-based loop closure detection via structured sparsity. [ref]  
    [2016] SRAL: Shared Representative Appearance Learning for Long-Term Visual Place Recognition. [ref], [code]  
    [2015] Precise Localization of an Autonomous Car Based on Probabilistic Noise Models of Road Surface Marker Features Using Multiple Cameras. [ref]  
    [2013] Planar Segments Based Three-dimensional Robotic Mapping in Outdoor Environments. [ref]  
    [2013] Vehicle Localization along a Previously Driven Route Using Image Database. [ref]  
    [2012] Can priors be trusted? Learning to anticipate roadworks. [ref]  
    [2009] Laser Scanner Based Slam in Real Road and Traffic Environment. [ref]  
    [2007] Map-Based Precision Vehicle Localization in Urban Environments. [ref]  
感知  
    [2016] VisualBackProp: visualizing CNNs for autonomous driving. [ref]  
    [2016] Driving in the Matrix: Can Virtual Worlds Replace Human-Generated Annotations for Real World Tasks?. [ref]  
    [2016] Lost and Found: Detecting Small Road Hazards for Self-Driving Vehicles. [ref]  
    [2016] Image segmentation of cross-country scenes captured in IR spectrum. [ref]  
    [2016] Traffic-Sign Detection and Classification in the Wild. [ref]  
    [2016] Persistent self-supervised learning principle: from stereo to monocular vision for obstacle avoidance. [ref]  
    [2016] Deep Multispectral Semantic Scene Understanding of Forested Environments Using Multimodal Fusion. [ref]  
    [2016] Joint Attention in Autonomous Driving (JAAD). [ref, data]  
    [2016] Perception for driverless vehicles: design and implementation. [ref]  
    [2016] Robust multimodal sequence-based loop closure detection via structured sparsity. [ref]  
    [2016] SRAL: Shared Representative Appearance Learning for Long-Term Visual Place Recognition. [ref], [code]  
    [2015] Pixel-wise Segmentation of Street with Neural Networks. [ref]  
    [2015] Deep convolutional neural networks for pedestrian detection. [ref]  
    [2015] Fast Algorithms for Convolutional Neural Networks. [ref]  
    [2015] Fusion of color images and LiDAR data for lane classification. [ref]  
    [2015] Environment Perception for Autonomous Vehicles in Challenging Conditions Using Stereo Vision. [ref]  
    [2015] Intention-aware online POMDP planning for autonomous driving in a crowd. [ref]  
    [2015] Survey on Vanishing Point Detection Method for General Road Region Identification. [ref]  
    [2015] Visual road following using intrinsic images. [ref]    
    [2014] Rover – a Lego* Self-driving Car. [ref]  
    [2014] Classification and Tracking of Dynamic Objects with Multiple Sensors for Autonomous Driving in Urban Environments. [ref]  
    [2014] Generating Omni-directional View of Neighboring Objects for Ensuring Safe Urban Driving. [ref]  
    [2014] Autonomous Visual Navigation and Laser-Based Moving Obstacle Avoidance. [ref]  
    [2014] Extending the Stixel World with online self-supervised color modeling for road-versus-obstacle segmentation. [ref]  
    [2014] Modeling Human Plan Recognition Using Bayesian Theory of Mind. [ref]  
    [2013] Focused Trajectory Planning for autonomous on-road driving. [ref]  
    [2013] Avoiding moving obstacles during visual navigation. [ref]  
    [2013] Mobile robot navigation system in outdoor pedestrian environment using vision-based road recognition. [ref]  
    [2013] Obstacle detection and mapping in low-cost, low-power multi-robot systems using an Inverted Particle Filter. [ref]  
    [2013] Real-time estimation of drivable image area based on monocular vision. [ref]  
    [2013] Road model prediction based unstructured road detection. [ref]  
    [2013] Selective Combination of Visual and Thermal Imaging for Resilient Localization in Adverse Conditions: Day and Night, Smoke and Fire. [ref]  
    [2012] Road Tracking Method Suitable for Both Unstructured and Structured Roads. [ref]  
    [2012] Autonomous Navigation and Sign Detector Learning. [ref]  
    [2012] Design of a Multi-Sensor Cooperation Travel Environment Perception System for Autonomous Vehicle. [ref]  
    [2012] Learning in Reality: a Case Study of Stanley, the Robot That Won the Darpa Challenge. [ref]  
    [2012] Portable and Scalable Vision-Based Vehicular Instrumentation for the Analysis of Driver Intentionality. [ref]  
    [2012] What could move? Finding cars, pedestrians and bicyclists in 3D laser data. [ref]  
    [2012] The Stixel World. [ref]  
    [2011] Stereo-based road boundary tracking for mobile robot navigation. [ref]  
    [2009] Autonomous Information Fusion for Robust Obstacle Localization on a Humanoid Robot. [ref]  
    [2009] Learning long-range vision for autonomous off-road driving. [ref]  
    [2009] On-line road boundary modeling with multiple sensory features, flexible road model, and particle filter. [ref]  
    [2008] The Area Processing Unit of Caroline - Finding the Way through DARPA's Urban Challenge. [ref]  
    [2008] Vehicle detection and tracking for the Urban Challenge. [ref]    
    [2007] Low cost sensing for autonomous car driving in highways. [ref]  
    [2007] _Stereo and Colour Vision Techniques for Autonomous Vehicle Guidance _. [ref]  
    [2000] Real-time multiple vehicle detection and tracking from a moving vehicle. [ref]  
导航与路径规划  
    [2017] Explaining How a Deep Neural Network Trained with End-to-End Learning Steers a Car[ref]  
    [2016] A Self-Driving Robot Using Deep Convolutional Neural Networks on Neuromorphic Hardware. [ref]  
    [2016] End to End Learning for Self-Driving Cars. [ref]  
    [2016] A Survey of Motion Planning and Control Techniques for Self-driving Urban Vehicles. [ref]  
    [2016] A Convex Optimization Approach to Smooth Trajectories for Motion Planning with Car-Like Robots. [ref]  
    [2016] Routing Autonomous Vehicles in Congested Transportation Networks: Structural Properties and Coordination Algorithms. [ref]  
    [2016] Machine Learning for Visual Navigation of Unmanned Ground Vehicles. [ref]  
    [2016] Real-time self-driving car navigation and obstacle avoidance using mobile 3D laser scanner and GNSS. [ref]  
    [2016] Watch this: Scalable cost-function learning for path planning in urban environments. [ref]  
    [2015] DeepDriving: Learning Affordance for Direct Perception in Autonomous Driving. [ref, data, code]  
    [2015] Automatic Driving on Ill-defined Roads: An Adaptive, Shape-constrained, Color-based Method. [ref, data]  
    [2015] A Framework for Applying Point Clouds Grabbed by Multi-Beam LIDAR in Perceiving the Driving Environment. [ref]  
    [2015] How Much of Driving Is Preattentive?. [ref]  
    [2015] Map-building and Planning for Autonomous Navigation of a Mobile Robot. [ref]  
    [2014] A Multiple Attribute-based Decision Making model for autonomous vehicle in urban environment. [ref]  
    [2014] A prediction-based reactive driving strategy for highly automated driving function on freeways. [ref]  
    [2014] An RRT-based navigation approach for mobile robots and automated vehicles. [ref]  
    [2014] Image Feature-based Traversability Analysis for Mobile Robot Navigation in Outdoor Environment. [ref]  
    [2014] Speed Daemon: Experience-Based Mobile Robot Speed Scheduling. [ref]  
    [2014] Toward human-like motion planning in urban environments. [ref]  
    [2013] Motion Estimation for Self-Driving Cars with a Generalized Camera. [ref]  
    [2013] Development of a Navigation Control System for an Autonomous Formula Sae-electric Race Car. [ref]  
    [2013] Low speed automation: Technical feasibility of the driving sharing in urban areas. [ref]  
    [2013] Path selection based on local terrain feature for unmanned ground vehicle in unknown rough terrain environment. [ref]  
    [2013] Stereo-based Autonomous Navigation and Obstacle Avoidance. [ref]  
    [2012] Development of an Autonomous Vehicle for High-Speed Navigation and Obstacle Avoidance. [ref]  
    [2012] Fast Vanishing-Point Detection in Unstructured Environments. [ref]  
    [2012] Navigation of an Autonomous Car Using Vector Fields and the Dynamic Window Approach. [ref]  
    [2012] Road direction detection based on vanishing-point tracking. [ref]  
    [2012] Self-supervised learning to visually detect terrain surfaces for autonomous robots operating in forested terrain. [ref]  
    [2012] Visual Navigation for Mobile Robots. [ref]  
    [2011] A new Approach for Robot Motion Planning using Rapidly-exploring Randomized Trees. [ref]  
    [2011] Driving me around the bend: Learning to drive from visual gist. [ref]  
    [2011] Optimized route network graph as map reference for autonomous cars operating on German autobahn. [ref]  
    [2011] Template-based autonomous navigation and obstacle avoidance in urban environments. [ref]  
    [2010] Vision-Based Autonomous Navigation System Using ANN and FSM Control[ref]  
    [2010] An optimal-control-based framework for trajectory planning, threat assessment, and semi-autonomous control of passenger vehicles in hazard avoidance scenarios. [ref]  
    [2010] Perception for Urban Driverless Vehicles: Design and Implementation. [ref]  
    [2009] Autonomous Offroad Navigation Under Poor GPS Conditions. [ref]  
    [2009] Autonomous robot navigation in outdoor cluttered pedestrian walkways. [ref]  
    [2009] Fast Path Planning in Uncertain Environments: Theory and Experiments. [ref]  
    [2009] Trajectory Based Autonomous Vehicle following Using a Robotic Driver. [ref]  
    [2009] Anticipatory Driving for a Robot-Car Based on Supervised Learning. [ref]  
    [2008] A Robust Motion Planning Approach for Autonomous Driving in Urban Areas. [ref]  
    [2008] Motion Planning in Urban Environments. [ref]  
    [2008] Motion planning in urban environments: Part II. [ref]  
    [2008] Planning Long Dynamically Feasible Maneuvers for Autonomous Vehicles. [ref]  
    [2007] Online Speed Adaptation Using Supervised Learning for High-Speed, Off-Road Autonomous Driving.[ref]  
    [2007] Predictive Active Steering Control for Autonomous Vehicle Systems. [ref]  
    [2006] Probabilistic Terrain Analysis For High-Speed Desert Driving.[ref]  
控制  
    [2016] Predictive Control for Autonomous Driving with Experimental Evaluation on a Heavy-duty Construction Truck. [ref]  
    [2015] Model Predictive Control of Autonomous Mobility-on-Demand Systems. [ref]  
    [2015] Toward integrated motion planning and control using potential fields and torque-based steering actuation for autonomous driving. [ref]  
    [2013] Strategic decision making for automated driving on two-lane, one way roads using model predictive control. [ref]  
    [2012] Autonomous vehicles control in the VisLab Intercontinental Autonomous Challenge. [ref]  
    [2012] Optimal Planning and Control for Hazard Avoidance of Front-wheel Steered Ground Vehicles. [ref]  
    [2009] Automatic Steering Methods for Autonomous Automobile Path Tracking. [ref]  
    [2009] Comparison of Three Control Methods for an Autonomous Vehicle. [ref]  
模拟  
    [2016] Learning a Driving Simulator. [ref]  
    [2014] From a Competition for Self-Driving Miniature Cars to a Standardized Experimental Platform: Concept, Models, Architecture, and Evaluation. [ref]  
    [2014] Technical evaluation of the Carolo-Cup 2014 - A competition for self-driving miniature cars. [ref]  
    [2014] Crowdsourcing as a methodology to obtain large and varied robotic data sets. [ref]  
    [2014] Efficient Learning of Pre-attentive Steering in a Driving School Framework. [ref]  
    [2007] A Simulation and Regression Testing Framework for Autonomous Vehicles. [ref]  
    [2006] Robot Competitions Ideal Benchmarks for Robotics Research. [ref]  
软件工程  
    [2016] Evaluation of Sandboxed Software Deployment for Real-time Software on the Example of a Self-Driving Heavy Vehicle. [ref]  
    [2014] Engineering the Hardware/Software Interface for Robotic Platforms - A Comparison of Applied Model Checking with Prolog and Alloy. [ref]  
    [2014] Comparison of Architectural Design Decisions for Resource-Constrained Self-Driving Cars - A Multiple Case-Study. [ref]  
    [2014] (Re)liability of Self-driving Cars. An Interesting Challenge!. [ref]  
    [2014] Explicating, Understanding, and Managing Technical Debt from Self-Driving Miniature Car Projects. [ref]  
    [2014] Towards Continuous Integration for Cyber-Physical Systems on the Example of Self-Driving Miniature Cars. [ref]  
    [2014] Saving virtual testing time for CPS by analyzing code coverage on the example of a lane-following algorithm. [ref]  
    [2013] Parallel scheduling for cyber-physical systems: analysis and case study on a self-driving car[ref]  
    [2012] SAFER: System-level Architecture for Failure Evasion in Real-time Applications. [ref]  
    [2011] A Flexible Real-Time Control System for Autonomous Vehicles. [ref]  
    [2010] Automating acceptance tests for sensor- and actuator-based systems on the example of autonomous vehicles. [ref]  
    [2007] Software & Systems Engineering Process and Tools for the Development of Autonomous Driving Intelligence [ref]  
人机交互  
    [2017] Universal Design of User Interfaces in Self-driving Cars [ref]  
    [2015] User interface considerations to prevent self-driving carsickness. [ref]  
    [2014] Public Opinion about Self-driving Vehicles. [ref]  
    [2014] Setting the Stage for Self-driving Cars: Exploration of Future Autonomous Driving Experiences. [ref]  
    [2014] Three Decades of Driver Assistance Systems: Review and Future Perspectives. [ref]  
    [2013] Review Article Automotive Technology and Human Factors Research: Past, Present, and Future. [ref]  
    [2012] Safe semi-autonomous control with enhanced driver modeling. [ref]  
    [2012] Semi-autonomous Car Control Using Brain Computer Interfaces. [ref]  
    [2011] iDriver - Human Machine Interface for Autonomous Cars. [ref]  
    [2010] Driving an Autonomous Car with Eye Tracking Driving an Autonomous Car with Eye Tracking. [ref]  
    [2010] Remote Controlling an Autonomous Car with an Iphone. [ref]  
    [2009] Car-driver Cooperation in Future Vehicles I. Adas and Autonomuos Vehicle. [ref]  
    [2009] Driver Inattention Detection based on Eye Gaze - Road Event Correlation. [ref]  
 基础架构  
     [2014] Control of Robotic Mobility-On-Demand Systems: a Queueing-Theoretical Perspective. [ref]  
    [2014] Priority-based Intersection Control Framework for Self-Driving Vehicles: Agent-based Model Development and Evaluation. [ref]  
    [2014] A lattice-based approach to multi-robot motion planning for non-holonomic vehicles. [ref]  
    [2005] Cooperative autonomous driving: intelligent vehicles sharing city roads. [ref]  
    [2014] Achieving Integrated Convoys: Cargo Unmanned Ground Vehicle Development and Experimentation. [ref]  
    [2014] Priority-based coordination of mobile robots. [ref]  
    [2012] Exploration and Mapping with Autonomous Robot Teams Results from the Magic 2010 Competition. [ref]  
    [2012] Progress toward multi-robot reconnaissance and the MAGIC 2010 competition. [ref]  
三：实验室  
    Center for Automotive Research at Stanford - Current areas of research focuses on human-centered mobility themes like understanding how people will interact with increasingly automated vehicles, societal impacts of vehicle automation from policy to ethics to law, technology advances in sensing, decision-making and control.  
    SAIL-TOYOTA Center for AI Research at Stanford - The theme of the center is Human-Centered Artificial Intelligence for Future Intelligent Vehicles and Beyond.  
    Berkeley DeepDrive - Investigates state-of-the-art technologies in computer vision and machine learning for automotive application.  
    Princeton Autonomous Vehicle Engineering - undergraduate student-led research group at Princeton University dedicated to advancing and promoting the field of robotics through competitive challenges, self-guided research and community outreach.  
    University of Maryland Autonomous Vehicle Laboratory - conducts research and development in the area of biologically inspired design and robotics.  
    University of Waterloo WAVE Laboratory - Research areas includes Multirotor UAV, Autonomous driving and Multi-Camera Parallel Tracking and Mapping.  
    Oxford Robotics Institute – Autonomous Systems - Researches all aspects of land based mobile autonomy.  
    Autonomous Lab - Freie Universität Berlin - Computer Vision, Cognitive Navigation, Spatial Car Environment Capture.  
    Honda Research Institute - USA - engaged in development and integration of multiple sensory modules and the coordination of these components while fulfilling tasks such as stable motion planning, decision making, obstacle avoidance, and control (test).  
    Toyota-CSAIL Research Center at MIT - Aimed at furthering the development of autonomous vehicle technologies, with the goal of reducing traffic casualties and potentially even developing a vehicle incapable of getting into an accident.  
    Princeton VisionRobotics - Autonomous Driving and StreetView.  
    CMU The Robotic Institute Vision and Autonomous Systems Center (VASC) - working in the areas of computer vision, autonomous navigation, virtual reality, intelligent manipulation, space robotics, and related fields.  
四：数据集  
    Udacity - Udacity driving datasets released for Udacity Challenges. Contains ROSBAG training data. (~80 GB).  
    Comma.ai - 7 and a quarter hours of largely highway driving. Consists of 10 videos clips of variable size recorded at 20 Hz with a camera mounted on the windshield of an Acura ILX 2016. In parallel to the videos, also recorded some measurements such as car's speed, acceleration, steering angle, GPS coordinates, gyroscope angles. These measurements are transformed into a uniform 100 Hz time base.  
    Oxfords Robotic Car - over 100 repetitions of a consistent route through Oxford, UK, captured over a period of over a year. The dataset captures many different combinations of weather, traffic and pedestrians, along with longer term changes such as construction and roadworks.  
    KITTI Vision Benchmark Suite - 6 hours of traffic scenarios at 10-100 Hz using a variety of sensor modalities such as highresolution color and grayscale stereo cameras, a Velodyne 3D laser scanner and a high-precision GPS/IMU inertial navigation system.  
    University of Michigan North Campus Long-Term Vision and LIDAR Dataset - consists of omnidirectional imagery, 3D lidar, planar lidar, GPS, and proprioceptive sensors for odometry collected using a Segway robot.  
    University of Michigan Ford Campus Vision and Lidar Data Set - dataset collected by an autonomous ground vehicle testbed, based upon a modified Ford F-250 pickup truck. The vehicle is outfitted with a professional (Applanix POS LV) and consumer (Xsens MTI-G) Inertial Measuring Unit (IMU), a Velodyne 3D-lidar scanner, two push-broom forward looking Riegl lidars, and a Point Grey Ladybug3 omnidirectional camera system.  
    DIPLECS Autonomous Driving Datasets (2015) - dataset was recorded by placing a HD camera in a car driving around the Surrey countryside. The dataset contains about 30 minutes of driving. The video is 1920x1080 in colour, encoded using H.264 codec. Steering is estimated by tracking markers on the steering wheel. The car's speed is estimated from OCR the car's speedometer (but the accuracy of the method is not guaranteed).  
    Velodyne SLAM Dataset from Karlsruhe Institute of Technology - two challenging datasets recorded with the Velodyne HDL64E-S2 scanner in the city of Karlsruhe, Germany.  
    SYNTHetic collection of Imagery and Annotations (SYNTHIA) - consists of a collection of photo-realistic frames rendered from a virtual city and comes with precise pixel-level semantic annotations for 13 classes: misc, sky, building, road, sidewalk, fence, vegetation, pole, car, sign, pedestrian, cyclist, lanemarking.  
    Cityscape Dataset - focuses on semantic understanding of urban street scenes. large-scale dataset that contains a diverse set of stereo video sequences recorded in street scenes from 50 different cities, with high quality pixel-level annotations of 5 000 frames in addition to a larger set of 20 000 weakly annotated frames. The dataset is thus an order of magnitude larger than similar previous attempts. Details on annotated classes and examples of our annotations are available.  
    CSSAD Dataset - Several real-world stereo datasets exist for the development and testing of algorithms in the fields of perception and navigation of autonomous vehicles. However, none of them was recorded in developing countries and therefore they lack the particular characteristics that can be found in their streets and roads, like abundant potholes, speed bumpers and peculiar flows of pedestrians. This stereo dataset was recorded from a moving vehicle and contains high resolution stereo images which are complemented with orientation and acceleration data obtained from an IMU, GPS data, and data from the car computer.  
    Daimler Urban Segmetation Dataset - consists of video sequences recorded in urban traffic. The dataset consists of 5000 rectified stereo image pairs with a resolution of 1024x440. 500 frames (every 10th frame of the sequence) come with pixel-level semantic class annotations into 5 classes: ground, building, vehicle, pedestrian, sky. Dense disparity maps are provided as a reference, however these are not manually annotated but computed using semi-global matching (sgm).  
    Self Racing Cars - XSens/Fairchild Dataset - The files include measurements from the Fairchild FIS1100 6 Degree of Freedom (DoF) IMU, the Fairchild FMT-1030 AHRS, the Xsens MTi-3 AHRS, and the Xsens MTi-G-710 GNSS/INS. The files from the event can all be read in the MT Manager software, available as part of the MT Software Suite, available here.
    MIT AGE Lab - a small sample of the 1,000+ hours of multi-sensor driving datasets collected at AgeLab.  
    Yet Another Computer Vision Index To Datasets (YACVID) - a list of frequently used computer vision datasets.  
    KUL Belgium Traffic Sign Dataset - a large dataset with 10000+ traffic sign annotations, thousands of physically distinct traffic signs. 4 video sequences recorded with 8 high resolution cameras mounted on a van, summing more than 3 hours, with traffic sign annotations, camera calibrations and poses. About 16000 background images. The material is captured in Belgium, in urban environments from Flanders region, by GeoAutomation.  
    LISA: Laboratory for IntelligentSafe Automobiles, UC San Diego Datasets - traffic sign, vehicles detection, traffic lights, trajectory patterns.  
    Multisensory Omni-directional Long-term Place Recognition (MOLP) dataset for autonomous driving It was recorded using omni-directional stereo cameras during one year in Colorado, USA. paper  
