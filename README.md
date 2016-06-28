package TEST;

import java.util.Scanner;

//import java.util.Random;

public class Test{
	public static void main(String [] args){
		System.out.print("请输入一个数：");
		Scanner s=new Scanner(System.in);
		int x=s.nextInt();
		if(x%2!=0){
			System.out.print(x+"为奇数");
		}
		else {
			System.out.print(x+"为偶数");
		}
	}
}

#奇数偶数的判定
