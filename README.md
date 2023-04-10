# Clause Process with treating unit

 The Claus process is the most significant gas desulfurizing process, recovering elemental sulfur from gaseous hydrogen sulfide. First patented in 1883 by the chemist Carl Friedrich Claus, the Claus process has become the industry standard. 
 
The description of the process can be read at this link : https://chemiopedia.com/claus-process-with-tail-gas-treating/

Softwere use for this simulation :
![Aspen Version](https://img.shields.io/badge/Aspen_Hysys-v12.1-Green)

The Process Flow Diagram from the process

![image](https://user-images.githubusercontent.com/121662875/230872866-52061e6f-8c41-4b59-99ea-93e90e2d403a.png)
The lower section is the sulphur recovery and the top section is the treating unit

# Lower_section
The simulation feed was generated automatically from the selection of the fluid package. The selected fluid package is Sulphur Recovery fluid Package. The PFD was constructed in the subflowsheet environment because there are equipments that can be access in the Parent flowsheet. The use of multiple stage sulphur condenser with catalythic converter is to increase the effeciency of the process. Most of the sulphur are condensed are recovered in the second stage, the third stage will serve the purpose of back up or extra stage if the feed is increase unexpectedly.

# Upper_section
In the treating section, Reducing Gas Generator is assumed function at 90 percent efficiency with steam to fuel Ratio by mass at 100 efficiency. The impact of the process in real life application is that there are rules and regulations that any process engineer has to follow and by using this simulation, the most efficient process with the lowest capital, utilities and operating cost can be estimated.

# Made by :
1. Abdul_Hafiz
2. Surayya
