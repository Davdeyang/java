# java

class Person{
   String name;
   int age;
   String sex;
   double salary;
   
   public void eat()
   {
       System.out.println("喜欢吃糖 结果吃成了胖子");
   
   }
   public void  study()
   {
       System.out.println("good good study,day day up; 好好学习天天向上");
   
   }
   public void hobby()
   {
      System.out.println("喜欢唱歌 跳舞 画画");
   }




    public static void main(String[]args)
    {
      Person ps = new Person();
      ps.eat();
      ps.study();
      ps.hobby();
    
    
    
    }
}
