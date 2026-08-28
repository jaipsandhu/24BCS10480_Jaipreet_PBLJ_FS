public class CLASS_1 {
    public static void main(String[] args){
        String a="new";                        
        String b=a;                            
        String c="new";
        String e="mark me";
        String d=new String("mark me");

        System.out.println(a==b);
        System.out.println(a==c);
        System.out.println(e==d);
        System.out.println(e.equals(d));
    }
}