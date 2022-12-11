Hi there ✋ I have designed VAP-D (Volume, Area, Perimeter, number of diagonal) circuit using Xilinx Design Suite 14.7.  



[S3]	[S2]	[S1]	[S0]	-	OPERATION  

 0	   0	   0	   0	-	Volume of Cube  

 0	   0	   0	   1	-	Volume of Triangular prism  
 
 0	 0	 1	 0	-	Volume of Cuboid  
 
 0	 0	 1	 1	-	Volume of Trapezoid  
 
 

 0	 1	 0	 0	-	Area of Square  
 
 0	 1	 0	 1	-	Area of Triangle  
 
 0	 1	 1	 0	-	Area of Rectangle  
 
 0	 1	 1	 1	-	Area of Trapezium  
 


 1	 0	 0	 0	-	Perimeter of Circle (in cm)  
 
 1	 0	 0	 1	-	Perimeter of Triangle  
 
 1	 0	 1	 0	-	Perimeter of Rectangle  
 
 1	 0	 1	 1	-	Perimeter of Trapezium  
   
   


 1	 1	 X	 X	-	Number of Diagonals  
 


Input- Length, Breath, Height, Base, Radius(in m), Sides of a polygon.  



![ADPV](https://user-images.githubusercontent.com/91768976/206904007-e961a387-a69f-4a80-8397-08da28dbd959.png)

![Area Waveform](https://user-images.githubusercontent.com/91768976/206904009-15cfde71-41eb-4901-a7ad-15a43c35aa87.png)

![Diagonal Waveform](https://user-images.githubusercontent.com/91768976/206904011-13eab672-c550-483d-a087-99f81774efbf.png)

![Perimeter Waveform](https://user-images.githubusercontent.com/91768976/206904012-e1079271-beb9-48ae-ad78-ec56b2d2f69e.png)

![Volume Waveform](https://user-images.githubusercontent.com/91768976/206904017-bc60e894-cef3-4adb-ad11-db4d8efc2c24.png)
