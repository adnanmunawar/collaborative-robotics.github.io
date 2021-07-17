<div align="center"> <h2> Toward Autonomous Suturing Using MOPS: A Modular and Open Platform for Surgical Robotics Research </h2> </div>

<div align="center"> <h4>Kim L. Schwaner(1), Inigo Iturrate(1), Jakob K. H. Andersen(1), Christian R. Dam(1), Pernille T. Jensen(2) and Thiusius R. Savarimuthu1(1) </h4> </div>

<div align="center"> <h4>(1) SDU Robotics, The Maersk Mc-Kinney Moller Institute, Faculty of Engineering, University of Southern Denmark, 5230 Odense, Denmark </h4> </div>
<div align="center"> <h4>(2) Department of Gynaecology and Obstetrics, Aarhus University Hospital, 8200 Aarhus, Denmark </h4> </div>

In an effort to evaluate methods for automating tasks in robotic minimally invasive surgery, we have developed MOPS - a platform for surgical robotics research. MOPS provides hardware and software components for turning common industrial robot arms into manipulators for a surgical robot system. Hardware includes adapters for mounting and actuating different types of standard surgical instruments. Software components are implemented using ROS in a modular fashion to make them reusable for different types of hardware. We present our reference MOPS-system comprised of two industrial robot arms with surgical instruments, a stereo camera rig and a simple operator console for teleoperating the manipulators. We apply our system to first demonstrate a bi-manual suturing task via teleoperation and to subsequently perform said task autonomously. The suturing task includes needle pick-up, insertion, re-grasping and hand-over sub-tasks. Primitive actions required for each sub-task are learned from a single human demonstration and encoded in an action library. We use stereo vision to estimate the 6 DOF suture needle pose and needle insertion points in order to close the control loop and make possible generalization to differing initial conditions. The suturing task is shown to generalize to different initial conditions with a full task (up to and including needle hand-over) success rate of 36%, mean sub-task success rate of 75% and mean needle insertion error of 3.3mm over the course of 46 trial task executions at human speed.