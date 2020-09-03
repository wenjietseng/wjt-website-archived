---
layout: page
title: Experiments
permalink: /experiments/
---

## WELCOME to the User Study of FingerMapper!
Thank you for participating our study. First, I would introduce what FingerMapper does and how to interact with it. The next step would be the setup and instructions for the study. Please read all the information in part B carefully before you start the study since our study would be remote. Finally, sign up the consent form through the link in part C and download the apk. I will then send you the user number. Let's go!

## A. FingerMapper and the purpose of this Study
FingerMapper is a finger mapping technique that allows users to control arm interaction inside Virtual Reality (VR) using small finger motions.

### Four techniques
- Physical hand: the virtual hand is your physical hand, which is the one-to-one hand tracking.

<iframe width="560" height="315" src="https://www.youtube.com/embed/VZTEbDaKN6M" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- Raycasting: using a ray casting from your fingertip to select.

<iframe width="560" height="315" src="https://www.youtube.com/embed/C1O5Ngp2aAc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- Direct: the virtual arms would follow the direction of your index finger. The shape of your finger is mapped one-to-one to the bending and shape of your arm. You can control and bend the arms by simply bending your fingers.

<iframe width="560" height="315" src="https://www.youtube.com/embed/msqmXK2s9TI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- Attach: there is a ray casting through the direction of your index finger. Bending your index finger inwards can retract the virtual hand closer to your shoulder.

<iframe width="560" height="315" src="https://www.youtube.com/embed/jJP5CqXA3hw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Our goal: We would like to ask you to evaluate four techniques with two different target layouts. There will be eight combinations, each has 30 tasks. After completing each technique, there would be one questionnaire.

## B. Study Setup
Please follow the instruction to setup the study environment, thank you!

### B.1 Oculus Quest
- <a href="https://support.oculus.com/guardian/">Set guardian as stationary.</a>
- <a href="https://frl.nyu.edu/disable-guardian-on-the-oculus-quest/">Disable guardian in developer tab. The Quest has to be Developer Mode.</a>
- <a href="https://uploadvr.com/sideloading-quest-how-to/">Upload the apk by SideQuest</a>
- Download the apk (link)

### B.2 Space
- Find a chair and put it in the middle of an empty space.
- Remove all the possible obstructions around you.

### B.3 Body posture
**Important!!** Please keep the posture in (a) throughout the whole study and interaction (except for the one-to-one hand tracking condition)!! Try to remember to have your elbows always be in contact with your upper body. 

<img width="560" src="https://wenjietseng.github.io/images/technique-body.jpg">

### B.4 Body measurements
Measure the following body dimensions, as shown in the figure (b).
- arm span (the length from one end of an individual's arms (measured at the fingertips) to the other when raised parallel to the ground at shoulder height at a 90 degrees angle.)
- arm length (from the shouder to the wrist)
- index finger length (from the MCP joint to the fingertip)

### B.5 Reposition yourself using thumb-pinky pinch
At the beginning of entering VR, right before entering user number, please use the thumb-pinky pinch to reposition yourself.

<img width="560" src="https://wenjietseng.github.io/images/reposition.png">

### B.6 Adjust your body dimensions in VR
<iframe width="560" height="315" src="https://www.youtube.com/embed/vdy5CAuR06o" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Next, you need to adjust the body dimensions to what you just measured. Remember to check if you can reach all the targets. If you cannot reach all targets, please reduce the arm span a little bit and try again.

### B.7 Tasks
<iframe width="560" height="315" src="https://www.youtube.com/embed/_mWjunNRBuA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

1. Touch the white cube in front of you with the red pointer on your virtual hand (both hands can start the task).
2. Two spheres turn green. Check where they are.
3. Choose one of your arm to touch one of the green sphere. The order of green sphere doesn't matter. 
4. Once you touch the first green sphere (for example, with your left virtual hand), the green sphere you touched turns into blue.
5. Use the same arm that you touched with the first green sphere to touch the other green sphere as fast and correct as possible.
5. To have a succeed task, you have to use the SAME arm for both green spheres. A beep sound occurs when the task succeed.
6. For each condition, there is a practicing phase. Get 10 succeed tasks in practicing. You can also practice the task until you feel completely comfortable with the technique.
7. Touch the red cube to end practicing and start the formal study.

### B.8 Questionnaire
After finishing one technique (one mapping with two layouts), there would be a questionnaire. Please fill them up as shown in the video below.

<iframe width="560" height="315" src="https://www.youtube.com/embed/HBYe3ZpFeok" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### B.9 End! Send the data back
- There are three files in this directory of your Quest.

```
sdcard > android > data > com.DefaultCompany.FingerSaber >
file"UserNo"_frameLog.csv
file"UserNo"_questionnaire.csv
file"UserNo"_study.csv

For example: file20_frameLog.csv, file20_questionnaire.csv, file20_study.csv
```

- Zip them into `"UserNo".zip`
- <a href="https://www.dropbox.com/request/iPF583DXZ8FFwed0nJyv">Upload your `"UserNo".zip` to this LINK</a>


### Contact
- Please contact Wen-Jie Tseng (email: wen-jie.tseng@telecom-paris.fr) if you have any further questions, email me and let me know :).

## C. Consent form and start
- <a href="https://form.jotform.com/202294350144346">The LINK to the Consent Form</a>
- Once I received your consent form, I will send you the user number. 
- Download the apk (link)
- Follow the setup an instructions in part B

### Final remark
- There are four techniques to test: direct, attach, physical, and raycasting
- Please remember to keep your posture during direct, attach, and raycasting.
- Please check the green targets before you start to touch the first one

### Avoid tracking loss
- To avoid tracking issues with the Oculus Quest, we suggest that you use an open hand during interaction.
- Also, try not to occlude the physical hand. If there was occlusion, the tracking would break.s

<img width="560" src="https://wenjietseng.github.io/images/quest-hand-tracking-guidelines.png">
(from Oculus Quest)

### Links for the study
- <a href="https://form.jotform.com/202294350144346">The LINK to the Consent Form</a>
- <a href="https://www.dropbox.com/request/iPF583DXZ8FFwed0nJyv">Upload your `"UserNo".zip` to this LINK</a>