# Driverless-Car-Open-Source-software

Car driving open source software which could work with any type/make of car 
Requirements



Curate all the available best technologies and make them work together

Determine location--- leverage Garmin GPS 
Determine Road objects Traffic lights, road signs, road lane markings---leverage sensors installed around car
Determine car condition---leverage car dashboard data 

http://www.nvidia.com/object/drive-px.html

http://www.nvidia.com/object/driveworks.html


http://www.ros.org/core-components/

http://www.ros.org/integration/

http://www.perronerobotics.com/dak/


NVIDIA DRIVE™ PX 2 is the open AI car computing platform that enables automakers and their tier 1 suppliers to accelerate production of automated and autonomous vehicles. It scales from a palm-sized, energy efficient module for AutoCruise capabilities, to a powerful AI supercomputer capable of autonomous driving. - See more at: http://www.nvidia.com/object/drive-px.html#sthash.ChXXYuPo.dpuf

The new single-processor configuration of DRIVE PX 2 for AutoCruise functions —which include highway automated driving and HD mapping—consumes just 10 watts of power. Plus, it enables vehicles to use deep neural networks to process data from multiple cameras and sensors.
 
DRIVE PX 2 can understand in real-time what's happening around the vehicle, precisely locate itself on an HD map, and plan a safe path forward. It's the world's most advanced self-driving car platform—combining deep learning, sensor fusion, and surround vision to change the driving experience.
 
The scalable architecture is available in a variety of configurations. These range from one passively cooled mobile processor operating at 10 watts, to a multi-chip configuration with two mobile processors and two discrete GPUs delivering 24 trillion deep learning operations per second. Multiple DRIVE PX 2 platforms can be used in parallel to enable fully autonomous driving.
 
With a unified architecture, deep neural networks can be trained on a system in the data center, and then deployed in the car.
- See more at: http://www.nvidia.com/object/drive-px.html#sthash.ChXXYuPo.dpuf

http://www.nvidia.com/object/driveworks.html

Developer Tools for Self-Driving Cars
Fully autonomous and driver assistance technologies have become a key focus for every car manufacturer, as well as transportation services and technology companies.
 
The car needs to know exactly where it is, recognize the objects around it, and continuously calculate the optimal path for a safe driving experience. NVIDIA DriveWorks software development kit (SDK) gives developers a foundation upon which to build applications, leveraging the computationally intensive algorithms for object detection, map localization, and path planning.
- See more at: http://www.nvidia.com/object/driveworks.html#sthash.6A1IRgHN.dpuf


DETECTION
 
NVIDIA DRIVE PX 2 platforms are built to enable sensor fusion, deep learning, and advanced computer vision (CV) libraries and primitives. Together, these technologies deliver an impressive array of detection and tracking capabilities.
- See more at: http://www.nvidia.com/object/driveworks.html#sthash.6A1IRgHN.dpuf

END-TO-END HD MAPPING
 
Mapping is a vital aspect of autonomous driving. NVIDIA has an open system for rapidly creating HD maps and keeping them updated. This end-to-end system is built on DriveWorks to enable deep learning in the car and in the cloud for the most efficient map creation--compressing what has traditionally taken weeks down to minutes. Learn more.
- See more at: http://www.nvidia.com/object/driveworks.html#sthash.6A1IRgHN.dpuf

LOCALIZATION
 
Understanding exactly where an autonomous vehicle is on the road is critical to it being able to safely drive down the road. The ability to integrate high definition mapping data, such as that from map leader HERE, will ensure that the vehicle is able to not only maintain its proper position in the lane, but to navigate safely through any type of complex traffic scenarios.
- See more at: http://www.nvidia.com/object/driveworks.html#sthash.6A1IRgHN.dpuf

PATH PLANNING
 
An autonomous car needs to be able to safely navigate around any potential hazards in a highly dynamic environment. Sophisticated algorithms are employed to calculate free space–where the vehicle can drive–as well as anticipate how the environment may change. In addition, the vehicle must move in a smooth manner, to avoid surprises to the occupants, as well as other vehicles. Complex path planning takes all these factors into account to ultimately deliver a safe and enjoyable experience.
- See more at: http://www.nvidia.com/object/driveworks.html#sthash.6A1IRgHN.dpuf

