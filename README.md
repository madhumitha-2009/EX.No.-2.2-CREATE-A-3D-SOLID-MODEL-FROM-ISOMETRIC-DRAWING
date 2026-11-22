# EX.No.-2.2 CREATE A 3D SOLID MODEL FROM ISOMETRIC DRAWING
## Date : 21/10/2026

## AIM:
To create a 3D solid model of the given engineering component using CAD software 
(such as AutoCAD, SolidWorks, or Fusion 360) based on the specified dimensions
## REQUIREMENTS:
* Hardware: Intel Core i5/i7 Processor (or equivalent), minimum 8 GB RAM, 
dedicated Graphics Card, and a Mouse with a scroll wheel. 
* Software: Any standard 3D CAD modeling software (AutoCAD 3D, SolidWorks, 
Creo, or Autodesk Fusion 360).
Procedure : 
Step 1: Set up the Modeling Environment 
*Open the CAD software, select a new 3D part design workspace, and set the 
standard units to Metric (mm). 
*choose the appropriate plane or coordinate system to begin creating the 3D model. 
*check that the sketch tools and modeling commands are available before   
proceeding to the next step.
<img width="1013" height="478" alt="Screenshot 2026-11-20 185836" src="https://github.com/user-attachments/assets/3a60d670-2ed0-4dca-80ef-259bbff2a92b" />
Step 2: Create the Base Plate Sketch 
Select the Top Plane and sketch the bottom base profile. 
* Draw an elongated slot or rectangle with rounded outer edges having a radius of 
R18 (total width across the rounded edges is 18 × 2 = 36 mm). 
* Set the total length of this base plate to 56 mm.* Sketch two concentric 
through-holes on both circular sides with a diameter of φ16 mm.
<img width="891" height="486" alt="Screenshot 2026-11-20 185954" src="https://github.com/user-attachments/assets/d5ccf4ba-47fa-4fca-949b-1316fb4bbebb" />
Step 3: Extrude the Base Plate 
*Use the Extrude tool to give thickness to the base plate sketch. 
*select new body if you are creating a separate solid.select join if you want to 
connect it to an existing solid. 
* Extrude it upwards by a height of 8 mm along the Z-axis.
<img width="710" height="422" alt="Screenshot 2026-11-20 190123" src="https://github.com/user-attachments/assets/81580e53-6c55-46e1-bed3-797c138744cd" />
Step 4: Draw and Extrude the Vertical Column 
 Select the top face of the extruded base plate. 
* Sketch a rectangular profile with a thickness of 12 mm and a width of 40 mm. 
* Extrude this rectangle vertically upwards by 32 mm (calculated from the top of the 
base to the bottom edge of the upper bracket).
<img width="902" height="487" alt="Screenshot 2026-11-20 190418" src="https://github.com/user-attachments/assets/c2e6b586-83fd-44f5-9adf-2bf6e24bfd61" />
Step 5: Create the Supporting Rib 
Select the central vertical mid-plane (symmetry plane). 
* Draw a triangular web profile starting from the top edge of the vertical column down 
to the base plate. 
* Use the Rib/Web tool to extrude it symmetrically with a thickness of 10 mm.
<img width="518" height="441" alt="Screenshot 2026-11-20 191822" src="https://github.com/user-attachments/assets/2db26a31-1f7e-469f-85d9-86ceb61a7e39" />
Step 6: Model the Upper Bracket Platform 
Select the top surface of the vertical column. 
* Sketch a horizontal rectangular platform extending outwards with a width of 40 mm 
and a length projection of 32 mm. 
* Extrude this platform vertically upwards with a thickness of 10 mm.
<img width="837" height="506" alt="Screenshot 2026-11-20 191019" src="https://github.com/user-attachments/assets/f895d316-7ce6-4ada-afbe-cff4ed6ed335" />
<img width="645" height="450" alt="Screenshot 2026-11-20 192007" src="https://github.com/user-attachments/assets/0c970eae-4403-48a3-a37c-e4245ab1c4c3" />
Step 7: Model the Cylindrical Boss 
On the extended end of the upper platform: 
* Sketch two concentric circles. The outer circle has a diameter of φ30 mm, and the 
inner circle has a diameter of φ20 mm. 
* Extrude the outer cylinder upwards by a height of 10 mm. Ensure the inner φ20 
mm circle cuts entirely through the 10mm platform to create a hollow bore.
<img width="756" height="477" alt="Screenshot 2026-11-20 192503" src="https://github.com/user-attachments/assets/2a595834-07ce-443f-be01-be2186e93b0a" />
Step 8: Final Inspection and Saving 
*Verify all geometric constraints and measurements against the original diagram. 
Check all dimensions and measurements with the original drawing. 
*Apply a material or color appearance if required, and save the final 3D CAD model 
file.
<img width="477" height="445" alt="Screenshot 2026-11-20 192746" src="https://github.com/user-attachments/assets/0817ea39-6f8f-4929-9fc5-3e14eeea5733" />
## INPUT:
![image](https://user-images.githubusercontent.com/113594316/198523331-05ace360-502b-4569-b9b4-31c60e3cd554.png)
Output:
<img width="1087" height="762" alt="Screenshot 2026-10-15 192839" src="https://github.com/user-attachments/assets/dba570c8-e48f-47b4-ae6e-271787eccef4" />
<img width="725" height="655" alt="Screenshot 2026-10-15 182954" src="https://github.com/user-attachments/assets/8589d8ff-8a65-4a7b-b18e-03b51fbd81d0" />


## RESULT: 
Thus, the 3D model is created from given isometric drawing.


