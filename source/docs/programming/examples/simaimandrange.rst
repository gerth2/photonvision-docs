Simulating Aiming and Getting in Range
======================================

Knowledge and Equipment Needed
-----------------------------------------------

- Everything required in :ref:`Combining Aiming and Getting in Range <docs/programming/examples/aimandrange:Knowledge and Equipment Needed>`.

Background
----------

Full code may be found in the PhotonLib example repository (:ref:`Java <https://github.com/PhotonVision/photonlib-examples/tree/master/java/sim-aim-and-range TODO FIX ME>`).

The previous examples show how to run PhotonVision on a real robot, with a physical robot drivetrain moving around and interacting with the software.

This example builds upon that, adding support for simulating robot motion and incorporating that motion into a :code:`SimVisionSystem`. This allows you to test control algorithms on your development computer, without requiring access to a real robot.

Walkthrough
-----------

First, in `Robot.java`, we add support to instantiate a new simulation-specific object and update it periodically. This logic only gets used while running in simulation:

.. tabs::

  .. group-tab:: Java

    .. remoteliteralinclude:: https://raw.githubusercontent.com/gerth2/photonvision/add-basic-sim/photonlib-java-examples/src/main/java/org/photonlib/examples/simaimandrange/Robot.java
      :language: java
      :lines: 109-123
      :linenos:
      :lineno-start: 109

  .. group-tab:: C++

          :code:`// Coming Soon!`


Then, we add in the implementation of our new `DrivetrainSim` class. 

Please reference the :ref:`WPILib documentation on doing drivetrain simulation <TODO LINK ME>`.

To support a :code:`SimVisionSystem`, we must take a few steps:

Defining the Simulated Vision System
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

First, we declare a new 

.. tabs::

  .. group-tab:: Java

    .. remoteliteralinclude:: https://raw.githubusercontent.com/gerth2/photonvision/add-basic-sim/photonlib-java-examples/src/main/java/org/photonlib/examples/simaimandrange/Robot.java
      :language: java
      :lines: 109-123
      :linenos:
      :lineno-start: 109

  .. group-tab:: C++

          :code:`// Coming Soon!`