Advanced Driver Assistance Systems (ADAS)
Conventional ADAS technology can detect some objects, do basic classification, alert the driver of hazardous road conditions, and in some cases, slow or stop the vehicle. This level of ADAS is great for applications like blind spot monitoring, lane change assistance, and forward collision warnings.
NVIDIA DRIVE™ PX 2 AI car computers take driver assistance to the next level. They take advantage of deep learning and include a software development kit (SDK) for autonomous driving called DriveWorks. This SDK gives developers a powerful foundation for building applications that leverage computationally intensive algorithms for object detection, map localization, and path planning.
With NVIDIA self-driving car solutions, a vehicle's ADAS can discern a police car from a taxi; an ambulance from a delivery truck; or a parked car from one that is about to pull out into traffic. It can even extend this capability to identify everything from cyclists on the sidewalk to absent-minded pedestrians.
- See more at: http://www.nvidia.com/object/advanced-driver-assistance-systems.html#sthash.kQS93q6F.dpuf

Enjoy the ride with the digital cockpit
NVIDIA uses the newest graphics processing architecture to deliver high-resolution, high frame-rate, photorealistic graphics for a range of applications. These include everything from rich, easy-to-read graphics and premium audio interfaces, to natural language processing, interactive cockpit controls, and 3D navigation with intuitive, glanceable displays.
PERSONALIZE YOUR JOURNEY
Traditional analog gauges and dials are going digital and demanding the highest levels of image quality. At the same time, the information displayed in the center stack and instrument cluster are starting to merge, placing very high demands on the cluster graphics system. NVIDIA solutions enable digital cockpit solutions.
SURROUND VISION WITH ADVANCED RENDERING
Conventional surround view systems show the driver a virtual view of the area around the car, but often have poor image quality due to warping effects from the fisheye camera lenses. NVIDIA uses sophisticated structure-from-motion and advanced stitching for better image rendering and reduced "ghosting", such as where a line on the pavement can appear in two places at once. 

Powerful graphics enable NVIDIA to render a virtual car with high-detail models and realistic lighting effects, so you see what looks like your car, rather than a generic or toy model.
- See more at: http://www.nvidia.com/object/automotive-infotainment-navigation.html#sthash.R2YzYUmQ.dpuf



MoveIt! is a motion planning library that offers efficient, well-tested implementations of state of the art planning algorithms that have been used on a wide variety of robots, from simple wheeled platforms to walking humanoids. Whether you want to apply an existing algorithm or develop your own approach, MoveIt! has what you need for motion planning. Through its integration with ROS, MoveIt! can be used with any ROS-supported robot. Planning data can be visualized with rviz and rqt plugins, and plans can be executed via the ROS control system.

OpenCV is the premier computer vision library, used in academia and in products around the world. OpenCV provides many common computer vision algorithms and utilities that you can use and build upon. ROS provides tight integration with OpenCV, allowing users to easily feed data published by cameras of various types into OpenCV algorithms, such as segmentation and tracking. ROS builds on OpenCV to provide libraries such as image_pipeline, which can be used for camera calibration, monocular image processing, stereo image processing, and depth image processing. If your robot has cameras connected through USB, Firewire, or Ethernet, ROS and OpenCV will make your life easier.

Perhaps the most well-known tool in ROS, rviz provides general purpose, three-dimensional visualization of many sensor data types and any URDF-described robot.

rviz can visualize many of the common message types provided in ROS, such as laser scans, three-dimensional point clouds, and camera images. It also uses information from the tf library to show all of the sensor data in a common coordinate frame of your choice, together with a three-dimensional rendering of your robot. Visualizing all of your data in the same application not only looks impressive, but also allows you to quickly see what your robot sees, and identify problems such as sensor misalignments or robot model inaccuracies.

ROS provides rqt, a Qt-based framework for developing graphical interfaces for your robot. You can create custom interfaces by composing and configuring the extensive library of built-in rqt plugins into tabbed, split-screen, and other layouts. You can also introduce new interface components by writing your own rqt plugins .

