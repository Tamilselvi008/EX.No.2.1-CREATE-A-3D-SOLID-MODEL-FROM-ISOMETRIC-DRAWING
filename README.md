# EX.No.2.1  CREATE A 3D SOLID MODEL FROM ISOMETRIC DRAWING
## Date:12-10-2026

## AIM
To create a 3Dmodel from the given isometric drawing using fusion 360 tool. 

## REQUIREMENTS
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE

## A. Set up the design

1. Open Fusion 360 and create a new design.
2. In the Browser, expand **Document Settings**.
3. Click the units setting and choose **Millimeters**.

## B. Draw and extrude the main rectangle

1. Select **Create Sketch**.
2. Select the **XY plane**.
<img width="1920" height="1028" alt="Screenshot (293)" src="https://github.com/user-attachments/assets/0d570d37-261a-4228-8305-80f67eea6c2e" />

3. Open the **Rectangle** dropdown and select **Center Rectangle**.
4. Click the origin to place the center of the rectangle.
5. Move the cursor outward and click to create the rectangle.
6. Use **Sketch Dimension**:
   - Select one horizontal edge and enter **100 mm**.
   - Select one vertical edge and enter **50 mm**.
   - <img width="1920" height="1011" alt="Screenshot (273)" src="https://github.com/user-attachments/assets/3c18ae01-0846-4fe3-b8a5-07623003e872" />

7. Check that the rectangle is centered on the origin.
8. Then choose the line option to draw the upper box portion.
9. <img width="1920" height="1024" alt="Screenshot (274)" src="https://github.com/user-attachments/assets/9e799e95-f571-4721-8f6f-93bd3d06be4d" />

10. Click **Finish Sketch**.
11. Select **Solid > Create > Extrude**.
12. Set **Operation** to **New Body**.
13. Click **OK**.
14. <img width="1920" height="1024" alt="Screenshot (275)" src="https://github.com/user-attachments/assets/1d8c3a94-31b5-48ad-801e-9f22b1e43b01" />

<img width="1920" height="1024" alt="Screenshot (276)" src="https://github.com/user-attachments/assets/6d58ea9e-5c29-4ba7-869d-cc98d5267e87" />


## D. Draw and extrude the front circular feature

1. Select the front face of the main block and choose **Create Sketch**.
2. Open **Create > Circle** and choose **Center Diameter Circle**.
3. Click to place the circle’s center on the front face.
4. Move the cursor outward and click to place the circle.
5. Use **Sketch Dimension** to set the circle diameter to **50 mm**.
   <img width="1920" height="1015" alt="Screenshot (277)" src="https://github.com/user-attachments/assets/47242750-6873-426b-9272-284f05e02887" />

6. Position the circle where you want it on the face. Use dimensions from the block edges if you need an exact location.
7. Click **Finish Sketch**.
8. Select **Solid > Create > Extrude**.
9. Select the circular profile.
10. Enter an extrusion distance of **20 mm**, directed outward from the front face.
11. Set **Operation** to **Join** so the cylinder connects to the block.
12. Click **OK**.
<img width="1920" height="1022" alt="Screenshot (279)" src="https://github.com/user-attachments/assets/82303fad-174c-4564-9242-7a02148ee59a" />

## E. Draw the small rectangular feature on top

1. Select the top face where the small rectangular feature should sit.
2. Choose **Create Sketch**.
3. Open **Rectangle** and select **Center Rectangle**.
6. Use **Sketch Dimension** to set its length and width.
7. 2. Select **Create > Circle > Center Diameter Circle**.
3. Click to place the circle’s center.
4. Draw the circle and set its diameter to **20 mm** using **Sketch Dimension**.
5. Position it with dimensions from the block edges if required.
6. Click **Finish Sketch**.
<img width="1920" height="1010" alt="Screenshot (280)" src="https://github.com/user-attachments/assets/82413a07-e1e9-496a-99ae-46c0a3946d30" />

7. Set the extrusion distance to **5 mm**.
8. Set **Operation** to **Join**.
9. Click **OK**.

<img width="1920" height="1020" alt="Screenshot (286)" src="https://github.com/user-attachments/assets/c14bf4d9-cbbd-4b2a-b505-80cf96742df4" />


## G. Draw and extrude the raised rectangular portion

1. Select the top face where the longer rectangular feature should be placed.
2. Choose **Create Sketch**.
3. Open **Rectangle** and select **Center Rectangle**.
4. Click to place the rectangle’s center.
5. Draw the rectangle.
6. Use **Sketch Dimension** to set its length to **30 mm**.
<img width="1920" height="1017" alt="Screenshot (289)" src="https://github.com/user-attachments/assets/e461e87c-7619-42ce-b461-5ab2957b9015" />

7. Click **Finish Sketch**.
8. Select **Extrude** and choose the rectangular profile.
9. Enter the required extrusion height. This height was not specified.
10. Set **Operation** to **Join** if the feature touches the main body.
11. Click **OK**.
<img width="1920" height="1022" alt="Screenshot (290)" src="https://github.com/user-attachments/assets/42e96173-05a3-4444-bd39-c038c6581f8a" />

## H. Make the slanted transition

A **Fillet** rounds an edge; it does not normally create a flat, straight slope. For a slanted face like the one visible in the screenshot, use **Chamfer**:

1. Rotate the model so the edge to be slanted is easy to select.
2. Select **Modify > Fillet**.
3. Select the edge that should become slanted.
<img width="1920" height="1026" alt="Screenshot (292)" src="https://github.com/user-attachments/assets/e67f02b4-486f-4161-abac-8f94bf870603" />

4. Preview the result and adjust the value until the slanted face has the intended size.
5. Click **OK**.


## I. Check and save the model

1. Orbit the model and check that the front cylinder and top features are joined as intended.
2. Confirm that the slanted feature is on the correct edge.
3. Save the design.
<img width="1920" height="1019" alt="Screenshot (270)" src="https://github.com/user-attachments/assets/a7cf8b6a-69fa-41f3-8194-02b050d9d675" />

## J. Create the drawing

1. With the model saved, select **Design > Drawing > From Design**.
2. Choose the drawing standard, units, and sheet size.
3. Select the base view orientation that shows the front cylinder clearly.
4. Place the base view on the sheet.
5. Use **Projected View** to add top and side views.
6. Add an isometric view if you want a visual overview.
7. Use **Dimension** to label the known dimensions:
   - Main rectangle: **100 mm × 50 mm**
   - Front circular feature: **Ø50 mm**
   - Front extrusion: **20 mm**
   - Top circle: **Ø20 mm**
   - Top feature heights: **5 mm**
   - Raised rectangle length: **30 mm**
8. Save the drawing.

## INPUT
![image](https://user-images.githubusercontent.com/113594316/198495472-9a69edb1-f0c6-470c-b9ae-fe282fa6a678.png)

## OUTPUT
<img width="1920" height="1015" alt="Screenshot (271)" src="https://github.com/user-attachments/assets/a2dbd825-fd7d-42d9-aa1e-5434fe242616" />

## RESULT: 
 Thus, the 3D model is created from given isometric drawing.
