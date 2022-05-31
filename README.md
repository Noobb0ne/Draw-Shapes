# Draw-Shapes
Simple python programs to draw shaped
To prevent an error I have to add

!apt-get install -y xvfb

import os
os.system("Xvfb:1 -screen 0 720x720x16 &")
os.environ['DISPLAY'] = ":2.0"