The rqt_graph plugin provides introspection and visualization of a live ROS system, showing nodes and the connections between them, and allowing you to easily debug and understand your running system and how it is structured.


With the rqt_plot plugin, you can monitor encoders, voltages, or anything that can be represented as a number that varies over time. The rqt_plot plugin 

allows you to choose the plotting backend (e.g., matplotlib, Qwt, pyqtgraph) that best fits your needs.

rqt_publisher screenshot

For monitoring and using topics, you have the rqt_topic and rqt_publisher plugins. The former lets you monitor and introspect any number of topics being published within the system. The latter allows you to publish your own messages to any topic, facilitating ad hoc experimentation with your system.



MoveIt! 

Instal LIDAR system, short for Light Detection and Ranging system provides accurate 3D information on the surrounding environment Using this data, the processor implements object identification, motion vector determination, collision prediction, and avoidance strategies. The LIDAR unit is well-suited to "big picture" imaging, and provides the needed 360⁰ view by using a rotating, scanning mirror assembly on the top of the car. The data collected would be used to calculate the vehicles' position, speed, and direction relative to these external objects

Install central processing unit to process all information and make decisions

360fly 4K Action Camera

Product Features
Powerful 16-megapixel image sensor

Provides 4K video resolution 2880 x 2880 pixels up to 30fps.
Eight glass element ultra-fisheye lens

Allows to capture your life in immersive, interactive 360° video.
Provides professional video features

Includes time-lapse and front-facing modes as well as motion and audio activation.
Built-in dual omni-directional microphones

For crisp, clear audio.
64GB internal storage

Offers plenty of room to store recorded video footage.
Durable and robust construction

Features dustproof, shockproof and water-resistant design with non-slip/soft-touch body coating.
Gyroscope, non-assisted GPS and Live Stream via mobile app

For convenient use and control.
Built-In 1710mAh Li-Polymer battery

Delivers improved battery life up to 1.5 hours.
USB 2.0 interface

For easy image transfer. Wireless streaming capability allows the camera to share immersive, interactive video.
Livit mobile app compatible

Provides wireless connectivity to iOS and Android devices.
http://www.bestbuy.com/site/360fly-4k-action-camera/5256502.p?skuId=5256502

http://drivesimsimulator.com/en/

The simulation program DriveSim allows you to practice driving as if you were commanding a real vehicle, thanks to its realistic situations and environment.
Features

    DriveSim scenarios include real traffic and pedestrians. With this program, you will have the positiblity of doing different tours with any climatic settings, timing and adhesion: driving at dusk, on slippery surfaces, snowy environments, with rain or even practice emergency braking with and without ABS.
    With DriveSim you mayconduct initial training on track, practicing overtaking, driving on urban roads, service roads, roundabouts and efficient driving, among many other options.
    Vehicles:Different types of vehicles may be used: diesel or petrol, front wheel drive, rear or 4x4, with manual or automatic, and different power (88HP, 114HP, and 147HP)
    Languages (optional):Spanish, German, Portuguese, Basque, Catalan, English, French, Chinese, Italian, Portuguese (Brazil), Arabic and others.
    Controlling students (optional): Management of students exercises performed by each of them with printed reports and listings.
    To use DriveSim you need the DS -PAD:lighting levers, turn signals and wipers, seat belt and parking brake.

http://www.livitnow.com/projects/livitnow/
Livit Now is the world’s first mobile-to-mobile VR app. With the free Livit Now app you can stream live from 360-degree video directly to friends and followers around the world.

https://buy.garmin.com/en-US/US/on-the-road/automotive/garmin-driveluxe-50lmthd/prod523329.html
Premium GPS Navigator with Smart Features

    Premium 5-inch auto navigator with powered magnetic mount and sleek metal design
    Detailed maps of North America with free lifetime¹ map updates and HD Digital Traffic², the fastest traffic solution available from Garmin
    Bluetooth® hands-free calling³ and voice-activated navigation
    Driver alerts for increased awareness, including upcoming sharp curves, school zones, speed changes and more
    Customizable smartphone notifications4 let you display calls, texts and other app alerts on your navigation screen

