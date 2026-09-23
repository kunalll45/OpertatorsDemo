void add(int a, int b) {
    int sum = a + b;
    System.out.println("Addition: " + sum);
}
// Method with return value
int multiply(int a, int b) {
    return a * b;
}
   public static void main(String[] args) {

    // Arithmetic promotion
    byte a = 69;
    byte b = 20;
    int result = a + b;
    System.out.println("Arithmetic Promotion result: " + result);
    // Arithmetic operators
    int x = 54 , y = 85;
    

    System.out.println("x + y = " + (x + y));
    System.out.println("x - y = " + (x - y));
    System.out.println("x * y = " + (x * y));
    System.out.println("x / y = " + (x / y));
    System.out.println("x % y = " + (x % y));

    // Method calling
    OperatorsDemo obj = new OperatorsDemo();

    obj.add(5, 7);

    int product = obj.multiply(4, 6);
    System.out.println("Multiplication: " + product);
    
int c = 0;
int d = 6;
int sum = c + d;
System.out.println("Sum of these two numbers : "+sum);

}
