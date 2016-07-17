# JavaSess4Ass1
package Basic;

public class Sess4Ass1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		int arr[];
		
		arr=new int[10];
		
		arr[0]=11;
		arr[1]=22;
		arr[2]=33;
		arr[3]=44;
		arr[4]=55;
		arr[5]=66;
		arr[6]=77;
		arr[7]=88;
		arr[8]=99;
		arr[9]=111;	

		System.out.println("Correct order");
		for(int i=0;i<arr.length;i++){
			System.out.println(arr[i]);
		}

		System.out.println();
		System.out.println("Reverse order");
		for(int i=arr.length-1;i>=0;i--){
			System.out.println(arr[i]);
		}
		
	}

}
