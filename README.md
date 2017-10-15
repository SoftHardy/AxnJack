# AxnJack
The game was written in Unity3D. The game has an added functinality of VR. You can add your VR headset to move left or right with the help of TrinusVR. You will be needing a phone more than Android 6.0 or iOS 7.


![111111](https://user-images.githubusercontent.com/32539405/31584641-f48a9648-b1cf-11e7-9afe-7869f0558fc7.png)
![1111111](https://user-images.githubusercontent.com/32539405/31584642-f4d5aaca-b1cf-11e7-8aa6-b7b2f2d857e8.png)
![1](https://user-images.githubusercontent.com/32539405/31584643-f513b842-b1cf-11e7-95c9-89c4948d5b7c.png)
![11](https://user-images.githubusercontent.com/32539405/31584644-f551cfe2-b1cf-11e7-8763-1f44975fc7d6.png)
![111](https://user-images.githubusercontent.com/32539405/31584645-f58f8792-b1cf-11e7-9812-85fe5f98e31b.png)
![1111](https://user-images.githubusercontent.com/32539405/31584647-f5cc5550-b1cf-11e7-80d2-b2d0b1ff70d0.png)
![11111](https://user-images.githubusercontent.com/32539405/31584648-f60cb140-b1cf-11e7-8a8c-4d2dc5c383a2.png)


Ansal University

School of Engineering and Technology



FPS Game for Windows/Mac_OS
AxnJack



A Report of Mid Term Major Project executed by 


Chandraveer Singh



in Partial Fulfillment of Continuous Assessment of

Degree Requirements as per AU Syllabus for the award of 


Bachelor of Technology (Computer Science Engineering)
Batch of 2012-16 


in the Major Project Class for 

IV Year, VIII Semester, B.Tech. Students 



 

March 2016

Ansal University

School of Engineering and Technology



FPS Gaming for Windows/Mac_OS
AxnJack



A Report of a Mid Term Major Project executed by 



Chandraveer Singh



in Partial Fulfillment of Continuous Assessment of

Degree Requirements as per AU Syllabus for the award of 


Bachelor of Technology (Computer Science Engineering)
Batch of 2012-16 


in the Major Project Class for 

IV Year, VIII Semester, B.Tech. Students 

 

March 2016

































SYNOPSIS




The primary objective of the game is for the player to eliminate all the bots present on the level. Throughout the level, there are various items placed on different locations where player can pick up and use to aid their way on the level. Our game is a first person shooter game. Commencing from the real life-like graphics, it consists of enemy bots and a very user friendly UI.
In the game, player will be playing on various levels consisting of enemy bots, weapons and other assets such as ammo, powerups, health packs, etc.

Characters: Player, AI Enabled Enemy Bots, 
Items: Weapons and their Ammo, Health Packs


The game is a 3D single player first-person shooter game creating using Javascript in Unity3D game engine. The aim of this document is to describe how the problem was analyzed and developed.

Tools USED: Unity3D game engine
                       Microsoft Visual Studio 2015
                     Blender










ACKNOWLEDGMENTS




I have taken efforts in this project. However, it would not have been possible without the kind support and help of many individuals and organizations. I would like to extend my sincere thanks to all of them.
I am highly indebted to Mrs. Pramneet Kaur for her guidance and constant supervision as well as for providing necessary information regarding the project & also for her support in completing the project.

I would like to express my special gratitude towards Internet community at Unity development Forum for their kind co-operation and encouragement which help me in completion of this project.

I would like to express my special gratitude and thanks to industry persons for giving me such attention and time.
















TABLE OF CONTENTS

											Page No. 

Synopsis										i

Acknowledgments									ii


1.	Introduction                                                                                           1
1.1	Background
1.2	 Project Objective and Deliverables 									

2. Technical Summary							            2
	

3. Methodology								            3	
	3.1. Proposed Development Process

4. Discussions									 4
	4.1. What Went Right
	4.2. What Went Wrong

5. Conclusions									 6

6. Snapshots                                                                                  		 7

7. Future Scope/Further Development                                                         12

References									           13

Bibliography									           14






1.	INTRODUCTION




“AxnJack” is a 3D FPS game with AI enabled bots and machines trying hard to kill you. You have to survive!


1.1	Background 

The game industry has grown multifold in recent years. The reason of this growth can be stated that the game industry can appeal any user with different tastes. Unity Technologies realized the opportunities in this field and developed a new technology - Unity3D game development studio for game developers. The idea of developing game is new for me. As everyone knows, there are several types of computer games. First person shooter is one of the best-known game genres. A first-person game is a game which makes the player feel within the game world; as if the main character has the game camera fixed at his eyes. After the success of Doom which is accepted as the first FPS game, many companies took a crack at this type of game. Nowadays, the best seller game is a kind of first-person shooters. 

1.2	Project Objectives & Deliverables 

The purpose of the project is to design and implement a 3-dimensional game written in Javascript using Unity3D game development studio. The project includes a complete level of game with documentation. The level will include everything that should be available in a FPS game. The game will be a single-player. 





                                                                                                                    
2. TECHNICAL SUMMARY



System to be developed “AxnJack” is an action based 3D first-person shooter game where the player takes role of the main character to destroy enemies. The game is inspired from a science fiction movie “War of the Worlds” by Tom Cruise which tells the story of the last man in the world where entire humanity has been killed by alien machine bots. New and crowded community afraid of him and ones like him, is trying to destroy them. The only way to protect from them is to kill all of them. The gameplay is action-based with no strategic or role-playing elements; instead, the game entirely provides a rush of adrenaline. The only goal is to kill all enemies until even one is not left before they kill our hero(the character). The version in this project consists of one level. I will add upper levels in our future works. The game starts on an island, where the end begins. In addition, the game involves no checkpoints; the player will start the game at level entries. The player plays these levels from a first person view in a 3D environment. The player experiences the game world through the eyes of a main character. This makes one feel one is a part of the game. The abilities of our character as a player are walking and running in all four directions, jumping, using-reloading-changing weapons, and collecting the pickups(health pack). The game has a design with only single-player mode. The player starts the game with two weapons and certain number of ammo. Along the way one face off against certain number of enemies which depends on the type of sub-mode. The attack of enemies reduces the health primarily. The effect of damage varies depending on the type of attack. The enemies have the ability to use gun and shoot. However, the player can pick up the power-ups that increase health. The player has only one life. When his/her health reduces to zero or lower, one will die. When our main character dies, the player loses the game. If the player kills all the enemies before the health reduce to zero or lower, one wins the game.





3. METHODOLOGY



3.1 Proposed Development Process 

Even if one can prepare a well-thought-out design document, some features do not give the same effect in gameplay as on the paper. During implementation phase many features are added, removed or modified. Accordingly, one needs to make some modifications on game design and requirement analysis. Thus, one of the most suitable development methodologies for game development is iterative development process. Most of game developers have the same idea about the advantages of iterative development process for game developers.

 As it is known:

“The more times you iterate, the better your final game will be”. 

I prefer the iterative development process with specified milestones and deliverables for our project.








4. DISCUSSIONS



4.1 What went Right 

4.1.1 A Clear Vision
 
As Marcus Annaeus Seneca said, “If a man does not know what port he is steering for, no wind is favorable to him.” From the beginning, I have had a grand vision of what the game would be. This was possible for the following reasons. In game market, there exist a considerable number of FPS game samples. I had a chance to observe existing games. This was a good start to think about setting out the game. While informing the design of the game, I took notice of the common features of these games. While making decision about game genre, I thought with a trader brain. I followed best-seller lists and decided to create FPS game because of the successful sales chart. In the next steps, this decision has turned into an advantage. In addition, for the back story I inspired from the best-known science fiction movie. The gameplay was not enigma anymore. 
I know that the FPS lovers are not interested in back stories. Thus, keeping the game simple without overcharging the player with back stories. The lesson learned from this is that one cannot achieve the goals, if he does not know what they are. If one wants to create a game without any pain, one has to be clear about what to create. 

4.1.2 3D Models

Because of limited time, the design and creation of 3D models are out of scope of the project. I planned to use free ready-to-use 3D models in the project. At the beginning this was a nightmare. If I did not find suitable models, making a game would be a fantasy and accordingly the project would fail. Fortunately, I found the suitable models in unexpected short time. I selected models from free models on the various sites selling models. At the end of the project, I realized that while I think finding 3D models as a nightmare, it becomes a stage that gives rapid results and makes us very happy. 


5.2 What Went Wrong 

5.2.1 Limited Time

The main problem for the project was limited time. Although the project is small, I think that 63 days are not enough for implementation. Due to the fact that I had no game development experience, I had to do a considerable amount of research during implementation. This did lead to slow down the progress of implementation of the game. Fortunately, I did not come up against the case of unfinished implementation work. This situation resulted in just putting increasing stress and acting as if I had panic attacks during the entire implementation phase. I felt the impacts of limited time during not only implementation stage but also testing stage. 
























5. CONCLUSIONS



Despite the fact that I was involved in many projects up until now, this project was my first game development project. This was an unquestionably important experience. In the following section, I have mentioned about the lessons that I have learned during this project process. 
Having regard to the suggestions of the authors who wrote the articles about game development process, I decided to apply iterative development methodology to the project. Especially because of two reasons, I realized that this is a very fortune decision. I have faced with the first reason causing me think like that during the preparation of this document. At the beginning I had a very clear vision about what I wanted to implement. The game would roughly be a single player FPS game with a known back story inspired from a well-known movie, The second was during the testing process. As we know, the testing is an iterative process. Once the bugs are fixed, the testing has to be done repeatedly. In addition, while checking the test cases we realized that there existed some test cases missing. Accordingly, I went back and made some modifications and additions on Test Plan. Shortly, the chosen development methodology is the most suitable for the project without a shadow of a doubt.
At the end of the project, the other lesson that I have learned and think to apply to my future projects is making a good project plan, remaining true to this plan as possible and documenting everything I do. By doing this, whenever I have a problem I can go back and see what I did the last time I had a similar problem. There exist so many alternatives to examine in the game market because of intense interest of the people in FPS games. Therefore, it was a good start for me. 
My thought is “the more examples one has near at hands, the easier the implementation will be.” 



As a result, 8 weeks were full of new great experiences and these experiences that I have gained will help me in my upcoming projects. Finally, the idea of developing game that was a dream for me since my high school education became real and I have experienced the pride of doing such a thing at the end of such an education.







































SNAPSHOTS

(During game development)



 
Setting up the game environment





 
Adding the main character (our hero)


 
Setting up the cross-hair and GUI







 
Creating non-movable obstacles









 
Weapon switching








 
Defining the Hitpoints





 
Robot AI and waypoints for robots to walk







 
Ragdoll Setup


 
Ragdoll Animation





























Future Scope/Further Development


 





Perceived as the technology of the future, Augmented Reality is making its way in the market place by continuing to work with top brands and companies.
The numerous applications emerging from the steady development of ground-breaking Augmented Reality is transforming the way people see and learn from their surroundings, and is revolutionizing companies’business models. 
The game will be created over AR platform Vuforia by Qualcomm.








REFERENCES


(1)	Schreiber, Ian, “Level 2: Game Design / Iteration and Rapid Prototyping”, 02 July 2009. 02 June 2010,

(2)	March 2015, http://www.turbosquid.com/3d-models/zombie-maps-normal-maxfree/327193

(3)	March 2015, www.unity3d.com



































BIBLIOGRAPHY


(1)	www.youtube.com/awesometuts
(2)	www.udemy.com
(3)	http://gamelab.mit.edu/
(4)	http://store.steampowered.com/




































