1. You need [Fragmotion](http://www.fragmosoft.com/fragMOTION/), [Juan's RMESH plugin](https://undertowgames.com/forum/viewtopic.php?f=11&t=7369) and [Irrlicht Engine](https://irrlicht.sourceforge.io/).
2. Install Fragmotion and put RMESH plugin to Fragmotion/Plugins folder (usually C://Fragmosoft/FragMOTION v.v.v/Plugins)
3. Enter the God's prayer and then load your .rmesh in Fragmotion.
4. Remove _lm textures in Textures tab [step4-1](/images/step4-1.png) , [step4-2](/images/step4-2.png).
5. Save as .b3d (Blitz 3D) file.
6. Extract Irrlicht Engine .zip and move to *<*your_place_of_Irrlicht*>*\bin\Win32-VisualStudio\
7. Run ```meshconverter --format=obj *<*place_of_your_B3D_model*>* *<*place_of_your_new_OBJ_model*>*```
As example ```meshconverter --format=obj d:\temp\CBRooms\LC_cont1_049.b3d d:\progs\irrlicht-1.8.5\bin\Win32-VisualStudio\LC_cont1_049.obj```
It is better to store your OBJ file in the same folder as MeshConverter.exe, because .mtl file, necessary for materials, is stored there.