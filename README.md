# Python_Tutorial
> #### This is a series of python tutorial which includes many types of apps and different logic implemented programs.

-- -- 
<br>

## RPS GAME
> A simple python project where we are going to build the RPS game using PYGAME module.
-- -- 
<br>

## Screen Recorder
### Basic App
* [ ] Create a new python file
* [ ] Install cv2, numpy and pyautogui
```python
# Installation Commands
pip install python-opencv
pip install numpy
pip install pyautogui
 ```
* [ ] Import cv2, numpy and pyautogui
* [ ] Initialize pyautogui to take screenshot
* [ ] Create a video writer object to write frames into file
* [ ] Create a loop and start taking screeshots of frames in specified time interval
* [ ] Finally close the video writer object

### GUI App
> #### Implementing a GUI app for screen recorder in python using TKINTER library

* [ ] Import TKINTER library
* [ ] Create a instance of tkinter app
* [ ] Create a main loop for the app to run 
	* [ ] Create a text box to take the file name
	* [ ] Create start and stop button
	* [ ] Start recording function
		* [ ] Create a video writer object
		* [ ] Check for the existence of file name
		* [ ] If filename is null show alert else start recording each frame
			* [ ] save each frame to the file using video writer object
	* [ ] Stop Recording function
		* [ ] Close the video writer object
		* [ ] Close the app