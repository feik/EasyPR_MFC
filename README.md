# EasyPR
EasyPR is an open source Chinese license plate recognition system. It aims to be Easy, Flexible, and Accurate. EasyPR based on openCV, you can transplant to all the platforms that opencv support. The repository of EasyPR is https://github.com/liuruoze/EasyPR, which is an excellent example of learning openCV. Thanks very much for the team of EasyPR!

# update
EasyPR has updated to 1.6alpha version. EasyPR_MFC update according to the 1.6alpha version of EasyPR.

# EasyPR_MFC
EasyPR comes with the demo based on win32 console, It's inconvenient to test one specified picture. So I created the EasyPR_MFC, which based on VS2013-x64 and opencv3.0. The functions of EasyPR_MFC is as follows:
## Single Test:  test one picture at a time
* The picture to be recognized could be specified by a button;
* The source picture and the identified result could show on the interface;
* The license plate recognition process and the middle process can be displayed in the top-left of source picture. 
![Single Test interface](http://livezingy.qiniudn.com/201608/easyPR_MFC.png)

## Batch Test:  test all pictures in the specified folder.
* The folder to be recognized could be specified by a button;
* The file name and recognise result, the time of plate detect, get plate color and char recognise could be show in a list.
![Batch Test interface](http://livezingy.qiniudn.com/201609/opencv/CMSER_Detect.png)

welcome to visit http://livezingy.com/batchtest-of-easypr/ for more information about EasyPR_MFC!
