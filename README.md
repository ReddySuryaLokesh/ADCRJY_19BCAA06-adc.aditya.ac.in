# ADCRJY_19BCAA06-adc.aditya.ac.in
 class reddy
 {  
  static int factorial(int n)
  {    
   if (n == 0)    
     return 1;    
   else    
     return(n * factorial(n-1));    
  }    
  public static void main(String args[])
  {  
   int i,fact=1;  
   int number=5;  
   fact = factorial(number);   
   System.out.println("Factorial of "+number+" is: "+fact);    
  }  
 }  
 ..........................
 Output
 Factorial of 5 is: 120