Garmin DriveLuxe GPS navigator provides driver alerts to encourage safer driving and increase situational awareness. Warnings include alerts for sharp curves, speed changes, railroad crossings, animal crossings and more. Additionally, Garmin DriveLuxe notifies you when driving the wrong way on a one-way street and sends warnings for nearby school zones. Receive alerts for nearby red light and speed cameras5, and be prepared for sudden halts in traffic with upcoming traffic jam6 alerts. For longer drives, a fatigue warning7 suggests break times and potential rest areas after hours of driving. The Up Ahead feature lets you easily see places up ahead and milestones along your route, without leaving the map view

Talk to Garmin DriveLuxe

Garmin DriveLuxe offers you the option of convenient voice-activated navigation. Control Garmin DriveLuxe with your voice, while your hands remain safely on the wheel.
Extensive Smart Features

Sync a Bluetooth-enabled device, such as your smartphone, to Garmin DriveLuxe for hands-free calling, and receive smart notifications on your Garmin DriveLuxe display. Receive calls, text messages and calendar reminders without ever removing your hands from the steering wheel to reach for your phone. Stay focused on your drive ahead while staying connected with customizable smart notifications that conveniently appear right on your navigation display.

For real-time information such as weather and traffic conditions, download Smartphone Link8 mobile app, which connects your Garmin DriveLuxe GPS navigator with your compatible smartphone.

Navigate Complex Interchanges with Ease

Active Lane Guidance with voice prompts prepares you to drive through an exit or interchange with confidence. As you approach, an animated model uses brightly colored arrows to indicate the proper lane needed for your route; a friendly voice offers additional help. Bird’s Eye junction view offers a detailed view of interchanges, looking down as if from overhead. And, photoReal Junction View realistically displays junctions and interchanges along your route, including the surrounding landscape.

Our Best Traffic Solutions

HD Digital Traffic is the best traffic solution available from Garmin. HD Digital Traffic is fast and free² — no distracting advertising and no subscription fees, ever, for the useful life of your device. Receive traffic updates as often as every 30 seconds. Plus, HD Digital Traffic has a great coverage area that includes interstates, highways and secondary roads. HD Digital Traffic is voice-activated, so it responds to spoken requests. It can give details about the situation, such as how many minutes of delay to expect and if there are any possible detours. Even learn whether or not you are on the fastest route. Traffic information is delivered straight to your Garmin DriveLuxe — no smartphone needed.

Guidance Using Recognizable Landmarks

Garmin DriveLuxe redefines “spoken turn-by-turn directions” with Garmin Real Directions™, easy-to-understand driving directions that guide like a friend, using recognizable landmarks, buildings and traffic lights (e.g., “Turn right after the red building” or “Turn left after the QT”). It’s preloaded with millions more new and popular places, thanks to Foursquare®

Find Exactly Where You Need to Go

The Direct Access feature simplifies navigating to select complex destinations, like airports and shopping malls, by finding a place within a larger location. Direct Access even navigates through parking lots to find the entrance nearest your destination. When navigating to the mall, Direct Access gives additional location information for specific retail stores inside. For example, “Arriving at Woodfield Mall. Anthropologie is inside, on the upper level.”

Add a Camera to Your Drive

For a complete navigation solution, Garmin DriveLuxe pairs with the BC™ 30 wireless backup camera (sold separately; professional installation recommended). Once connected, you can easily see vehicles, pedestrians and other obstacles right on the Garmin DriveLuxe display, as you move in reverse

https://buy.garmin.com/en-US/US/on-the-road/automotive/garmin-driveassist-50lmt/on-the-road/automotive/garmin-driveluxe-50lmthd/on-the-road/533/bc-30-wireless-backup-camera/prod501486.html

BC™ 30 Wireless Backup Camera

Keep a Watchful Eye on What’s Behind You

    Shows what’s behind your vehicle when in reverse
    View footage right on your GPS navigator’s display* (sold separately)
    Wire to constant power and toggle easily between camera and navigation modes
    Wirelessly transmits video up to 45 feet
    Rugged enough to withstand harsh weather

