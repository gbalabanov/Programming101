# Programming101
public class HelloWorld{

     public static void main(String []args){
        public double fill_tetrahedron(int a){
        return a*1.1782;    
        }
        
        public int tetrahedron_filled(int[] tetrahedrons, int water){
            int sum=0;
            for (int i = 0; i < tetrahedrons.length(); i++) {
                for(int j = 0; j < tetrahedrons.length(); j++) {
                        if(numbers[i] > numbers[j + 1])
                        {   
                            temp = tetrahedrons[j + 1];
                            tetrahedrons[j + 1]= tetrahedrons[i];
                            tetrahedrons[i] = temp;
                        }
                    }
            }
            for(i=0;i<=tetrahedrons.length();i++) {
                sum+=fill_tetrahedron(tetrahedrons[i]);
                if(sum>water) {
                    return i;
                }
                return tetrahedrons.lenght();
            }
        }
     }
}
