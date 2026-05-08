# Person Counting and Heatmap System using YOLO11<br>

# Project Overview<br>
Here we are doing video analysis. Here we are counting people through two lines, how many are entering and how many are leaving and generating the final heatmath.
<br>

# Features
<br>
*Person Detection<br>
*Tracking<br>
*IN/OUT Counting<br>
*Heatmap Generation<br>
*Video Output<br>

# Detection Method<br>
1) YOLO11x <br>
2) BoTSORT Tracker <br>
3) COCO Class ID = 0 (Person) <br>
4) Virtual Line Crossing <br>
5) Supervision HeatMapAnnotator <br>

# IN / OUT Logic<br>
Here we have drawn two lines a little above and one below. Then we detected the center point of the object. If the object's center point crosses the line, the count is incremented. <br>

# Line Coordinates<br>
ANNOT_LINE_IN_START = (1, 284)<br>
ANNOT_LINE_IN_END = (1670, 289)<br>
ANNOT_LINE_OUT_START = (6, 846)<br>
ANNOT_LINE_OUT_END = (1665, 851)<br>
ANNOT_W, ANNOT_H = 1678, 949<br>
# SS of counting person<br>
![image alt](https://github.com/MD-shahriar6/person-count-heatmap-01996736977/blob/e418b807eb7cc789eaa6a7d3e405131fac32cfca/Screenshot%202026-05-08%20210704.png)

# SS of heatmap <br>

![image alt](https://github.com/MD-shahriar6/person-count-heatmap-01996736977/blob/840afc093aa68c5112e5538bee3ec4e4c9837ef0/Screenshot%202026-05-08%20210755.png)
