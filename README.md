public class Recur{
    public static int sum (int k){ //Starting a method
        if (k>0){
        return k+sum (k-1);
        }else{
        return 0;
    }
}
    public static void main(String[] args){
        int result = sum(10);
        System.out.println(result);
    }
}
 
