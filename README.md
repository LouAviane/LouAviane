-public class Matrix{
   public static void main(String args[]){  
 
    java.util.Scanner input = new java.util.Scanner(System.in);
    
     int[][]matrix - new int [3][3]
    
    System.out.print1n("Enter "+ matrix.length +"rows and"+ matrix [0].length + "columns:");
       for (int row = 0; row < matrix.length; row++)
       {
           
         for (int column =0; column < matrix[row].length; column++)
         {  
           matrix[row][column] = input.nextInt();
           //matrix[row][column] = (int)(Math.random() * 100);
       }
     }   
     //display the contents of array
     for (int row - 0; row < matrix.length;row+)
     {
        for (int column - 0; column < matrix[row].length;column++) {
     System.out.print(matrix[row][column] +" ");
    }
    System.out.print1n();
{
  
