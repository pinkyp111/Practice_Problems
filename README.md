public class Factorial{
    int n=5;
    public void findfactorial(){
        int product=1;
        for(int i=n;n>0;n--){
            product*=n;

        }
        System.out.println(product);
        
    }
    public static void main(String args[]){
        Factorial ft = new Factorial();
        System.out.println("Factorial of a number::");
        ft.findfactorial();
    }
}
-------------------------------------------------------------
