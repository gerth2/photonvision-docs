Simulating Aiming and Getting in Range
======================================

Knowledge and Equipment Needed
-----------------------------------------------

- Everything required in :ref:`Combining Aiming and Getting in Range <docs/programming/examples/aimandrange:Knowledge and Equipment Needed>`.

Code
-------

Full code may be found in the PhotonLib example repository (`Java <https://github.com/PhotonVision/photonlib-examples/tree/master/java/sim-aim-and-range TODO FIX ME>`).

The previous examples show how to run PhotonVision on a real robot, with a physical robot drivetrain moving around and interacting with the software.

This example builds upon that, adding support for simulating robot motion and incorporating that motion into a :code:`SimPhotonCamera`. This allows you to test control algorithms on your development computer, without requiring access to a real robot.


.. tabs::

  .. group-tab:: Java

    .. remoteliteralinclude:: https://raw.githubusercontent.com/PhotonVision/photonlib-examples/main/java/aim-and-range/src/main/java/frc/robot/Robot.java
      :language: java
      :linenos:

  .. group-tab:: C++

          // Coming Soon!

