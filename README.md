# Project-Scholarship
[![Open in Codespaces] (https://github.dev/BoiMegadonutstheguy/Project-Scholarship)]
This is a fun school project that simplifies school notes


package tasks;

import java.util.Scanner;

public class UsefulTasks {

	public static Object obtainInput(int choice) {
		Scanner scan = new Scanner(System.in);
		String response = scan.nextLine();
		scan.close();
		switch (choice) {

		case 1:{
			int returnitem = Integer.parseInt(response);
			return returnitem;
		}
		case 2:{
			Double returnitem = Double.parseDouble(response);
			return returnitem;
		}
		default:{
			String returnitem = response;
			return returnitem;
		}
		}

	}
}
