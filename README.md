# Addtion-Matrix
public class AdditionMatrix {

	public static void main(String[] args)  {
		// TODO Auto-generated method stub
		int [][] a={{4,5,8},{6,8,3}};
		int [][] b={{6,7,9},{2,6,7}};
		for(int i=0;i<2;i++)
		{
			for(int j=0;j<=2;j++)
			{
				int d=a[i][j]+b[i][j];
				System.out.print(d+" ");
			}
			System.out.println();
		}

	}

}
