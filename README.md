# cs408a2
CS408-A2

YUPENG YANG 200388555


Github page: https://github.com/danielegendary/cs408a2

The "assignment2.unity file" is the output scene file. Hope you can open it properly.

Part1

Create an object name “object1” and use script file name “print” to print the position, rotation and keyframe value in the console window:
    
    void Awake()
    {
        // Create three cubes and place them close to the world space center.
        ob1 = GameObject.Find("object 1");
    }
    
    void Update()
    {  
       print("position: "+ transform.position+ "rotation: "+transform.rotation + "keyframe: "+Time.time);
    }

![image](https://user-images.githubusercontent.com/67968545/195736840-1cc695cc-f000-46c0-b9a2-4a472c53bfb0.png)

  
So This script file can be placed under any object to load their position and transform value, but I only used it on one object to demonstrate the effect.
Then animation file( end with.anim file) is created to store the animation of other objects
 
 ![11](https://user-images.githubusercontent.com/67968545/195736906-63da4a2a-8a9f-4488-b810-9bc28b4e9d1b.png)

Progress video:

https://user-images.githubusercontent.com/67968545/195737268-0e8d2fc5-3356-43a8-9217-3f36793b7786.mp4

https://user-images.githubusercontent.com/67968545/195737254-840ca9f6-38b3-4722-85d9-07680f663155.mp4



https://user-images.githubusercontent.com/67968545/195737264-b12fdb61-ea98-4673-a190-d16f2a6bd8c3.mp4



https://user-images.githubusercontent.com/67968545/195737266-ab42d6ac-c5c2-486d-8b92-6c5cf482e410.mp4


 
Creative Feature: Use UModeler to create individual model.

 ![tttt](https://user-images.githubusercontent.com/67968545/195736488-27826c98-de89-4e41-bd93-88f7172901e4.png)

Using Umodeler create a helicopter from sketch with animation.
![tttt1](https://user-images.githubusercontent.com/67968545/195736458-840e3aed-a608-43f8-90b0-7011e6b41087.png)

Final result:



https://user-images.githubusercontent.com/67968545/195737170-a1e8fb86-1673-4c01-971d-49cede097fe9.mp4


Cite:

Spider model Spider 
https://assetstore.unity.com/packages/3d/characters/animals/insects/spider-polygon-221108

UModeler Lite UModeler 
https://assetstore.unity.com/packages/tools/modeling/umodeler-lite-133081

Ground Texture pack 
https://assetstore.unity.com/packages/2d/textures-materials/floors/yughues-free-ground-materials-13001

