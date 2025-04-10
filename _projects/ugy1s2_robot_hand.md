---
name: Robot Hand - Design for Manufacture
time_frame: Fall 2019
institution: Olin College of Engineering
---
For my Design for Manufacture final project, we (a team of five) were tasked with redesigning a robot hand (first image, first row) to be more cost-effective, easier to manufacture and assemble, and to overall have a less clunky design. Following this, we were to actualize our design into a working robot hand that could interface with a UR5 robot arm.

<div class="oohbaby">
  <img class="triplet myImages" id="myImg" src="/imgs/dfm_initial.PNG">
  <img class="triplet myImages" id="myImg" src="/imgs/dfm_proto2.png">
  <img class="triplet myImages" id="myImg" src="/imgs/dfm_render.png">
</div>

We went through several design iterations before reaching a final design to begin fabricating, one of which is shown above (second image and third images, first row). Our redesign of the hand notably uses a single motor to drive the transmission, has no parts that protrude from the main body of the hand, maintains the prior grip strength and extends the grip width of the original design, and has easily accessible electronics and removal from the wrist of the UR5. We also reduced the bill of materials for the redesigned hand from approximately $1600 (original) to $417.38.

<div class="oohbaby">
  <img class="triplet myImages" id="myImg" src="/imgs/dfm_unassembled.jpg">
  <img class="triplet myImages" id="myImg" src="/imgs/dfm_housing.png">
  <img class="triplet myImages" id="myImg" src="/imgs/dfm_full_assembly.jpg">
</div>

One of our goals was to primarily use COTS parts, unless we could achieve meaningful cost-reduction or specific functionality through custom designed parts. For these custom parts, we made use of waterjet, mill, casting, and TIG welding techniques. We prioritized simple machining operations by mainly using the mill to drill and tap holes, using the waterjet to do most of the heavy lifting. The required welding occurs between the aluminum center column and an adapter plate that mounts to the main transmission mounting plate.

The fingers of the hand are cast out of urethane rubber and ONYX. The urethane rubber gives the fingers compliance, offering an additional safety measure should the robot arm accidentally drive the hand into a surface (a common problem, we're told).

The housing is a snap-fit shell and is easily removable, giving easy access to the electronics.

Below is a video of an initial test run of our hand.

<div class="video">
  <iframe width="560" height="315" margin="auto" src="https://www.youtube.com/embed/0-3BCeAxWb4?rel=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

The CAD for this project was done in Autodesk Fusion 360.

<button class="prev" onclick="window.location.href = '/projects/ugy1s1_fairness_machine_learning.html';"> < Previous Project</button><button class="next" onclick="window.location.href = '/projects/ugy3s1_community_food_assemblies.html';">Next Project > </button>
