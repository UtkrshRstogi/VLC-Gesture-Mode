# VLC-Gesture-Mode

The purpose of this porject is to detect hand gestues in images and control the VLC media player. It is being done using OpenCV and not using Machine/Deep Learning. However, it is not as as accurate (backgrounds with similar color as that of skin can fool the detector). Also note that, this isn't really a "Hand detector". It is just an Object Detector, using color. You can play around and modify the code to detect other objects as well, pretty easily. 
The following VLC media source code consist the following gestures. 
	1. Palm Close -  Mute the audio
	2. Open Palm - Unmute the audio
	3. Two finger slide right - Forward
	4. Two finger slide left - Backward
	5. Palm Up- Volume raise
	6. Palm Down - Volume down
	7. I am also trying to include close the video and open the video getsture. We can also add pause and play getsure.
	
	

![Alt Text](sample.gif)

```sh
$ pip install -r requirements.txt
```
Install the addiotional requirements. The requirements.txt file is available in src folder.

The following has the idea of providing a seamless user experience to the user.

The src consists of the image classification codes. The VLC folder conssit of the updated source code of VLC with hand gesture controls. The following VLC media player wokrs on Mac and no other changes were made in it. Code with no changes are not uploaded.

Please check the documentation to setup and run the above.
