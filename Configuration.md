---
title: Configuration
layout: default
has_children: false
nav_order: 0
---
## Configuration
*You don't have to restart the game if you make changes either in the file or menu! Changes are applied automatically*
### Changable In-Game
*You can configure tricksaber if you go to the 'Mods' tab in the left menu panel in Beat Saber*
### Changable in Tricksaber.json
*You can find the file in the 'Beat Saber/UserData' directory*
- TriggerAction <span class="variable-type enum">Throw | Spin | None</span> **(should be changed In-Game)**
```
What happens on trigger press
```
- GripAction <span class="variable-type enum">Throw | Spin | None</span> **(should be changed In-Game)**
```
What happens on grip press
```
- ThumbstickAction <span class="variable-type enum">Throw | Spin | None</span> **(should be changed In-Game)**
```
What happens on thumbstick move
```
- ThumstickDirection <span class="variable-type enum">Horizontal | Vertical</span> **(should be changed In-Game)**
```
In which direction do I need to move the thumbstick to spin you saber
```
- TriggerThreshold <span class="variable-type float">float</span> *(can be changed In-Game)*
```
How much do I need to press the trigger for something to happen
```
- GripThreshold <span class="variable-type float">float</span> *(can be changed In-Game)*
```
How much do I need to press the grip for something to happen
```
- ThumbstickThreshold <span class="variable-type float">float</span> *(can be changed In-Game)*
```
How much do I need to move the thumbstick for something to happen
```
- ControllerSnapThreshold <span class="variable-type float">float</span> *(can be changed In-Game)*
```
The minimum distance between the controller and saber for the saber to snap back to the controller after a throw
```
- IsSpeedVelocityDependent <span class="variable-type bool">bool</span> *(can be changed In-Game)*
```
Is the spin speed/direction determined by how the controller was moved
```
- SpinSpeed <span class="variable-type float">float</span> *(can be changed In-Game)*
```
Multiplies the spin speed with the value
```
- SpinDirection <span class="variable-type enum">Forward | Backward</span> **(should be changed In-Game)**
```
In which direction does the saber spin
```
- ThrowVelocity <span class="variable-type float">float</span> *(can be changed In-Game)*
```
Multiplies the throw velocity with the value
```
- ReturnSpeed <span class="variable-type float">float</span> *(can be changed In-Game)*
```
How fast does the saber return
```
- EnableCuttingDuringTrick <span class="variable-type bool">bool</span> *(currently does nothing)*
```
Can I hit stuff during a trick
!DISABLES SCORE SUBMISSION!
```
- SlowmoDuringThrow <span class="variable-type bool">bool</span> *(can be changed In-Game)*
```
Slow down time during the throw trick
!DISABLES SCORE SUBMISSION!
```
- CompleteRotationMode <span class="variable-type bool">bool</span>
```
Completes the spin if stopped midway
```
- SlowmoMultiplier <span class="variable-type float">float</span>
```
How much percent of the default time during slowmo
```
- VelocityBufferSize <span class="variable-type int">int</span> *(Advanced)*
```
For how many frames does the velocity get recorded to get the average velocity
```
- SlowmoStepAmount <span class="variable-type float">float</span> *(Advanced)*
```
By how much does the timescale gets increased/decreased per frame (higher value mean the slowmo effect gets applied faster)
```