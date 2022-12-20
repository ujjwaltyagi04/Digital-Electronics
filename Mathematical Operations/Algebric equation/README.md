Hi there✋ I have designed a circuit to calculate the value of algebraic equations using Xilinx Design Suite 14.7.
a and b are two four-bit inputs.
S0 and S1 decides the polarity of a and b.

 [M2]      [M1]       [M0]    -         OPERATION  
 
  0         0          0        -          A²+ B²  
  
  0          0         1        -          (A+B)²  
  
  0          1         0        -          A²-B²   
  
  0          1         1        -          (A-B)²  
  

  1          0         0        -          A³+B³  
  
  1          0         1        -          (A+B)³  
  
  1          1         0        -          A³-B³  
  
  1          1         1        -          (A-B)³  
  
![a](https://user-images.githubusercontent.com/91768976/208586976-fcd3f770-39be-4792-9965-d0b044a38c65.png)
![b](https://user-images.githubusercontent.com/91768976/208586977-bfbf018c-ab90-4abc-abd6-fafdc1f732dd.png)
![c](https://user-images.githubusercontent.com/91768976/208586986-6d62c963-e79b-4bcf-9cda-9b7d26c71345.png)
