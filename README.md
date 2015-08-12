# RTQR
A simple real time QR and Bar code recognition using Python. This will connect to your webcam and constantly scan for any QR or bar codes. If one is detected, it'll translate it for you in the output.  

# Dependencies
Required ZBar, OpenCV, and PIL.
To install Zbar:
```brew install zbar```
*** If you get a segmentation error, follow this [guide] (http://stackoverflow.com/questions/21612908/zbar-python-crashes-on-import-osx-10-9-1). To apply the patch, download that version and install it.

To install OpenCV:
```brew tap homebrew/science```
```brew install opencv```

To install PIL:
```pip install PIL```

