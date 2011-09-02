.. Troy Straszheim's Blog @ Willow Garage documentation master file, created by
   sphinx-quickstart on Tue Aug 16 06:27:31 2011.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


.. image:: ecto_4x4.jpg
   :align: center
   :width: 33%

Ecto - a framework for perception
---------------------------------

Initially aimed at computer vision and perception research tasks, Ecto
is a hybrid C++/Python framework for organizing computations as
directed acyclic graphs of computing vertices connected by typed
edges.  These graphs are typically constructed via Python script and
executed in a single process (and possibly multiple threads) by
external schedulers.  The computing nodes are written in C++ against a
simple interface that naturally creates libraries of self-documenting,
scriptable components and smooths the path from prototyping to testing
to deployment.

Ecto itself is small, has minimal dependencies (C++, Boost, Python)
and works with or without OpenCV, PCL, and ROS in any combination.  We
believe that Ecto allows vision and perception researchers to express
their computational models in a natural fashion, obviating e.g. ROS
[#ROS]_ time synchronizers and ROS nodelets in most cases.

As of August 2011, Ecto is in its first beta release.  It is being
used by researchers at Willow Garage and in industry for prototype
applications of object capture and modelling, object recognition, pose
estimation and refinement, projector-based augmented reality and chess
playing.

.. rubric:: The latest tagged release of ecto is
            `amoeba-beta3 <releases/amoeba-beta3>`_


Releases
^^^^^^^^

`Documentation for checkpoints, betas and releases of ecto are
avaiable in this directory <releases>`_.


IRC
^^^

We're in channel ``#ecto`` on ``oftc.net``.  Use the client of your
choice or this `web client
<http://www.wsirc.com/?username=wsirc_******&server=irc.oftc.net%3A6667&channel=%23ecto&autojoin=true&color=%23C0C0C0&dark=false>`_


Buildbots
^^^^^^^^^

There are `buildbots <http://ecto.willowgarage.com:8010/waterfall>`_ working
round the clock to serve you.





.. rubric:: Notes

.. [#ROS] `Robot Operating System <http://www.ros.org>`_

