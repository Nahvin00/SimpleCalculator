# include <iostream>
using namespace std;
int main()
{
    char op;
    float num,num1,num2, tot=0, sub=0, mul=0, divi=0; //Declaration of variable
    cout << "Enter operator either + or - or * or /: "; //Prompting users to enter operator
    cin >> op;
    switch(op) //Switch tests the variable op
    {
        case '+': //Case for addition
           cout << "Enter numbers to be added (Enter 0 to End): ";
           cin >> num;
             for(int i=0;num!=0;i++) //Sentinel controlled loop to input multiple numbers
               {cout <<" + "; 
               tot=tot+num;
               cin >> num;}
           cout << "The answer is: " << tot;  //Display of Final Answer  
           break; 

        case '-': //Case for substraction
           cout << "Enter numbers to be substracted (Enter 0 to End): ";
           cin >> num1;
           cout << " - ";
           cin >> num2;
             for(int i=0;num2!=0;i++) //Sentinel controlled loop to input multiple numbers
             { sub=num1-num2;
               num1=sub;
               cout <<" - ";
               cin>>num2;}
           cout << "The answer is: " << sub;    //Display of Final Answer
           break; 
        
        case '*': //Case for multiplication
           cout << "Enter numbers to be muliplied (Enter 0 to End): ";
           cin >> num1;
           cout << " * ";
           cin >> num2;
             for(int i=0;num2!=0;i++) //Sentinel controlled loop to input multiple numbers
             { mul=num1*num2;
               num1=mul;
               cout <<" * ";
               cin>>num2;}
           cout << "The answer is: " << mul;    //Display of Final Answer
           break; 
        
        case '/': //Case for Division
           cout << "Enter numbers to be divided (Enter 0 to End): ";
           cin >> num1;
           cout << " / ";
           cin >> num2; 
             for(int i=0;num2!=0;i++) //Sentinel controlled loop to input multiple numbers
             { divi=num1/num2;
               num1=divi;
               cout <<" / ";
               cin>>num2;}
           cout << "The answer is: " << divi;    //Display of Final Answer
           break; 
        
        default:
            cout << "Error! operator is not correct"; // If the operator is other than +, -, * or /, error message is shown
            break;
    }
    return 0; //Return value of 0
}
