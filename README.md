# Fibonacci-



 class Fibonacci {

    public static void series(int n) {

        int a = 0;

        int b = 1;

        int c = 1;

        for (int i = 1; i <= n; i++) {

            System.out.println(a);

            a = b;

            b = c;

            c = a + b;

        }

    }

    public static void main(String[] args) {

        System.out.println("Fibonacci series");

        series(10);

    }

}

/*

Fibonacci series

0

1

1

2

3

5

8

13

21

34

 */
