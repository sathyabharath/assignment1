package gsc;

public class Star {

	/**
	 * @param args
	 */
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int i,j;
		for(i=7;i>0;i--)
		{
			
			
			for(j=0;j<i;j++){	
			System.out.print("* ");
			}
			
			
			System.out.print("\n");
			
			
			for(j=7;j>=i;j--){
				System.out.print(" ");
				}
			
		}
		

	}

}

