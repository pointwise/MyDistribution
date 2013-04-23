MyDistribution
===============
This script demonstrates how you can use the setPoint command to create your own connector grid point distribution function. It's not all that useful right out of the box, but it provides the basis on which you can build a distribution function that better meets your requirements.

The script includes several sample functions that are based on a linear parameter u along the connector's length. There is a simple linear function, square, hyperbolic tangent, and a cubic (shown in the illustration).

As illustrated here, by programming your own distribution function you can cluster points toward the middle of the connector. You can only do this with Pointwise's GUI by inserting break points.

In the image below, the script uses a cubic function to cluster points on the connectors' interior (top) relative to its original state (bottom).

![ScriptImage](https://raw.github.com/pointwise/MyDistribution/master/ScriptImage.png)

Disclaimer
----------
Scripts are freely provided. They are not supported products of
Pointwise, Inc. Some scripts have been written and contributed by third
parties outside of Pointwise's control.

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, POINTWISE DISCLAIMS
ALL WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING, BUT NOT LIMITED
TO, IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
PURPOSE, WITH REGARD TO THESE SCRIPTS. TO THE MAXIMUM EXTENT PERMITTED
BY APPLICABLE LAW, IN NO EVENT SHALL POINTWISE BE LIABLE TO ANY PARTY
FOR ANY SPECIAL, INCIDENTAL, INDIRECT, OR CONSEQUENTIAL DAMAGES
WHATSOEVER (INCLUDING, WITHOUT LIMITATION, DAMAGES FOR LOSS OF BUSINESS
INFORMATION, OR ANY OTHER PECUNIARY LOSS) ARISING OUT OF THE USE OF OR
INABILITY TO USE THESE SCRIPTS EVEN IF POINTWISE HAS BEEN ADVISED OF THE
POSSIBILITY OF SUCH DAMAGES AND REGARDLESS OF THE FAULT OR NEGLIGENCE OF
POINTWISE.
	 

