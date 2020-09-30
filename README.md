# -1.2---30.09
1 вариант
public class Control4 { 
    // Данно двухзначное число и кратно ли оно 3? 
    public static void main(String[] args) { 
        Scanner s = new Scanner(System.in); 
        System.out.print("Введите двухзначное число: "); 
        int a = s.nextInt(); 
        int b = a/10; 
        int c = a / 10 % 10; 
 
       if ((b+c) % 3 == 0) { 
           System.out.println("Да"); 
       }else { 
           System.out.println("Нет"); 
       } 
 
    } 
 
 
} 
 
