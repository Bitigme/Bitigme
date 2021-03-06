### Hi there 👋

<!--
**Bitigme/Bitigme** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
hi, i am trying to use your repositories but i got an error like this. I am currently working on a project and looking forward to your help with "stay filter" and "opencv". Thanks.

If you want to help contact: abdullahtatass26@gmail.com





error message : 

Traceback (most recent call last):
  File "C:/Users/dikol/Documents/YOLO/ULGEN/Simple-Online-Realtime-Tracker-master/main.py", line 90, in <module>
    matched_id,unmatched_tracker,unmatched_detector=hungarian_method(x_box,z_box)
  File "C:/Users/dikol/Documents/YOLO/ULGEN/Simple-Online-Realtime-Tracker-master/main.py", line 56, in hungarian_method
    if(iou_mat[m[0],m[1]]<iou_threshold):
IndexError: index 0 is out of bounds for axis 0 with size 0
tracker length: 0 detector length: 0

error message code : 
	for m in matched_id:
		if(iou_mat[m[0],m[1]]<iou_threshold):
			unmatched_tracker.append(m[0])
			unmatched_detector.append(m[1])
      
   --> I tried to run it by removing the error message code, the video stops as soon as it is detected.
   --> The number of objects tried to be detected is 1.
   
   ![sorun](https://user-images.githubusercontent.com/51065516/110212960-e8cb9f00-7eae-11eb-93a9-5c7ba7e1c996.PNG)

