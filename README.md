//java-ternary-operator-
//Easier way to use if:ese statement

//using if-else statement
class demo{
 public static void main(String []args)
 {
 int marks[]={78,98,66,55];
 for(int i=0;i<marks.length;i++){
 if(marks>=75){
 System.out.println("pass!!");
 
 }else{
System.out.println("fail!!!");
}
 }
}
}

//using ternary operator
class demo{
 public static void main(String []args)
 {
 int marks[]={78,98,66,55];
 for(int i=0;i<marks.length;i++){
 
 marks>=75 ? "System.out.println("pass!!")":"System.out.println("fail!!")";//ternary operator
 }
 


}}
