# Java-basics-Import java.util.Scanner;
Public class Main
{
        Public static void main(String[] args) {
          Scanner in=new Scanner(System.in);
          /*int a=in.nextInt();
          If(a%4==0)
          System.out.println(“leap year”);
          Else
          System.out.println(“ordinary year”);*/      
         /* int a=in.nextInt();
          If(a%2==0)
          System.out.println(“even”);
          Else
          System.out.println(“odd”);*/
     /* int p=in.nextInt();
      Int r=in.nextInt();
      Float t=in.nextFloat();
      System.out.println(SI=(p*r*t)/100);*/

Import java.util.Scanner;

Public class Max{
    Public static void main(String[] args) {
       /* Scanner i = new Scanner(System.in);
        System.out.print(“Enter first number: “);
        Int a = i.nextInt();
        System.out.print(“Enter second number: “);
        Int b = sc.nextInt();

        Int max = (a > b) ? a : b;
        System.out.println(“Maximum is: “ + max);
    }
}

        Scanner n = new Scanner(System.in);
        System.out.print(“Enter first number: “);
        Int a = n.nextInt();
        System.out.print(“Enter second number: “);
        Int b = sc.nextInt();

        // Swapping without temp variable
        A = a + b;
        B = a – b;
        A = a – b;

        System.out.println(“After swapping: a = “ + a + “, b = “ + b);
    }
}
Scanner n = new Scanner(System.in);
        System.out.print(“Enter marks: “);
        Int m = n.nextInt();

        If (m >= 90 && m <= 100)
            System.out.print(“Grade: A”);
        Else if (m >= 75 && m< 90)
            System.out.print(“Grade: B”);
        Else if (m >=35 && m < 75)
            System.out.print(“Grade: C”);
        Else
            System.out.print(“Fail”);
    }
}
Scanner i = new Scanner(System.in);
        System.out.print(“Enter your age: “);
        Int age = i.nextInt();

        If (age >= 18)
            System.out.println(“You are eligible to vote.”);
        Else
            System.out.println(“You are not eligible to vote.”);
    }
}
       Scanner t=new Scanner(System.in);
       System.out.print()
       Int days=t.nextInt();
       Switch(days)
       {
           Case 1:
               {
                   System.out.println(“Monday”);
                   Break;
               }

           Case 2:
               {
               System.out.println(“Tuesday”);
               Break;
               }

           Case 3:
               {
               System.out.println(“Wednesday”);
               Break;
               }

           Case 4:
               {
               System.out.println(“Thursday”);
               Break;
               }
           Case 5:
               {
               System.out.println(“Friday”);
               Break;
               }
           Case 6:
               {
               System.out.println(“Saturday”);
               Break;
               }

           Case 7:
               {
               System.out.println(“Sunday”);
               Break;
               }
               Default:
               {
                   System.out.println(“Invalid”);
               }
       }
       Int sum=0;
       For(int i=0;i<21&&i%2==0;i++)
       {

       System.out.println(i);
       }

                Scanner in = new Scanner(System.in);
                Boolean flag = true;
                While(flag){
                    System.out.println(“new operation”);
                                        System.out.print(“Enter num1 :”);
                                        Int num1 = in.nextInt();
                                        System.out.print(“Enter num2:”);
                                        Int num2 = in.nextInt();
                                     System.out.print(“Enter operator :”);
                                     Char op = in.next().charAt(0);
                                     System.out.print(“output is :”);
                    Switch(op){
                        Case ‘+’:
                            {
                              System.out.println(num1+num2); 
                              Break;
                            }
                              Case ‘-‘:
                            {
                              System.out.println(num1-num2); 
                              Break;
                            }
                              Case ‘*’:
                            {
                              System.out.println(num1*num2); 
                              Break;
                            }
                              Case ‘/’:
                            {
                              System.out.println(num1/num2); 
                              Break;
                            }
                              Case ‘%’:
                            {
                              System.out.println(num1%num2); 
                              Break;
                            }
                            Default :{
                                System.out.println(“Invalid operator”);
                                Break;
                            }
                    }
                    System.out.print(“Do u need to continue : (Y / N)”);
                    Char k = in.next().charAt(0);
                    If(k != ‘y’){
                        Flag = false;
                    }
                }
                Scanner l = new Scanner(System.in);
                Boolean flag = true;

                    System.out.println(“      MENU      “);
                                        System.out.println(“1.Login”);
                                        System.out.println(“2.Sign in”);
                                        System.out.println(“3.Logout”);
                Do 
                {

                                     Int a=l.nextInt();
                    Switch(a){
                        Case 1:
                            {
                              System.out.println(“ Account Login successfully”); 
                              Break;
                            }
                              Case 2:
                            {
                              System.out.println(“Account Signed successfully “); 
                              Break;
                            }
                              Case 3:
                            {
                              System.out.println(“Account Logout successfully”); 
                              Break;
                            }

                            Default :{
                                System.out.println(“Invalid option”);
                                Break;
                            }
                    }
                    System.out.print(“Do u need to continue : (NEXT/ EXIST)”);
                    String k = l.next();
                    If(k !=”NEXT” ){
                        Flag = false;
                    }
                }
                While(flag);





                /*

                Int k = 4;
                For(int i=0;i < k;i++){
                    For(int j = 1; j<= k-i;j++){
                        System.out.print(j + “ “);
                    }
                    System.out.println();
                }

        Int rows = 5;

        For (int i = 1; i <= rows; i++) {

            For (int j = i; j < rows; j++) {
                System.out.print(“ “);
            }

            For (int k = 1; k <= (2 * i – 1); k++) {
                System.out.print(“*”);
            }
            System.out.println();
        }
Int rows = 4;

        For (int i = 1; i <= rows; i++) {

            For (int j = 0; j <=rows-i; j++) {
                System.out.print(“*”);
            }
            System.out.println();
            }
        Scanner r=new Scanner(System.in);
        Int n=r.nextInt();
            For(int i=0;i<n;i++)
            {
                For(int j=0;j<n;j++)
                {
                    If(i==j||i+j==n-1)
                    {
                        System.out.print(“*”);

                    }
                    Else 
                    {
                        System.out.print(“ “);
                    }
                }
                System.out.println();
            }

            Int rows = 5;

        For (int i = 1; i <= rows; i++) {

            For (int j = 1; j <= (rows-i)*2; j++) {
                System.out.print(“ “);
            }

            For (int k = 1; k <=i ; k++) {
                System.out.print(k+” “);

            }
            System.out.println();
        }

        Int r = 4; 
        Int n = 1;

        For (int i = 1; i <= r; i++) {
        For (int j = 1; j <= (r-i)*2; j++) {
                System.out.print(“*”);
            }

            For (int j = 1; j <= i; j++) {
                System.out.print(n +”*”);
                N++;
            }
            System.out.println(); 
        }
        Int sum=0;
        Int r=101;
        //while(i<0)
        For(int i=0;i<r;i++)
        {
            If(i%2==0)

            Sum+=i;
        }
        System.out.println(sum);

//Digit manipulation
Int num=5294;int rev=0;
While(num>0)
{
    Int digit =num%10;
    Rev=rev*10+digit;
    Num/=10;
}
System.out.println(rev);


Int num=5294;int rev=0;
While(num>0)
{
    Int digit =num%10;
    Rev=rev+digit;
    Num/=10;
}
System.out.println(rev);
*/
While(num>0)
{
    Int digit =num%10;
    Rev=rev+digit;
    Num/=10

         }

}
Import java.util.Scanner;
Public class Main
{
        Public static void main(String[] args) {
          Scanner in=new Scanner(System.in);
          /*int a=in.nextInt();
          If(a%4==0)
          System.out.println(“leap year”);
          Else
          System.out.println(“ordinary year”);*/

//ODD EVEN          
         /* int a=in.nextInt();
          If(a%2==0)
          System.out.println(“even”);
          Else
          System.out.println(“odd”);*/

//SIMPLE INTREST CALCULATOR
     /* int p=in.nextInt();
      Int r=in.nextInt();
      Float t=in.nextFloat();
      System.out.println(SI=(p*r*t)/100);*/

Import java.util.Scanner;

Public class Max{
    Public static void main(String[] args) {
       /* Scanner i = new Scanner(System.in);
        System.out.print(“Enter first number: “);
        Int a = i.nextInt();
        System.out.print(“Enter second number: “);
        Int b = sc.nextInt();

        Int max = (a > b) ? a : b;
        System.out.println(“Maximum is: “ + max);
    }
}

        Scanner n = new Scanner(System.in);
        System.out.print(“Enter first number: “);
        Int a = n.nextInt();
        System.out.print(“Enter second number: “);
        Int b = sc.nextInt();

        // Swapping without temp variable
        A = a + b;
        B = a – b;
        A = a – b;

        System.out.println(“After swapping: a = “ + a + “, b = “ + b);
    }
}
Scanner n = new Scanner(System.in);
        System.out.print(“Enter marks: “);
        Int m = n.nextInt();

        If (m >= 90 && m <= 100)
            System.out.print(“Grade: A”);
        Else if (m >= 75 && m< 90)
            System.out.print(“Grade: B”);
        Else if (m >=35 && m < 75)
            System.out.print(“Grade: C”);
        Else
            System.out.print(“Fail”);
    }
}
Scanner i = new Scanner(System.in);
        System.out.print(“Enter your age: “);
        Int age = i.nextInt();

        If (age >= 18)
            System.out.println(“You are eligible to vote.”);
        Else
            System.out.println(“You are not eligible to vote.”);
    }
}
       Scanner t=new Scanner(System.in);
       System.out.print()
       Int days=t.nextInt();
       Switch(days)
       {
           Case 1:
               {
                   System.out.println(“Monday”);
                   Break;
               }

           Case 2:
               {
               System.out.println(“Tuesday”);
               Break;
               }

           Case 3:
               {
               System.out.println(“Wednesday”);
               Break;
               }

           Case 4:
               {
               System.out.println(“Thursday”);
               Break;
               }
           Case 5:
               {
               System.out.println(“Friday”);
               Break;
               }
           Case 6:
               {
               System.out.println(“Saturday”);
               Break;
               }

           Case 7:
               {
               System.out.println(“Sunday”);
               Break;
               }
               Default:
               {
                   System.out.println(“Invalid”);
               }
       }
       Int sum=0;
       For(int i=0;i<21&&i%2==0;i++)
       {

       System.out.println(i);
       }

                Scanner in = new Scanner(System.in);
                Boolean flag = true;
                While(flag){
                    System.out.println(“new operation”);
                                        System.out.print(“Enter num1 :”);
                                        Int num1 = in.nextInt();
                                        System.out.print(“Enter num2:”);
                                        Int num2 = in.nextInt();
                                     System.out.print(“Enter operator :”);
                                     Char op = in.next().charAt(0);
                                     System.out.print(“output is :”);
                    Switch(op){
                        Case ‘+’:
                            {
                              System.out.println(num1+num2); 
                              Break;
                            }
                              Case ‘-‘:
                            {
                              System.out.println(num1-num2); 
                              Break;
                            }
                              Case ‘*’:
                            {
                              System.out.println(num1*num2); 
                              Break;
                            }
                              Case ‘/’:
                            {
                              System.out.println(num1/num2); 
                              Break;
                            }
                              Case ‘%’:
                            {
                              System.out.println(num1%num2); 
                              Break;
                            }
                            Default :{
                                System.out.println(“Invalid operator”);
                                Break;
                            }
                    }
                    System.out.print(“Do u need to continue : (Y / N)”);
                    Char k = in.next().charAt(0);
                    If(k != ‘y’){
                        Flag = false;
                    }
                }
                Scanner l = new Scanner(System.in);
                Boolean flag = true;

                    System.out.println(“      MENU      “);
                                        System.out.println(“1.Login”);
                                        System.out.println(“2.Sign in”);
                                        System.out.println(“3.Logout”);
                Do 
                {

                                     Int a=l.nextInt();
                    Switch(a){
                        Case 1:
                            {
                              System.out.println(“ Account Login successfully”); 
                              Break;
                            }
                              Case 2:
                            {
                              System.out.println(“Account Signed successfully “); 
                              Break;
                            }
                              Case 3:
                            {
                              System.out.println(“Account Logout successfully”); 
                              Break;
                            }

                            Default :{
                                System.out.println(“Invalid option”);
                                Break;
                            }
                    }
                    System.out.print(“Do u need to continue : (NEXT/ EXIST)”);
                    String k = l.next();
                    If(k !=”NEXT” ){
                        Flag = false;
                    }
                }
                While(flag);





                /*

                Int k = 4;
                For(int i=0;i < k;i++){
                    For(int j = 1; j<= k-i;j++){
                        System.out.print(j + “ “);
                    }
                    System.out.println();
                }

        Int rows = 5;

        For (int i = 1; i <= rows; i++) {

            For (int j = i; j < rows; j++) {
                System.out.print(“ “);
            }

            For (int k = 1; k <= (2 * i – 1); k++) {
                System.out.print(“*”);
            }
            System.out.println();
        }
Int rows = 4;

        For (int i = 1; i <= rows; i++) {

            For (int j = 0; j <=rows-i; j++) {
                System.out.print(“*”);
            }
            System.out.println();
            }
        Scanner r=new Scanner(System.in);
        Int n=r.nextInt();
            For(int i=0;i<n;i++)
            {
                For(int j=0;j<n;j++)
                {
                    If(i==j||i+j==n-1)
                    {
                        System.out.print(“*”);

                    }
                    Else 
                    {
                        System.out.print(“ “);
                    }
                }
                System.out.println();
            }

            Int rows = 5;

        For (int i = 1; i <= rows; i++) {

            For (int j = 1; j <= (rows-i)*2; j++) {
                System.out.print(“ “);
            }

            For (int k = 1; k <=i ; k++) {
                System.out.print(k+” “);

            }
            System.out.println();
        }

        Int r = 4; 
        Int n = 1;

        For (int i = 1; i <= r; i++) {
        For (int j = 1; j <= (r-i)*2; j++) {
                System.out.print(“*”);
            }

            For (int j = 1; j <= i; j++) {
                System.out.print(n +”*”);
                N++;
            }
            System.out.println(); 
        }
        Int sum=0;
        Int r=101;
        //while(i<0)
        For(int i=0;i<r;i++)
        {
            If(i%2==0)

            Sum+=i;
        }
        System.out.println(sum);

//Digit manipulation
Int num=5294;int rev=0;
While(num>0)
{
    Int digit =num%10;
    Rev=rev*10+digit;
    Num/=10;
}
System.out.println(rev);


Int num=5294;int rev=0;
While(num>0)
{
    Int digit =num%10;
    Rev=rev+digit;
    Num/=10;
}
System.out.println(rev);
*/
While(num>0)
{
    Int digit =num%10;
    Rev=rev+digit;
    Num/=10

         }

}
