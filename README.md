
public class science 
{
	public static void main(String[] args)
	{
		File input = new File("params.txt");
		PrintWriter output = new Printwriter("rc.txt");
		while (input.hasNextInt())
		{
			int B = input.hasNextInt();
			while (input.hasNextInt())
			{
				int R = input.hasNextInt();
				while (input.hasNextDouble())
				{
					double C = input.hasNextDouble();
					output.printf(R*C);
					output.printf("velocity: " + C);
				}
			}
		}
	}
}
		

		
