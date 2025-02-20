This is a portscanner I use for project boxes

My focus for this was to have threading, so you can set the threads to scan multiple ports simultaneously because it feels a bit long sometimes. Another focus was on clear output so I could set it and forget it and then check it while working on other things. It's also important to have banners added, so I put that in. I tried to do some error handling, it went -ok.

to start use: python portscanner.py , IE: python portscanner.py 192.168.1.1 20 80

Features:

You can adjust the number of threads by modifying NUM_THREADS variable.

The logic with the banner grabbing can be pushed to more protocols or look for specific service types.
