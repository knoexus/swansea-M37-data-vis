---
follows: coursework
---

# Bear Declassified

{(aim|}

We can learn what is written on the belly of the teddy bear. Potentially, this can help us determine its origin (place of sale / manufacturing) or why it was acquired (e.g., a New Year / Christmas present). 

{|aim)}

{(vistype|}

Volume Clip Visualization

{|vistype)}

![alt text](./images/2_1_1.png)<br/>
![alt text](./images/2_1_2.png)<br/>
![alt text](./images/2_1_3.png)<br/>

{(vismapping|}

Color mapping:

We have selected the Yellow - gray - blue palette as the basis the our color mapping. 

<ul>
  <li>
    Body (insides): red, data values: ~[0; 250];
  </li>
  <li>
    Space around the bear: red, data values ~ [0; 250];
  </li>
  <li>
    Seams (contours): yellow, data values: ~[250; 700];
  </li>
  <li>
    Eyes: black & blue, data values: ~[700; 1300].
  </li>
</ul>


Opacity mapping:

<ul>
  <li>
    Bear insides, space around the bear: ~ [0; 0.37];
  </li>
  <li>
    Seams, letters: ~ [0.37; 0.76];
  </li>
  <li>
    Eyes: ~ [0.76, 1].
  </li>
</ul>

{|vismapping)}

{(dataprep|}
1. Data Spacing -> z-axis x 6.7 times
2. Subset extraction:
To remove the surface the bear is leaning (lying) on and the volume right before the sign, we extract the susbset within the y-axis: (0 — 511) -> (230 — 350)

{|dataprep)}

{(limitations|}

Unfortunately, even though the text is rather undestandable (presumably, "MERRY CHRISTMAS HAPPY NEW YEAR POLAR BEAR"), we cannot distinguish some letters (e.g., letter "R") and have to deduce the word through its context. However, we have not found other ways (e.g., switching opacity of the bear's insides to lower values) to amplify resolution of certain letters without sacrifising the resolution of the others. In addition, the luminance of the seam behind the sign on the bear's belly covers some letters of the sign, but is very difficult to remove. Finally, the color mappings used for enhancing the perception of the text may deviate from its viewer's cognitive bias and they may find the visualization daunting. 

{|limitations)}