A quality backup camera like the Garmin BC 30 can significantly enhance rearward visibility for drivers and, thus, help minimize the risk of “blind zone” accidents whenever your vehicle is moving in reverse.
Take the Worry out of Backing Up

When paired with a compatible GPS navigator, the BC 30 wireless backup camera helps you easily spot vehicles, pedestrians, pets and other hard-to-see obstructions behind your vehicle. If the camera is wired to your reverse lights for power, your navigator can automatically display camera footage every time the vehicle is shifted into reverse – and go back into navigation mode when shifted into a forward gear.
See Clearly What Needs to be Seen

As another option, you can wire the system to constant power, which allows you to toggle between the navigation display and backup display modes at the press of a button. The transmitter will send camera footage to your navigator’s receiver mounted up to 45 feet (13.7 meters) away (range varies based on installation; some vehicles may require an extension cable,


Drop-in Autonomy Kit (DAK)
Rapidly transform any car or truck into an automated self-driving vehicle using a drop-in kit.

The Drop-in Autonomy Kit (DAK) is a system for outfitting existing vehicles with autonomous and remote control driving capabilities. The kit includes all of the actuators, sensors, electronics, and software needed in one package. The DAK allows for a 30 minute or less install into any vehicle and allows for an operator to sit in the driver's seat.

DAK system key features:

    Steering, brake, and throttle control
    Installs in any vehicle in 30 minutes or less
    Programmatic fully autonomous navigation
    Route and trajectory planning
    Sophisticated maneuver planning
    Comfortably accommodate operator in driver's seat
    Fully autonomous with a remote tele-operation option
    
    dak adapters/components

The DAK includes a family of adapters for different pedal styles as well as adjustable components to fit various cabin layouts. The steering force reaction stand anchors firmly in the rear of the vehicle, leaving ample room for vehicle passengers and equipment.

Man and Machine

While the DAK delivers fully autonomous operation, sometimes you want to have a human ride along in the driver's seat. The placement of the DAK pedal actuators and steering force reaction stand allow for a person to sit comfortably in the driver's seat and, if needed, take control of the vehicle at any time with the press of a button.

Local or Global Positioning

The DAK includes sensors for position, heading and speed as well as a ruggedized computer with software for navigation and control. The DAK is not limited to GPS for position information. For testing that requires tunable precision or indoor/covered track operation, the DAK is available with an alternative local positioning system called Locata™. Locata uses a constellation of LocataLite™ units that you can use where you want, when you want. Locata™ allows the DAK to deliver tunable accuracy indoors or outdoors, rain or shine, 24/7.

Control and Navigation Software

The DAK system includes an embedded computer with software for defining and controlling your tests, as well as transferring and reviewing data.  The DAK software also performs real-time tasks for autonomous self-navigation and bot-to-bot communication. The DAK was developed based on requirements from the Insurance Institute for Highway Safety (IIHS) and features software support for performing tests, including NHTSA Crash-Imminent Braking (CIB), NHTSA Dynamic Brake Support (DBS), Euro NCAP Autonomous Emergency Braking (AEB) and others.

Built using the MAX™ general purpose robotics and automated vehicle operating system, the DAK inherits a long legacy of sophisticated fully autonomous robotics functions, maneuvers, and programmable behaviors. 

https://perronerobotics.squarespace.com/max

What is MAX?

In short, MAX is the brain of a self-driving car or robot. MAX is a software platform engineered to make building new autonomous solutions fast and efficient. Using our graphical interface, MAX allows engineers to create autonomous solutions by snapping together pieces much like building with Legos. MAX works with all sensors regardless of brand and type to provide your solution with a comprehensive picture of the road and environment. Further, MAX works with all types of control systems for your autonomous vehicle including drive-by-wire and mechanical actuators. Unlike our competitors, MAX is real-time capable, has a path to ISO certification, and is a "full-stack" comprehensive autonomous vehicle software platform. MAX allows you to develop a solution that works not only in your lab and your test track but also in commercial production applications without requiring any rewrites.

MAX stands for Mobile Autonomous 'X', whereby 'X' is a variable in which a robotics designer can define and create their robotics application of choice. 

Rapid Development

MAX’s development user interface supports configuration of a new autonomous system in minutes. Simply use our graphical interface to select your sensors and control systems from the provided library and just drop it on your vehicle and hit the road! 

Simulation Capability

Our solution includes an optional simulator toolset that allows you to test your autonomous vehicle under real-world conditions including sun, rain, snow, ice, and darkness. Nothing can compare to physical testing, but our simulation solution can help reduce development cycles and cost by letting your team test quickly and safely from their very own desk.

Runs from Day 1

With the included autonomous application, you will be ready to drive your vehicle without the need to write a single line of code. MAX handles all of the critical operating functions including logging, security, and system management so you don’t have to.

Road-Ready

MAX has operated in real-time environments for over a decade and has been tested with all major real-time operating systems. Further, MAX was built as a production grade system from day 1 and is in the process of certification as ISO 26262 ASIL x compliant. MAX is the one solution that works from the test bench to the test track to the manufacturing line without ever needing a rewrite.

Flexible

While MAX includes all required functions out of the box, you can quickly insert your own custom algorithms and logic into MAX. That way your existing investments in your current software can be re-used. MAX's layered architecture and robust API give you the flexibility to pick and choose what MAX will do and what parts you want to do yourself.

World-Class Services

With experienced, high quality autonomous engineers in short supply, you may want some help as you staff up your team. Perrone Robotics' Services Team is there to help any way you need it. We can fill in any gaps in expertise or we can implement an entire solution to your specs. And, of course, we provide world class support for our MAX platform. Help us help you, thats what we're here for!

Brakes: If a vehicle is equipped with dynamic stability control then software control of the brakes is possible. Dynamic stability control incorporates all the needed pieces to operate the brakes without driver input. The base software will not incorporate software brake control and will require hacking to incorporate the feature. If a vehicle does not have dynamic stability control it will need a third party system that can press the brake pedal.

Throttle: With the incorporation of throttle by wire the task has become far easier. There are provisions for accepting commands to control the throttle for diagnostic purposes. The latency can vary among systems. It may be necessary to hack the software to incorporate a direct bridge to the throttle commands. If the vehicle does not have throttle by wire it may be possible to use cruise control to substitute. Cruise controls operation at low speed and low throttle angle tends to be unstable and jittery. I would recommend installing a third party actuator.

Steering: If a vehicle has electric power steering then it may be possible to have software controlled steering. These systems measure the torque from the steering wheel and then apply the same torque but in the opposite direction for a net torque of zero. They incorporate a steering angle sensor. As with just about everything else hacking the software would be required. If the vehicle does not have electric power steering (hydro electric does not count) the a third party actuator would be required.

Shifter: Many cars now incorporate fully electronic transmission controls. These would be totally software controllable. Other transmissions have electronic control but still retain a physical shifter. The physical shifter incorporates a connection to the transmission to operate the parking paw. In this and all other cases a third party actuator would be required to operate the shifter.

The 'software' loop is described below.

Capture Image: The software captures the image from the webcam using classes and methods available in the java media framework.
Filter Colour: Then, the captured image is put through a simple colour filter - the orange stickers remain orange, everything else is changed to black.
Dilate and Shrink: In order to coalesce the edges of the image of each sticker, the orange part of the image is dilated (black pixels next to orange ones are changed to orange), then shrunk (orange pixels near black ones are changed to black). This ensures that a stray pixel near the edge of an image of a sticker is not counted as a very small sticker.
Detect Regions: Using a simple region-filling algorithm, the orange pixels are collected into groups, each group (hopefully) representing one sticker.
Apply Geometry: The centre and size of each group is measured. The large one is assumed to be the goal, the other five to be the four corners and the front of the car. From this, the software finds the distance and angle from car to goal, and the orientation of the car. The software doesn't bother with real-world coordinates, it measures everything in pixels.
Decide Strategy: Knowing the relative positions of the car and goal, the software applies a set of rules to decide what to do. An example might be if distance is LARGE and angle is between -5 to 5, then move straight forward.
Drive! Once the decision is made, the appropriate commands are sent to the interface board. The software waits for a reasonable amount of time, captures another webcam image, and the software loop begins again.









