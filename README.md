### EX NO : 01
### DATE  : 
# <p align="center">Rotating the Gaming Object</p>

## Aim:
To develop a 3D application for rotating the gaming objects in unity.
## Algorithm:
### Step 1:
&emsp;Start
### Step 2:
1. Click File -> Scene -> Select the scene -> Save as-> New folder(Scenes)-> File name (Exp1)
### Step 3:
1. Click Hierarchy -> 3DObject -> Cylinder
2. Hierarchy -> 3DObject -> Capsule
3. Hierarchy -> 3DObject -> Text
4. Hierarchy -> Effects -> Particle system
### Step 4:
1. Create a folder in project and name as Materials
2. Material folder -> Create -> Material (Name: Capsule)
3. Inspector ->Surface Inputs ->BaseMAp (Choose the color)
4. Drag the Cylinder to the plane and release the mouse


### Step 5:
1. Click Hierarchy -> DirectionalLight
2. Inspector -> Change the color to white (255,255,255)

### Step 6:
&emsp;Create a folder name Coding and create a C# file to add the coding in it.

### Step 7:
&emsp;To add our C# Script file to our selected object, click on the C# Script file and drag it to our selected objects in the Hierarchy window nad run the application.

### Step 8:
&emsp;Stop
## Program:
Developed By: **Virgil Jovita.A**
<br/>
Register Number: **212221240062**
### Rotate object(Capsule):
```C#
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class prog1 : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        transform.RotateAround(Vector3.right, Vector3.down, 90 * Time.deltaTime);
    }
}
```
### Rotate object(Cylinder):
```C#
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class prog2 : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        transform.RotateAround(Vector3.left, Vector3.up, 120 * Time.deltaTime);
    }
}
```
## Output:
![Out](https://user-images.githubusercontent.com/93427017/226107047-98b87971-1927-45f6-b557-80d9e26be55b.jpeg)

https://user-images.githubusercontent.com/93427017/226107106-e232748a-774f-4f1d-a7be-69a594f0aff5.mp4


## Result:
Thus a 3D application for rotating the gaming objects in unity is developed successfully.
