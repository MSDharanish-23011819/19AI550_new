# Ex.No: 9  Implementation of RollarBall Design using Reinforcement Learning 
### DATE:28-08-2026                                                                
### REGISTER NUMBER : 212223240027
### AIM: 
To write a program to design RollerBall and train the Rollerbal by Reinforcement learning  in Unity 
### Installation Required 
```
1.Check sytem have python 3.10.0  ( if any higher version then uninstall and install python3.10.0)

2. Open commandprompt and Create and activate Python virtualenv by
     python -m venv venv 
     venv\Scripts\activate

3. install the packages 
   pip install numpy==1.23.5 scipy==1.10.1 h5py==3.8.0 protobuf==3.20.*

4. install ML agents by 
   pip install mlagents==0.28.0

5. install torch by 
  pip install torch torchvision torchaudio

6. Check mlagent version and check all the main options that you can use when launching the Python trainer by 
pip show mlagents 
mlagents-learn --help
```
### Algorithm:
```

1.Create a new 3D Unity project

2.Create a plane → Right-click Hierarchy > 3D Object > Plane

3.Create an Agent (Cube)
    Select-Gameobject->3D Object → Cube → Rename to Agent

5. Add Rigidbody (disable gravity if needed) to Agent ( by Inspector window- Adcomponent->physics->Rigidbody)

6. Create a Target (Sphere)
   Select-Gameobject-> 3D Object → Sphere → Rename to Target

7.Create an empty GameObject → Academy (to reset Agent and Target positions)

8.Install ml-agents in unity by window-packagemanager-Packageaddbyname=> com.unity.ml-agents => click install

9.Create a new script in Project window, name it as RollerAgent.cs and type the script

10. Attach the script to Agent
