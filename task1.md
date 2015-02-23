public class HelloWorld{

     public static void main(String []args){
        int xcount,ocount;
        public boolean ExOh(String str){
            for(int i=0;i<=str.length();i++){
                if(str.charAt(i)=='x')
                    xcount++;
                else
                    ocount++;
            }
            if(xcount==ocount)
                return true;
            else return false;
        }
     }
}
