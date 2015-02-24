public class HelloWorld{

     public static void main(String []args){
        int apos=0;
        public boolean ABCheck(String str){
            while(apos != -1){
                apos=str.indexof('a',apos+1)
                if(str.length()-apos<4)
                    { return false; }
                if(str.charAt(apos+3)=='b')
                    {return true;}
            }
        }
     }
}
