import java.util.Scanner;    
public class ATM   
{     
    public static void main(String args[] )  
    {   Scanner sc= new Scanner(System.in);
        
        int balance = 100000;
        int withdraw = 0;
        int deposit = 0;
        
        System.out.println( "ATM INTERFACE"); 
        System.out.println( "Enter the pin");
        int pin;
        pin =sc.nextInt();
        if(pin==2701) {
             System.out.println("Enter the option you want");
        
        while(true)  
        {  
            System.out.println("Choose 1 for Withdraw");  
            System.out.println("Choose 2 for Deposit");  
            System.out.println("Choose 3 for Transfer");  
            System.out.println("Choose 4 for Check Balance");  
            System.out.println("Choose 5 for Transaction History");  
            System.out.println("Choose 6 for EXIT");  

        int choice = sc.nextInt();  
        switch(choice)  
        {  
            case 1:  
                System.out.print("Enter money to be withdrawn:");    
                withdraw = sc.nextInt();  
            if(balance >= withdraw)
            {  
            balance = balance - withdraw;  
            System.out.println("Please collect your money");  
            System.out.println("Available Balance: "+balance);  
         }  
            else
              {  
                  System.out.println("Insufficient Balance");  
                }   
            break;  
   
            case 2:      
                System.out.print("Enter money to be deposited: ");            
                deposit = sc.nextInt();            
                balance = balance + deposit;  
                System.out.println("Your Money has been successfully depsited");  
                System.out.println("Available Balance: "+balance); 
            break;  
            
            case 3:
                System.out.println("Enter the account number");
                int accountNumber = sc.nextInt();  
                System.out.println("Enter IFSC Code");
                int ifscCode = sc.nextInt(); 
                System.out.println("Enter amount to be transferred:");
                int amount = sc.nextInt();
                balance = balance - amount; 
                System.out.println("Available Balance: "+balance); 
            break;
               
            case 4:   
                System.out.println("Balance: "+balance);  
            break;  
            
            case 5:
            System.out.println("Deposit Amount: "+balance);
            System.out.println("Withdraw Amount: "+balance);
            System.out.println("Balance Amount: "+balance);
            break;

            case 6: 
            System.exit(0);   
            }  
        }
        
        }  
        else
        { System.out.println("You entered wrong pin");
    }
    }  
}  
