# Hadoop2.7-on-Windows
Binaries for Hadoop 2.7 built on Windows 7 64 bit

# Hadoop 2.x Windows Binaries


Windows Binaries specially built for Hadoop 2.7.6 (these Binaries should work for other verions of Hadoop2.x) These binaries were built on Windows 7 64 bit and also work with 32 bit systems.
I have not tested the binaries in Windows 10 setup. if anyone were able to test them, let me know :)
 

# How to Use

 Download the zip file of the binaries and follow the last steps (from video playhead 1:38 ) suggested in my youtube video.
 
# How to debug

  What to do when daemons shutdown or do not start:  

    Edit hadoop-env.bat, enable logging  and restart the daemons to see the errors. Mostly the errors are related to 
	configuration typos or due to missing of any one of the steps suggested in the video
	
# FAQs

1. Hadoop Daemons Start and stop. What might be the problem?
	Edit hadoop-env.bat, enable logging  and restart the daemons to see the actual errors.
    
