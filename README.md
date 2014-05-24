tester
======
public static void main(String[] args){
  String name = "Ryan";
  greetUser(name);

}

private void greetUser(String name){
  if(name != null){
    System.out.println("Hello " + name);
  }
  else{
    System.out.println("Please enter name");
  }
}
