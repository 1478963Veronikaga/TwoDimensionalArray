# TwoDimensionalArray
Algorithum
package flowgorithm;

import java.util.Scanner;

public class TowDimensionalArray {
	

public static void main(String[]args){
	Scanner scan = new Scanner(System.in);
	double array[][] = new double[10][10];
	double sumI = 0;
	double sumIt = 0;
		
	    for(int i = 0;i<4;i++){
		for(int j = 0;j<2;j++){
	       
		//	System.out.println("Enter range  :  ");
			//    int rangeI = scan.nextInt();
			   // array[i][j] = rangeI;
			    for(int m = 0;m<4;m++){
					for(int n = 0;n<2;n++){
			    System.out.println("Enter range:  ");
			    array[i][j] = scan.nextFloat();
			    System.out.println("[" + m + "] ["+ n + "]"+ array[i][j]);
			    if((i==0)||(i==1)){
			    sumI+=array[i][j];
			    }else{
			    sumIt+=array[i][j];
			    }		
			}
			    
	    
		    }
			    System.out.println("Sum for I is: " + sumI);	
			    System.out.println("Sum for It is: " + sumIt);
	    }
		 
	    }
}
}

