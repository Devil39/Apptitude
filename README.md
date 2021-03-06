# **Cura**

(_latin for to take care or to pay attention to)_

## App Preview

![Screen1](https://github.com/Devil39/Apptitude/blob/master/assets/Screen1.png)    ![Screen2](https://github.com/Devil39/Apptitude/blob/master/assets/Screen2.png)
![Screen3](https://github.com/Devil39/Apptitude/blob/master/assets/Screen3.png)    ![Screen4](https://github.com/Devil39/Apptitude/blob/master/assets/Screen4.png)

### NOTE
Biometric has been bypassed for now, if you want to verify its working, its just shifting Navigtor push into if statement, we had to take this move, because I do not have a mobile to test it upon, but as I have used it before in my internship, I know the code works 100%, as said before, you can defenitely verify it by pushing it in if, also you will get a toast stating the status, hence proving its working.

### ADHD


Cura is a task curating and tracking platform to help children suffering from ADHD, Attention deficit hyperactivity disorder. ADHD mainly affects children severely below the age of 12. ADHD shows its signs in children in ages as young as three years old. ADHD is often accompanied with or potentially leads to autism or dementia in children as well.



 ADHD has broadly 4 symptoms – short attention spans or unable to focus, impulsive behavior, hyperactivity or fidgetiness, poor management skills or decision making.



Most children as they grow up loose most symptoms except maybe their lack of focus or poor decision making for which various task management apps now exist.


### Value Proposition


Cura is a platform to help tackle all 4 broad symptoms and collect progress reports to help better improve their treatment. The app is targeted towards parents having children in the age group of 6-8. Cura stands unique as most of the present apps focus on engagement of kids through their platform. Whereas Cura is an that not only integrates learning through engagement but also helps children improve in their daily activities and increase their productivity.


### Features


- Daily task generator: A daily task generator generates a maximum of 5 tasks a day ranging from simple reminders like eating fruits, watching certain movies to giving challenges. The tasks are curated keeping in mind patterns and behavior seen in children suffering from ADHD.

- Reward system: The app also generates certain rewards upon completion of all tasks in a given day. In children suffering from ADHD it is seen that they pickup up things faster or try to imitate patters if they get rewards for it

- Streaks: For every reward collected a streak in maintained which breaks if on any day tasks are left incomplete. This helps in realizing a child&#39;s attention span, tasks that they may not like and other such patterns.

- Daily challenges: Daily challenges include finding or recognition of certain objects through questions. For eg: We show a picture of a pen and ask the child to take a picture of 5+2 pens. Children with ADHD are restless in nature. This feature no only helps turn their restlessness into something productive but also at the same time judges the child&#39;s recognition and cognitive abilities (Dementia and Autism)

- Word of the day: By showing pictures of objects we increase the child&#39;s engagement in learning as well as ensuring to improve their recognition capabilities.

- Timer: A timer is set in the background which clocks the amount of time required for a child to complete a task. This is done again to note the attention span of the child.

- Record: The records section allows for one to go through the previous tasks and also help find out certain pattern or dislikes.



### Challenges faced:


- Researching od ADHD and curating tasks

- Understanding patterns



### Accomplishments:


- Integration of Biometric authorization to help reflect patient doctor privacy

- Integration of Firbase ML toolkit- Labelling of images

- Using Rx library- Rx is great at handling streaming data, here in our project we have leveraged it with the help of behaviour subject utiliy provided by Rx library.

- APIs used: http://glyffix.com/api/Image?word={word}, https://www.wordsapi.com/, https://random-word-api.herokuapp.com/home 


### Steps to Run the app:
#### Getting Started

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

To start the project you need to do two things:
- Add google-services.json
- Add a keys.js file in **lib/** folder with **Web Client ID** of your firebase project and you are ready to go. Ensure its a class with name Keys and static const memebers.


