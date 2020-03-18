=========================
Rookie Mistakes: Building
=========================
.. image:: images/building.png
    :width: 100%

2 Motor Drivetrain → 4 Motor Drivetrain
=======================================
In general, it is not recommended for teams to use 2 motors on the drivetrain,
but instead use 4.
This is mainly due to the added power and increased acceleration 4 motors
provide.
Typically, top speed is determined by the gear ratio and the motor
specifications, not the number of motors.
**However**, acceleration is affected by the number of motors,
and as FTC robots need to change direction and accelerate numerous times per
match, slow acceleration has a significant adverse effect on the
competitiveness of the robot.
In addition, 2 motor robots may struggle to get over obstacles or climb up
ramps, due to less power.
Typically, it is always possible to build a competitive robot with 4 motors
allocated to drivetrain, and 4 motors to other mechanisms,
so there should be no reason to skimp on drivetrain motors.

Pushbot → Mecanum, 6WD, Other Recommended Drivetrains
=====================================================
The pushbot drivetrain,
commonly built by first-year teams using the FIRST-provided guides,
should not be used as a competitive drivetrain.
We do recommend teams who have purchased the Tetrix kit to build it for
educational purposes only -
that is, to get familiarized with the parts and basic building principles using
a channel-based kit.
However, we do not advise that teams use that pushbot at a competition due to
its many flaws.
The first major flaw is that the pushbot is powered by 2 motors,
and as stated above, there isn’t a reason to stay with 2 motors on drivetrain.
Secondly, the pushbot has poor top speed and turning ability, given that the
gear ratio (40:1 on 4 inch wheels) is half the speed that many teams use.
Thirdly, it is not advisable to use direct drive.
However, most if not all of these problems will be solved by using a four-motor
drivetrain such as the ones recommended in the Drivetrain guide (Mecanum, 6WD).
Therefore, it is recommended for teams to refer to the
:doc:`Drivetrain <../robot-design/drivetrains/index>` section and
see which drivetrain would fit best for their overall game strategy.

Passive Intake/Claw → Active Intake
===================================
Active intakes (ones with continuous rotational motion)
should always be prioritized over passive intakes and grippers because active
intakes are much more efficient and effective in picking up common game
elements such as balls, cubes, rectangular prisms, etc.
The exception is that a claw should be used for irregularly shaped objects that
would be impossible to control via intake; for example, the relic in Relic
Recovery.
Intakes have two major advantages over claws -
the first being that intakes can control multiple game elements at a time, and
the second being that intakes are indiscriminate at picking up objects,
making them much more efficient.
Claws can only pick up one object at a time, and the driver needs to aim the
claw at that specific object to grab it.
With an intake, the driver does not need to focus on one game element -
instead; intakes will just pick up anything in its path, if designed properly.
Claws are also prone to breakage, and thus suffer to defensive robots.
They are also generally more fragile than intakes.
Therefore, active intakes are as a result much more efficient than claws.
Nearly every competitive robot from past years have used active intakes to
great effect, so there is plenty of precedent to follow.

Spur Gear Gearboxes → Planetary Gearboxes
=========================================
Note: Spur gear gearboxes are fine for most applications for a rookie team.
We are not advocating necessarily having to upgrade to planetary motors,
but there are some advantages which may become useful in more advanced
use cases such as high-load systems.
Spur gear gearboxes have inherent disadvantages to planetary gearboxes.
Spur gear gearboxes should not be used in high-load situations,
primarily because the gears can strip and destroy the gearbox.
An example would be a drivetrain that has to change directions repeatedly and
quickly.
Planetary gearboxes are much better suited for drivetrain and arms,
due to the configuration of the sun and planet gears.
In addition, spur gear gearboxes are prone to shock loads; therefore,
direct drive is not advisable on drivetrains.
Refer to the Motor guide for more complete information on gearboxes.
**This refers to using spur gear gearboxes which are attached directly to the
pinion gear of the motor.
It does not mean external ratios outside of the motor gearbox,
which will always be in a spur gear configuration.**

Single/multi axis arm → Linear extension
=========================================
Teams are generally advised to stay away from arms and move in the direction of
linear slides, primarily due to the issue of complexity.
This is because arms typically are less effective than linear extensions and
are harder to implement properly.
Arms require a high gear ratio,
which usually in turn will require an expensive gearbox (e.g.
`VersaPlanetary <https://www.vexrobotics.com/versaplanetary.html>`_)
that teams on a tight budget may not want to invest in.
However, there are more inexpensive options such as the REV UltraPlanetary
motor to consider.
Furthermore, arms must be supported extremely well to bear the torque that the
motor provides. A poorly supported and/or constructed arm will cause the driver
needless pain as it is exceedingly difficult to line up an arm that constantly
shakes.
In contrast, linear extensions do not need to worry about gear ratios and
gearboxes.
They can be optimized to be more efficient than arms, and typically are more
precise, as linear motion is easier to control than angular motion.
Furthermore, linear slides can have more extension than arms, with some
reaching over 3-4 feet in length.
