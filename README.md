# Railway-Ticket-Booking-Project
The Railway Ticket Booking System is a Java-based console application for booking tickets on the Chennai Beach Train. It offers an interactive menu to choose destinations, travel times, and payment methods, verifies payments, and generates tickets with passenger details for a seamless booking experience.
package RandomProjects;

import java.util.Scanner;

public class RailwayTickect {
	public static void main(String[] args) {
		System.out.println("WELCOME TO CHENNAI BEACH TRAIN");
		System.out.println("Select the Destination:");
		System.out.println("1)Chennai Park" + " " + "2)Chennai Fort" + " " + "3)Chennai Beach");
		Scanner sc = new Scanner(System.in);
		int i = sc.nextInt();
		if (i == 1) {
			System.out.println("Chennai Park");
			System.out.println("1) 10.00AM" + " " + "2) 6.00PM");
			int n = sc.nextInt();
			if (n == 1) {
				System.out.println("10.00AM");
				System.out.println("1) Cash" + " " + "or" + " " + "2) UPI");
				int m = sc.nextInt();
				if (m == 1) {
					System.out.println("Cash");
					System.out.println("Pay your cash Payment 0f Rs.20");
					System.out.println("1)Received" + " " + "2)Not Received");
					int o = sc.nextInt();
					if (o == 1) {
						System.out.println("Amount Received");
						System.out.println("Have Your Ticket");
					} else if (o == 2) {
						System.out.println("Amount Not Received, TRY AGAIN!!!");
					} else {
						System.out.println("Payment Cancel");
					}
				} else if (m == 2) {
					System.out.println("UPI");
					System.out.println("Pay your Cash using Mobile Banking 0f Rs.20 using This UPI id:sathishupi@513");
					System.out.println("1)Received" + " " + "2)Not Received");
					int o = sc.nextInt();
					if (o == 1) {
						System.out.println("Amount Received");
						System.out.println("Have Your Ticket");
					} else if (o == 2) {
						System.out.println("Amount Not Received, TRY AGAIN!!!");
					} else {
						System.out.println("Payment Cancel");
					}
				} else {
					System.out.println("Access Denied");
				}
			} else if (n == 2) {
				System.out.println("6.00PM");
				System.out.println("1) Cash" + " " + "or" + " " + "2) UPI");
				int m = sc.nextInt();
				if (m == 1) {
					System.out.println("Cash");
					System.out.println("Pay your cash Payment 0f Rs.20");
					System.out.println("1)Received" + " " + "2)Not Received");
					int o = sc.nextInt();
					if (o == 1) {
						System.out.println("Amount Received");
						System.out.println("Have Your Ticket");
					} else if (o == 2) {
						System.out.println("Amount Not Received, TRY AGAIN!!!");
					} else {
						System.out.println("Payment Cancel");
					}
				} else if (m == 2) {
					System.out.println("UPI");
					System.out.println("Pay your Cash using Mobile Banking 0f Rs.20 using This UPI id:sathishupi@513");
					System.out.println("1)Received" + " " + "2)Not Received");
					int o = sc.nextInt();
					if (o == 1) {
						System.out.println("Amount Received");
						System.out.println("Have Your Ticket");
					} else if (o == 2) {
						System.out.println("Amount Not Received, TRY AGAIN!!!");
					} else {
						System.out.println("Payment Cancel");
					}
				} else {
					System.out.println("Access Denied");
				}
			} else {
				System.out.println("No Trains");
			}
		} else if (i == 2) {
			System.out.println("Chennai Fort");
			System.out.println("1) 4.00PM" + " " + "2) 7.00PM");
			int n = sc.nextInt();
			if (n == 1) {
				System.out.println("4.00PM");
				System.out.println("1) Cash" + " " + "or" + " " + "2) UPI");
				int m = sc.nextInt();
				if (m == 1) {
					System.out.println("Cash");
					System.out.println("Pay your cash Payment 0f Rs.30");
					System.out.println("1)Received" + " " + "2)Not Received");
					int o = sc.nextInt();
					if (o == 1) {
						System.out.println("Amount Received");
						System.out.println("Have Your Ticket");
					} else if (o == 2) {
						System.out.println("Amount Not Received, TRY AGAIN!!!");
					} else {
						System.out.println("Payment Cancel");
					}
				} else if (m == 2) {
					System.out.println("UPI");
					System.out.println("Pay your Cash using Mobile Banking 0f Rs.30 using This UPI id:sathishupi@513");
					System.out.println("1)Received" + " " + "2)Not Received");
					int o = sc.nextInt();
					if (o == 1) {
						System.out.println("Amount Received");
						System.out.println("Have Your Ticket");
					} else if (o == 2) {
						System.out.println("Amount Not Received, TRY AGAIN!!!");
					} else {
						System.out.println("Payment Cancel");
					}
				} else {
					System.out.println("Access Denied");
				}
			} else if (n == 2) {
				System.out.println("7.00PM");
				System.out.println("1) Cash" + " " + "or" + " " + "2) UPI");
				int m = sc.nextInt();
				if (m == 1) {
					System.out.println("Cash");
					System.out.println("Pay your cash Payment 0f Rs.200");
					System.out.println("1)Received" + " " + "2)Not Received");
					int o = sc.nextInt();
					if (o == 1) {
						System.out.println("Amount Received");
						System.out.println("Have Your Ticket");
					} else if (o == 2) {
						System.out.println("Amount Not Received, TRY AGAIN!!!");
					} else {
						System.out.println("Payment Cancel");
					}
				} else if (m == 2) {
					System.out.println("UPI");
					System.out.println("Pay your Cash using Mobile Banking 0f Rs.200 using This UPI id:sathishupi@513");
					System.out.println("1)Received" + " " + "2)Not Received");
					int o = sc.nextInt();
					if (o == 1) {
						System.out.println("Amount Received");
						System.out.println("Have Your Ticket");
					} else if (o == 2) {
						System.out.println("Amount Not Received, TRY AGAIN!!!");
					} else {
						System.out.println("Payment Cancel");
					}
				} else {
					System.out.println("Access Denied");
				}
			} else {
				System.out.println("No Trains");
			}
		} else if (i == 3) {
			System.out.println("Chennai Beach");
			System.out.println("1) 11.00AM" + " " + "2) 2.00AM");
			int n = sc.nextInt();
			if (n == 1) {
				System.out.println("11.00AM");
				System.out.println("1) Cash" + " " + "or" + " " + "2) UPI");
				int m = sc.nextInt();
				if (m == 1) {
					System.out.println("Cash");
					System.out.println("Pay your cash Payment 0f Rs.200");
					System.out.println("1)Received" + " " + "2)Not Received");
					int o = sc.nextInt();
					if (o == 1) {
						System.out.println("Amount Received");
						System.out.println("Have Your Ticket");
					} else if (o == 2) {
						System.out.println("Amount Not Received, TRY AGAIN!!!");
					} else {
						System.out.println("Payment Cancel");
					}
				} else if (m == 2) {
					System.out.println("UPI");
					System.out.println("Pay your Cash using Mobile Banking 0f Rs.200 using This UPI id:sathishupi@513");
					System.out.println("1)Received" + " " + "2)Not Received");
					int o = sc.nextInt();
					if (o == 1) {
						System.out.println("Amount Received");
						System.out.println("Have Your Ticket");
					} else if (o == 2) {
						System.out.println("Amount Not Received, TRY AGAIN!!!");
					} else {
						System.out.println("Payment Cancel");
					}
				} else {
					System.out.println("Access Denied");
				}
			} else if (n == 2) {
				System.out.println("2.00AM");
				System.out.println("1) Cash" + " " + "or" + " " + "2) UPI");
				int m = sc.nextInt();
				if (m == 1) {
					System.out.println("Cash");
					System.out.println("Pay your cash Payment 0f Rs.200");
					System.out.println("1)Received" + " " + "2)Not Received");
					int o = sc.nextInt();
					if (o == 1) {
						System.out.println("Amount Received");
						System.out.println("Have Your Ticket");
					} else if (o == 2) {
						System.out.println("Amount Not Received, TRY AGAIN!!!");
					} else {
						System.out.println("Payment Cancel");
					}
				} else if (m == 2) {
					System.out.println("UPI");
					System.out.println("Pay your Cash using Mobile Banking 0f Rs.200 using This UPI id:sathishupi@513");
					System.out.println("1)Received" + " " + "2)Not Received");
					int o = sc.nextInt();
					if (o == 1) {
						System.out.println("Amount Received");
						System.out.println("Have Your Ticket");
					} else if (o == 2) {
						System.out.println("Amount Not Received, TRY AGAIN!!!");
					} else {
						System.out.println("Payment Cancel");
					}
				} else {
					System.out.println("Access Denied");
				}
			} else {
				System.out.println("No Trains");
			}
		} else {
			System.out.println("No Trains are Available");
		}
		System.out.println("x-------------***Have a Nice Day***---------------x");

	}

}
