# Command-F
Project Proposal
16423 - Designing Computer Vision Apps Cheng-Yang Liu, chengyal
Title: Command ⌘ F (Cheng-Yang Liu, andrew id: chengyal)

Summary: In this project we plan on implementing Convolutional Neural Network (CNN) for real-time scene text localization and recognition on an iOS devise. We plan on employing CAFFE or other packages for learning scene text models. Also, on  OpenGL ES for speeding up feature preprocessing stage (such as Canny edge detection and contour finder segmentation). Our goal is to realize scene text recognition on mobile devises, in terms of both accuracy and real-time.

Background: In this project, we are going to bring the function in personal computers, Command ⌘ F, to real-world. Have you ever lost in a messy menu where you could not find the food you were craving for; or a street of signboards where you could hardly find the right store to shop? The motivation of this app is trying to solve these kind problems by moving your mobile phone around the text region or even the whole environment, and detect, recognize and track the desired scene text, in order to notify the user. With the flourishing of mobile devises, smartphones bring personal computing (portable) closer to the human. Furthermore, the high-speed camera on the mobile devise allows people to connect the digital world to the real-world. Therefore the function “Command F”, which is use to search a specific context in a machine, could be brought out to real world.

The Challenge: In order to get a more accurate recognition, CNN has been brought on board recently to solve a scene text recognition problem. The main challenge of running CNN on a mobile devise is the memory issue, both computational memory and trained model storing memory. One solution for this problem could be a back-end server to process and recognize the images. However, the downside of this solution is the network latency and network connection. On the other hand, we can solve the problem by reducing the complexity of CNN architecture. But the trade off of this would be accuracy. Then this becomes a “Chicken-Egg” problem.

Goals & Deliverables:
1. CNN recognition on food menu images on mobile. This is a task with simple images (lighting conditions, variable fonts, orientations, background noise, and imaging distortions) which the output of preprocessing might have a great job on it.
2. CNN recognition on street signboard images on mobile. The task become harder with the images become complex. However, with larger training dataset, we might able to solve this problem. To get a larger training dataset, we might runout of memory in mobile devise.
3. Real-time CNN recognition and tracking on food menu video on mobile. Similar problem as 1, but the computational time is take into account. Same as previous solution, due to the simple visual background, we are highly possible to solve this problem.
4. Real-time CNN recognition and tracking on street signboard video on mobile. This is the hardest goal, which require high accuracy and memory. One solution might be solving the problem with offline trained model. 
There are two ways to validate our method. First, we can test our application on a standard dataset, such as ICDAR dataset. Second, we can demo our method on a real food menu or video street signboard view.

Schedule:
(11/7~11/13) Preprocessing: feature extraction.
(11/14~11/20) CNN offline training
(11/21~11/27) Experiment
(11/28~12/4) Evaluation
(12/5~12/11) Warp-up and prepare for presentations 
