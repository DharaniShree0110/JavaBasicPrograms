# JavaBasicPrograms
Basic programs

[Uploading addition.java…]()public class addition {
    static public void main(String[] args) {
            int num1 = 5;
            int num2 = 10;
            int sum = num1 + num2;
            System.out.println("The sum of " + num1 + " and " + num2 + " is: " + sum);
    }
}
[Upimport java.util.Scanner;

public class arithmeticoperator {
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();

        //addition
        int add=a+b;

        //subraction
        int sub=a-b;

        //multiplication
        int mul=a*b;

        //division
        int div=a/b;
        float di=(float)a/b;

        //modulo
        int mod=a%b;

        System.out.println(add+" "+sub+" "+mul+" "+div+" "+di+" "+mod);
    }
}
loading arithmeticoperator.java…]()

[Uploading assignmentoperator.java…]()public class assignmentoperator {
    public static void main(String[] args){

        //assignment
        int a =10;

        // += plus equal
        System.out.println(a+=10);

        // -= minus equal
        System.out.println(a-=10);

        // *= multiple equal
        System.out.println(a*=10);

        // /= divide equal
        System.out.println(a/=10);

        // %= modulo equal
        System.out.println(a%=10);
    }
}

[Uploading logicaloperator.java…]()public class logicaloperator {
    public static void main(String[] args){

        //  AND

        // Used in boolean logic only.
        //Short-circuits: If the first condition is false, it doesn't check the second one.
        int a = 50, b = 10;
        if (a > 10 && b > 5) {
            System.out.println("True");
        }
        System.out.println(b); // Output: 10 (b++ not executed)

        //Can be used on integers as a bitwise operator.
        //Also works in boolean expressions, but always evaluates both sides.
        int c = 50, d = 10;
        if (c > 10 & d > 5) {
            System.out.println("True");
        }
        System.out.println(d); // Output: 11 (b++ evaluated even though a > 10 is false)


        //  OR

        //Used only with boolean expressions.
        //Short-circuits: If the first condition is true, it does not check the second.
        int e = 5, f = 10;
        if (e < 10 || f > 5) {
            System.out.println("Condition is true");
        }
        System.out.println(f); // Output: 10 — b++ not evaluated

        //Works with integers as a bitwise OR
        //Can also be used with boolean expressions, but it always evaluates both sides.
        int g = 5, h = 10;
        if (g < 10 | h > 5) {
            System.out.println("Condition is true");
        }
        System.out.println(h); // Output: 11 — b++ IS evaluated

    }
}

[Uploading relationaloperatpublic class relationaloperator {
    public static void main(String[] args){
        int a=10,b=5;

        // == equal
        System.out.println(a==b);

        // > greater
        System.out.println(a>b);

        // < less
        System.out.println(a<b);

        // >= greater than
        System.out.println(a>=b);

        // <= less than
        System.out.println(a<=b);

        // != not equal
        System.out.println(a!=b);
    }
}
or.java…]()

[Uploading ternaryoperator.javaimport java.util.Scanner;

public class ternaryoperator {
        public static void main(String[] args) {
            Scanner sc = new Scanner(System.in);

            // Input two numbers
            int a = sc.nextInt();
            int b = sc.nextInt();

            // Find largest using ternary operator
            int max = (a > b) ? a : b;

            // Output the result
            System.out.println("Largest number is: " + max);
        }

}
…]()

