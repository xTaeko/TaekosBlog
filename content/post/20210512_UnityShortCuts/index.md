---
title: "Unity Shortcuts"
date: 2021-05-12T17:54:08+01:00
draft: true
slug: "unity_shortcuts"
---

We all know these people, they sit in front of a computer and it seems like they just use some kind of darf magic. New windows open, tools changes within seconds, they search for things without even touching the mouse. And after a blink they changed so much and you have no idea what happend. 

This magic is called the usage of shortcuts. And like everything in the IT in general, you first need to know they exists and after that it's easy to use them or search for them in case you forgot it. 

Unity have a lot of useful shortcuts and today I want to show you some of them. I discovered recently, a lot of people don't know a lot of "common" shortcuts, so this post will cover these too. 

At the end I hope you can practice the magic of shortcuts yourself. Before getting started... Almost every shortcut I tell you about are also written down in Unity itself and you can edit them if you want to have it different. 
Just go to `Edit -> Shortcuts...` in your Unity Window. But now, lets get started!


## Object Tools
Maybe one of the first things you came across while using Unity are these object tools.

{{< image src="./Objects_Tools.png" alt="Image of Object Tools in Unity" position="center">}}



There are different ways to manipulate an object in a scene. First of all you can set the position, rotation and scale in the Transform Component. But sometimes you don't know the values you want. Maybe you want to try things out to get a feeling for the values. 

In this case you can switch between these tools. With each of them you can manipulate the object by dragging an arrow or something else around. This is really quick and it can be useful to quickly switch between the Move and Rotation Tool for example. Especially if you're not a real fan of the combination tool, where you can do everything at the same time.

These tools have a really easy shortcut. You just need to remember one key and then you can find out any tool. Great right? 
The Shortcuts are as followed:

| Tool          | Shortcut-Key  |
| ----          | ----          | 
| Hand Tool     | Q             |
| Move Tool     | W             |
| Rotate Tool   | E             |
| Scale Tool    | R             |    
| Rect Tool     | T             |     
| Combined Tool | Y             |

\
The trick is, that the order of the keys are the same as displayed at the top of your unity editor. 
You can easily switch between those tool without moving your mouse away from your object just by looking at the top of you editor (or just try it out until you have the right one). 

If you are using a QWERTZ-Keyboard, you may notice that your combined tool is not in the row as all the others. But I think that is okay, because either you get used to it or you just use the single tools as I do. 

Two additional shortcuts worth to know are for toggle the values next to the tools. To look at the center of an object or its pivot (especially useful when editing a UI) and toggle between global and local transform of an object. 

| Tool                  | Shortcut-Key  | 
| ---                   |     ---       |
| Toggle Pivot/Center   |  Z            | 
| Toggle Global/Local   |  X            |

\
Again QWERTZ-Keyboard kinda messed with Unitys intention to have it between each other, but you 


## Expanding/collapse GameObjects

While working on a project it will get a lot bigger every commit you make. As well as the depth of some GameObjects increase during the development. It can be really annoying to collapse and expand everything every time. So I will show you some tricks to save some time while doing so. 



## Renaming GameObjects

There are several ways of renaming a GameObject in Unity. You can do it the long way, where you right click on the object and click on rename. Or you can do some kind of slow double click. Once an object is selected, clicking on this object enable the renaming. 

But for those who like to use the keyboard, of course there is a way. Some of you already know about it, because it is the same shortcut as it is for the Linux file browser. Just press ` F2 ` and you can rename the object you have selected. 

## Placing Objects

Sometimes we create something like a road, or walls. Things that needed to be right beside each other. But nobody wants to count pixels to get it right or just leave it chaotic in the scene. But you don't have to!

Unity has something called "Snapping". Just to know that snapping exists helped me so much. I will show you some examples.

The first kind of snapping is the Face-Snapping. By holding `CTRL + SHIFT` the center of your tool kinda looks different (as seen in the gif below). When you move your object near a surface now, the object will stick to it. And that what we want most of the time, to just have our objects on the ground, right?

{{< image src="./FaceSnappingSmaller.gif" alt="Example for Face Snapping" position="center">}}

The second thing is Vertex-Snapping. While holding `V` the center of your tool change again, to let you know you are snapping now. Furthermore you not selecting the center of the object anymore. While hovering over the object, the tool you choose stick to the nearest corner of the object. If your move your object like that, you can fit the selected vertex to a vertex of another object. 

{{< image src="./VertexSnappingSmaller.gif" alt="Example for Vertex Snapping" position="center">}}

I hope these tips helps you when starting with Unity or even tell you some tricks if you already work with it. 

Good luck with your coding!

---
---
## Additional Information
Overview about all Unity Shortcuts: \
https://docs.unity3d.com/2017.3/Documentation/Manual/UnityHotkeys.html

I currently use Unity version:
-  Unity 2019.4.1.17f1

In case of questions or feedback, feel free to contact me on twitter.

##### **Written 16.05.2021**