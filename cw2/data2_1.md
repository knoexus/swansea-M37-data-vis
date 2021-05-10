---
follows: coursework
---

Swimbladder Gives You Wings

{(aim|}

We can learn what the structure, shape and possibly the volume of the fish's swimbladder is. All three can be useful for comparing various types of fish in ichthyological contexts.

{|aim)}

{(vistype|}

Slice

{|vistype)}

![alt text](./images/3_1_1.png)<br/>
![alt text](./images/3_1_2.png)<br/>

{(vismapping|}

We have selected the default x-ray palette as the basis the our color mapping. 

Body — {swimbladder, other gaps}: white / grey, data values: ~[0; 2501];
Swimbladder: black, data values ~ [2501; 2871];

Opacity mapping:

Body — {swimbladder, other gaps}: ~[0.77; 0.93];
Swimbladder: ~[0.93; 1];

{|vismapping)}

{(dataprep|}

Slice extraction:
<table>
    <thead>
        <tr>
            <td>Property</td>
            <td>X</td>
            <td>Y</td>
            <td>Z</td>
        <tr>
    </thead>
    <tbody>
        <tr>
            <td>Origin</td>
            <td>127.5</td>
            <td>127.5</td>
            <td>255.5</td>
        <tr>
        <tr>
            <td>Normal (image 1)</td>
            <td>0</td>
            <td>-1</td>
            <td>0</td>
        <tr>
        <tr>
            <td>Normal (image 2)</td>
            <td>1</td>
            <td>0</td>
            <td>0</td>
        <tr>
    </tbody>
</table>

{|dataprep)}

{(limitations|}

We cannot really see at which stage of inflation the swimbladder is, so we need to know the state of the fish prior to analysing the swimbladder's aforementioned properties. Also, as this is a slice, perhaps undestanding how smooth / homogeneous the surface of the swimbladder is, is a bit problematic.

{|limitations)}
