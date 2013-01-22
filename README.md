NCTOOLBOX
=========

Full instructions and documentation at:
http://code.google.com/p/nctoolbox/

We are in the progress of moving the project hosting here to github.com.

##Brief summary:

###Prequisites

Matlab R2008a+.  You can verify the version of Matlab by typing:
    
    
    version


Java 6+.  You can verify the version of Java used by Matlab by typing: 
    

    version('-java'). 


The version returned should start with 'Java 1.6'. If it starts with 'Java 1.5' you can try updating the Matlab JVM: http://www.mathworks.com/support/solutions/en/data/1-1812J/ or use the older nctoolbox-20091112 version of this toolbox.

###Setup

In Matlab, change to the nctoolbox directory. For example,
 

    cd ~/Documents/MATLAB/nctoolbox


Run the setup_nctoolbox.m function
 

    setup_nctoolbox


This sets up nctoolbox for the current Matlab session only. You will need to add the follwing lines to your startup.m file if you would like nctoolbox automatically when you start Matlab:


    % Edit "/Path/to/nctoolbox" to correct nctoolbox directory
    addpath("/Path/To/nctoolbox")
    setup_nctoolbox
      
###Demos

  * Demos that display basic functionality are in the 'demos' subdirectory.  These demos
     can fail if the machines serving the remote data access URLs are unavailable.
  * Contributed demos that display additional or specialized functionality are in 
     the demos/contrib directory.  Some of these depend on accessing remote sites for
     data that can be less reliable than the data URLs in the 'demos' directory.

