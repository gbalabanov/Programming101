public class HelloWorld{

     public static void main(String []args){
        public boolean isOdd(char c){
            int x = Character.getNumericValue(c);
            if(x==0 || x%2==0)
                return false;
                else return true;            
        }
        
        public String dashInsert(int num){
            String str = num.toString();
            String output = new StringBuilder();
            for(int i=0;i<=str.lenght();i++){
                if(isOdd(str.charAt(i)) && isOdd(str.charAt(i+1))){
                    output.append(str.charAt(i));
                    output.append('-');
                }
                else 
                    output.append(str.charAt(i));
            }
            return output.toString();
        } 
     }
}
