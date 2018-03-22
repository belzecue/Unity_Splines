# Unity Splines

Creates bezier spline curves directly in Unity using a GUI interface that mimics the Adobe pen tool. You 
can also import SVG files and the program with convert the path into Unity splines. <br>

By simply adding an animation script to a GameObject and selecting the spline, the object will animate along the curve.

![Spline Demo](https://raw.githubusercontent.com/Shealynntate/Unity_Splines/master/Images/SplineDemo1.gif)

## Usage
---

To animate a GameObject, simply add the *SplineAnimation.cs* script to the object and add the spline to the public field in the inspector. You can then set the move speed and whether or not you want the object to orient itself along the path.

Here's the GNU logo imported as an SVG file.
![GNU](https://raw.githubusercontent.com/Shealynntate/Unity_Splines/master/Images/GNU_Logo.png)
And a floral SVG file.
![Floral Design](https://raw.githubusercontent.com/Shealynntate/Unity_Splines/master/Images/Floral_Design.png)

### Note
---
This project is a work in progress. Some svg commands aren't yet implemented 
and the Spline Editor Window feature set is minimal at the moment.

