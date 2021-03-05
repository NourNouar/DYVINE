# DYVINE
DYnamic forwarding graphs for VIrtual NEtwork functions.  

# Description
A solution for dynamic forwarding graphs for virtual network functions  
<img width="679" alt="main2" src="https://user-images.githubusercontent.com/67935963/110173076-6aafbf80-7dfe-11eb-9424-5a93a9942313.PNG">

DYVINE_maker exposes the main UI. Throught this UI, you are able to create you NS by simply draging and dropping the consituent VNFs from tap "Element" to the workplace  
Element tap conatins 2 VNF types: Operative VNF and Routing. The first implements the regular (functional) network functions while the second implement the control logic among operative VNFs like concurrency (i.e., swing-AND), exclusivity (i.e., swing-XOR), or both (i.e., swing-OR).  
Once you have all the constituent VNFs in the workplace, you are able to connect the VNF by simply drag the source VNF and drop on the destinator VNF. 
After defining the NS execution workflow, you select the desired VNF to enhance it with wiring capabilities and you choose from the element Tab the Routing VNF type (Proxy or Swing). After you select the wiring type (AND, OR, XOR). Once you click on this button, a new window will appear. this windows allwos you the define the different paths.
At the right side of this GUI, you use property Tab in order to discover a concrete VNFs based on specific information (e.g., VNF type, operation, price...etc).
Finally, you press the finish button to gnerate the different VNFs/NS packages and requet OSM to onboard them.


# Common setup
Clone the repo
git clone https://github.com/nouarnour/DYVINE.git  
