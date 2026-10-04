# Project Overview
This project is a learning-focused redesign of Elektor’s Tiny Solar Power Supply. The aim is to understand the fundamentals of solar energy harvesting and low-power power supply design through hands-on schematic capture and PCB layout.

The entire circuit and PCB were redesigned from scratch using KiCad EDA, while referring to the original Elektor concept strictly for educational and learning purposes

# Learning Objectives
- Understanding solar input conditioning and handling variable input sources
- Learning power regulation basics for low-power applications
- Developing component selection reasoning based on electrical and practical constraints
- Applying practical PCB layout considerations such as trace routing, grounding, and component placement

# Circuit Operation
The system starts with a solar panel as the primary energy source. Since solar output varies with light conditions, the input stage conditions and stabilizes this energy before it is used further.

The conditioned solar input is then passed to a DC-DC regulation stage, which converts the variable input voltage into a usable and stable output suitable for low-power electronic circuits. Passive components around the regulator help improve stability and efficiency.

Finally, the regulated output is made available through the output terminals, allowing it to power small loads or act as a learning reference for energy-harvesting power supplies.

# Images

|Schematic|Layout|
|---|---|
| [Schematic](img/Schematic.png) | [Layout](img/PCB_layout.png) |

|Top|Bottom|
|---|---|
| [Top](img/Render_top.png) | [Bottom](img/Render_bottom.png) |
