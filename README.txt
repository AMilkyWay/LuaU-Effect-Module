@A_MilkyWay

version_0_3.rbxm - effect module file.

effect module version: 0.3

inside a source container write `effects = require(MODULE_PATH);` to get the module.
After you've done that, you can use a number of functions from inside of the module.

Function list: 

effects.basic(table) - Table Values: 
<
Start CFrame, 
Goal CFrame(Optional), 
Vector3 Spin, 
Color3 Color,
Color3 Final Color,
Vector3 Size,
Vector3 Final Size,
String/Enum Material,
Number Transparency,
Number Transparency Final,
String Mesh,
Number Speed;
>
---------------------------------------------------
effects.ghost_up(table) - Table Values:
<
Instance Part,
Color3 Color;
>