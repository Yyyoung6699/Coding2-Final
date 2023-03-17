# Coding2-Final
Github link：
https://github.com/Yyyoung6699/Coding2-Final

Video link：
https://ual.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=b04a2442-ebbd-4834-8eda-afc800390f1f

Helper functions for downloading images and for visualization.
FasterRCNN+InceptionResNet V2and ssd+mobilenet V2.
Run_detector is a function that detects the image.
I have provided three images, which are panda, bear and deer.
It takes some time to detect.
Panda, grizzly brown and deer are annotated.
Based on this I made some changes to the code.
I added a condition that I wanted it to help me pick out image with pandas and save them locally.
I was delayed because I realized that all the images could detect pandas. But they don't show up because the score is too small.
This is misleading the conditional judgment. So I also put conditions on detection scores.
I print the value of score, is 0.994.
This time it only gave me the image of panda and saved it for me.
The url of the image that passes the condition will be given to the subsequent code for stylization
