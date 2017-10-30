package practise;

import java.util.Scanner;

public class ArraysLearning {

    public static void main(String[] args) {
        // TODO Auto-generated method stub
      System.out.println("what is your name");
      String userName = "";
      Scanner scnr = new Scanner(System.in);
      userName  =scnr.next();
      
      if(userName.equals("jim")) {
          for (int j=0;j<4;j++) {
              System.out.println(userName);
          }
      }
      else {
      
         
          for (int i=0;i<9;i++) {
              System.out.println(userName);
          }
    }

}
}
