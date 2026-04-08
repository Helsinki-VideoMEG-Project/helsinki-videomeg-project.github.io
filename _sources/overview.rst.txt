Project Overview
----------------
Helsinki VideoMEG Project is an open-source project that aims at providing any magnetoencephalography (MEG) laboratory with a complete set of tools for adding synchronized audio and video recording to their MEG acquisition.

.. note::

   Contrary to what the name of the project might suggest, the tools provided by the Helsinki VideoMEG Project are not limited to MEG. They can be used in a wide variety of experimental setups, including EEG, eye-tracking, and other types of experiments that require synchronized video recording. The only requirement is that the experimental setup has a trigger input that can be connected to the parallel port output of the video recording computer for synchronization purposes.

   Essentially, the Helsinki VideoMEG Project allows you to build your own standalone audio/video recording system that uses machine vision cameras, records multiple video and audio streams, allows flexible audio routing, and outputs a timing signal that can be used for synchronization with other devices.

   Nevertheless, this documentation assumes that you are using the tools provided by the Helsinki VideoMEG Project in a MEG laboratory. Modifications to the setup to use with something other than MEG should be pretty straightforward. 

.. note::

    This is a further development of the original Helsinki VideoMEG Project that was reported in `Zhdanov et al. 2018 <https://doi.org/10.1016/j.mex.2018.01.002>`_. The archived version of the original repo is available `here <https://github.com/Helsinki-VideoMEG-Project/Old_VideoMEG>`_.

To start your video-MEG recordings, you need to:
  #. Assemble the video-recording hardware
  #. Install the video-recording software
  #. Do the actual recording: record MEG, video, and audio datastreams simultaneously
  #. Analyze the results: synchronize all the recorded datastreams and analyze them together


