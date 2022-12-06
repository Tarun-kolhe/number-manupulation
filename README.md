//# number-manupulation
//all programs related like perfect no armstrong no

public class sumofsqure {
	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		System.out.println("enter any value to get sum of squre of each digit");
		int num=sc.nextInt();
		int sum=0;
		int temp=num;
		while(num!=0) {
			int digit=num%10;
			sum=sum+digit*digit;
			num=num/10;	
			
		}
		System.out.println(" the sum of squre of "+temp+" is "+sum);
		
	}

}
