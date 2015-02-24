/* package whatever; // don't place package name! */

import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Ideone
{
	public static void main (String[] args) throws java.lang.Exception
	{
		public String caesar_encrypt(String str, int n){
			int temp;
			String output = new Stringbuilder();
			int diff=0;
			if(n>26) 
				diff=n%26;
			else
				diff=n;
			for(int i=0;i<str.length();i++){
				char temp = (char)str.charAt(i+diff);
				while((temp>='a' && temp<='z') || (temp>='A' && temp<='Z')) {
					if (c > 'Z')
            			output.append((char)(str.charAt(i) - (26-diff)));
        			else
            			output.append((char)(str.charAt(i) + diff));
					if (c > 'z')
            			output.append((char)(str.charAt(i) - (26-diff)));
        			else
            			output.append((char)(str.charAt(x) + diff));
				}
			}
			return output;
			
		}
	}
}
