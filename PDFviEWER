import java.util.Scanner;


public class Euler {

	/**
	 * @param args
	 */
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		 
		        Scanner in = new Scanner(System.in);
		        int h[] = new int[]{1, 3, 1, 3, 1, 4, 1, 3, 2, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5};
		        int h1[]= new int[26];
		        int k=0;
		        String word = in.next();
		        int breadth=word.length();
		        char ch;
		        for(int i=0;i<breadth;++i){
		            ch=word.charAt(i);
		            int index=ch-97;
		            // now try to map this index to an array and then sort it in descecning order to find the maximum
		            h1[k++]=h[index];
		        }
		        int n = h1.length;  
		        int temp = 0;  
		         for(int i=0; i < n; i++){  
		                 for(int j=1; j < (n-i); j++){  
		                          if(h1[j-1] > h1[j]){  
		                                 //swap elements  
		                                 temp = h1[j-1];  
		                                 h1[j-1] = h1[j];  
		                                 h1[j] = temp;  
		                         }  
		                          
		                 }  
		         	
		        }
		        	 System.out.println(h1[25]*breadth);
		          
		    }
}
