Analyzing video-MEG
-------------------
Although the Helsinki VideoMEG Project records audio and video separately from the MEG data, it timestamps all the data streams, which allows aligning the all data to the common timeline.

Here are your options for analyzing the video-MEG:

  #. If you are writing Python scripts for analysing your data, you can use the libraries provided by the project for importing audio and video and synchronizing it to MEG traces.
  #. You can check out `mne-videobrowser <https://github.com/ttaiv/mne-videobrowser>`_ tool.
  #. If none of the above works for you, you can at least export the video and audio to the avi format so you can review them without the MEG traces. This can be done with the Python video-MEG analysis tools.
