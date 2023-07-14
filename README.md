# AsynchronousMotorControl_PLC
Asynchronous Motor Control With TiaPortal &amp; PLCSIM &amp; WinccAdvanced
8*3 phase asynchronous motors were contrelled with using simulation,in this project.Firstly,choise PLC and HMI then added to project.
You will add Profinet board to HMI device from communications boards.Of course, your choised HMI device's if nothing profinet input.
Then you will communicate PLC and HMI devices from profinet inputs.
After that,you will determine PLC inputs/outputs for run 3 phase asynchronous motor.Then you'll to name to this I/O's by creating DATABLOCK structure.
![motorsdb](https://github.com/huseyinbali/AsynchronousMotorControl_PLC/assets/137905457/ceed4019-2a69-46d5-98f7-de274e1c12d0)
After that you'll creating Function Block(FB) for control of the motors.
You'll creating Ladder diagram with using PLC Inputs/Outputs in this FUNCTION BLOCK.
![functionblockLadderdiagram](https://github.com/huseyinbali/AsynchronousMotorControl_PLC/assets/137905457/381a9da4-1bd6-40b0-846b-5e9c33e09852)
You'll create main operation block by associating Function Block and Data Block.If the conditions we want come true,the engine will be start.
![main_ob1](https://github.com/huseyinbali/AsynchronousMotorControl_PLC/assets/137905457/a1dc3787-375f-45bb-aabc-27f393d4e22f)
Finally,you'll add a new screen to HMI device.You'll draw Power and Control circuits 3 phase asynchronous motor's in this screen.
Select each object you drew one by one and you are by associating with PLC I/O's so that you can simulate power and control circuit you drew.
You can control other motors by adding new screen with copy/paste.
![motorscreens](https://github.com/huseyinbali/AsynchronousMotorControl_PLC/assets/137905457/eb2308bd-b669-4bac-a231-5a53fd3c8e7e)
You can run the PLC and HMI simulations.
![interface](https://github.com/huseyinbali/AsynchronousMotorControl_PLC/assets/137905457/6da1c97e-febf-4f10-a58b-d9c0cedb5dd0)
