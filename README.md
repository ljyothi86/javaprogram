write a java program class and object
class student
{
int sid;     // Instance variables
string name;
 void display() // method
 {
 System .out.println("student id:+ sid);
 System.out.println ("student name:"+name);
 }
 }
 class demo12
 {
 public static void main(String arges[])
 {
 student s= new student();
 s.sid =345;
 s.name="john";
 s.display();
  student s1= new student();
  s1.sid=456;
  s1.name="rani";
  s1. display();
  }

  }
