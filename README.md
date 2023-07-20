# Plindrome
Palindrome Program
//SOURCE CODE
1.	import java.io.*;
2.	import java.util.*;
3.	class PalindromeExample{  
4.	 public static void main(String args[]){  
5.	  int r,sum=0,temp;    
6.	  int n=454; //It is the number variable to be checked for palindrome  
7.	  temp=n;    
8.	  while(n>0){    
9.	   r=n%10;  //getting remainder  
10.	   sum=(sum*10)+r;    
11.	   n=n/10;    
12.	  }    
13.	  if(temp==sum)    
14.	   System.out.println("palindrome number ");    
15.	  else    
16.	   System.out.println("not palindrome");    
17.	}  
18.	}  
//OUTPUT:
palindrome  number

