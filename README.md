# stairs
Please understand that i just started coding 3 days ago. I try to organize my codes as best as possible but I'm sorry if my codes are messy.
//any advice would be greated appreciated and you can contact me at zhanrong@hotmail.co.uk

package stairs;

/**
 *
 * @author Desktop
 */
public class Stairs {
    public static final int STAIRS = 5; //input number of stairs/humans.
    public static void main(String[] args) {
        for(int i = 1; i <= STAIRS; i++){//for the number of stairs. it repeats the entire function.
            for(int j = 1; j <= ((STAIRS+1)-i)*5-3; j++){  //counts number of spaces to print the head
                System.out.print(" ");
            }
            System.out.print("o  ******");
            for(int j = 1; j <= (i-1)*5; j++){  //prints spaces between staircase
                System.out.print(" ");               
            }
            
            System.out.print("*\n");
            
            for(int k = 1; k <= ((STAIRS+1)-i)*5-4; k++){
                System.out.print(" ");
            }
            
            System.out.print("/|\\ *");
           
            for(int j = 1; j <= (i)*5; j++){  //prints spaces between staircase
                System.out.print(" ");               
            }
            System.out.print("*\n");
            
                        for(int k = 1; k <= ((STAIRS+1)-i)*5-4; k++){
                System.out.print(" ");
            }
            
            System.out.print("/ \\ *");
           
            for(int j = 1; j <= (i)*5; j++){  //prints spaces between staircase
                System.out.print(" ");               
            }
            System.out.print("*\n");                        
        } //end of main loop
        
        for(int i = 1; i <=(STAIRS+1)*5+2; i++){ //this loop is used to 
            System.out.print("*");                  //print the floor of the staircase
        }
        System.out.println();
    }
    
   

    
}
