# COIT11134 - Sample Exam - BQ5 - Complete Missing Code

## Question 5   (5 MARKS)

Insert the missing codes in the following Java program.


```
//Class PlayListener is an action listener
import javax.swing.JButton;
import javax.swing.JFrame;


// *** Missing code:
//Complete the two missing import statements below:
import java.awt.event.
import java.awt.event.


class PlayListener  implements ActionListener
{
   public void actionPerformed(ActionEvent event)
   {
      System.out.println("Play is selected");
   }
}


// Class PlayTester is a GUI to use PlayListener
public class PlayTester extends JFrame
{
   JButton bt;

   PlayTester()
   {
      JButton bt = new JButton("Start Play");
      add(bt);
      //Write your code here to install PlayListner
      //Write your code related to �Start Play� button-click
      //event handled by the PlayListener

      // *** Missing code:
      //Missing lines of codes




   }


   public static void main(String [] args)
   {
      PlayTester aGame = new PlayTester();
      aGame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
      aGame.setSize(300, 300);
      aGame.setVisible(true);
   }
}
~~~
