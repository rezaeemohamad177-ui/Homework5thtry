

Q1: writte a program that shows diffrence between cin and getline?
*****************************************
string a ,b;
cout << "enter with cin";
cin>>a;
cin.ignore();
cout << "enter with getline:";
getline(cin,b)
cout << "result of cin:"<<a<<endl;
cout << "result of getline:"<<b<<endl;
return 0;
**************************************
q2: write a program that take 3 dicimal numbers and (+) them?
float num1 , num2, sum;

cout << "etnter the first number:";
cin>>num1;
cout << "enter the second number:";
cin>>num2;
sum =num1+num2;
cout << "the sum is ="<<sum;
return 0;
}
****************************
Q3: ascii code of a character?
 char ch;
   cout<< "enter a character:";
   cin>>ch;
   cout << "ascii code="<<int(ch)<<endl;
   return 0;
*****************
Q4:perimeter of a aquare?
    double side;

   double perimeter;
   double doubled;

   cout<< "enter side of square:";
   cin>>side;
   perimeter =4*side;
   doubled = perimeter*2;

   cout << "perimeter ="<<perimeter<<endl;
   cout << "double perimeter="<<doubled<<endl;

   return 0;
*******************
Q5:rectangle with lenght and width?

      double length,width,area;
       cout << "enter length:";
       cin>>length;
       cout << "enter width:";
       cin>>width;
       area=length*width;
       cout << "area of rectangle ="<<area<<endl;
       return 0;
********************
Q6: power of a number ?
 double base,power,result;
        cout << "base number:";
        cin>>base;
        cout << "enter power number:";
        cin>>power;
        result =pow(base,power);
        cout << "result="<<result<<endl;
        return 0;
**************************
Q7: by using pi constant, result be the area of circle?
  double radius,area;
         cout << "enter radius:";
         cin >>radius;
         area = pi*radius*radius;
         cout << "area of circle="<<area<<endl;
         return 0;
****************
Q8:showing a text with getline?
  
               string sentence;
               cout << "enter a sentence:";
               getline(cin,sentence);
               cout << "sentence="<<sentence<<endl;
               return 0;
***********************
Q9: SQTR of a number, getting the number by user?
 

               double number, result;
               cout << "enter a non negative number:";
               cin>>number;
               result =sqrt(number);
               cout << "square root ="<<result<<endl;
               return 0;
************************
Q10:odd and even of a number?
  /* int number;
               cout << "enter a number:";
               cin>>number;
               if (number %2==0)
               {
                   cout << "number is even"<<endl;

               }
               else
               {
                   cout << "number is odd"<<endl;

               }
               return 0;
******************
Q11 :  using the opreator of > and power it?
    double a, b;
               cout << "enter first number :";
               cin>>a;
               cout << "enter second number  :";
               cin>>b;

                   if (a>b)
                   {
                       cout << "first is greater ."<<endl;

                   }
                    else if (b>a)
                    {
                        cout << "second number is greater."<<endl;


                    }
                else
                {
                    cout << "both number are equal."<<endl;

                }

                  double a2 =pow(a,2);
                  double b2 =pow(b,2);
                  cout << "square of first number ="<<a2<<endl;
                  cout << "square of second number ="<<b2<<endl;
                  return 0;
********************************
Q12: using :? to find the bigest number?
     int a, b;
                  cout << "enter the first number:";
                  cin>>a;

                  cout << "enter the second number:";
                  cin>>b;
                  int greater=(a>b)? a:b;
                  cout << "greater number:" <<greater<<endl;
                  return 0;
*****************************
Q13: getting the name and age of user and print out a welcome text?

                  string name;
                  int age;

                  cout << "enter your name:";
                  cin>>name;
                  cout << "enter your age:";
                  cin>>age;
                  cout << "welcome "<<name<< "!"<<endl;
                  cout << "you are "<<age<< "years old."<<endl;
                  return 0;
********************************
Q14: arrange the three number from the big up to small?
  int a,b,c,temp;


                   cout << "enter first number:";
                   cin>>a;

                   cout << " enter second number:";
                   cin>>b;

                    cout << "enter the third number:";
                    cin>>c;

                    if (a>b){
                        temp =a;
                        a=b;
                        b =temp;

                    }
                    if (a>c){
                        temp =a;
                        a=b;
                        b =temp;

                    }
                    if (b>c){
                        temp =b;
                        b =c;
                        c =temp;

                    }
                    cout << "number in descending order:";
                    cout <<a<<" "<<b<< " "<<c<<" "<<endl;
                    return 0;
*******************************************
Q15:  using the size of showing the size of int?

                    cout << "size of int:"<<sizeof(int)<<"bytes"<<endl;
                    return 0;
***************************************
Q16:  a program that calculate the math question?

                    cout << "size of int:"<<sizeof(int)<<"bytes"<<endl;
                    return 0;

                    int a,b,c;

                     cout << "enter first number:";
                     cin>>a;

                      cout << "enter second number:";
                      cin>>b;

                      cout << "enter third number:";
                      cin>>c;
                      int result = a+b*c;
                      cout << "result ="<<result<<endl;
                      return 0;
***********************************
Q17: a program that count everything of a sentence?
 string text;

                      cout << "enter a text:";
                      getline(cin,text);
                      int count=text.length();
                      cout << "total characters:"<<count<<endl;
                      return 0;
*******************************
Q18: program that calculate the question?
                   
                        double result;

                       result= 1-2.0/4*3+2;
                       cout << "result=" << result<< endl;
                       return 0;


*******************************
Q19: program that take the radius and print the area?
  
                       double r, area;
                       cout << "input radius: ";
                       cin >> r;
                       area = 3.14 * r * r;
                       cout << area;

******************************
Q20: program that take 4 number and print each of them by individual?
                      string number;
                       cout << "enter 4 digit number:";
                       cin>>number;
                       cout << number[0]<< endl;
                        cout << number[1]<< endl;
                         cout << number[2]<< endl;
                          cout << number[3]<< endl;
                          return 0;
**********************************
Q21: use the ~ on a number?
                         int num;
                        cout << "enter a number: ";
                        cin >> num;
                        cout << ~num << endl;
*********************************
Q22:wirte a program that gets oponion of a user about a product include the sppaces?
                      string text;
                        cout << "enter the product name:";
                        string product;
                        getline(cin,product);
                        system("cls");
                        cout << product<<endl;
                        cout << "enter your oponion:";
                        getline(cin,text);

                        cout << "fedback:" << text<<endl;

                        return 0;
**********************************
Q23: write a program that shows average of three numbers?
                      float num1,num2,num3;

                        cout << "enter three numbers :";
                        cin>>num1>>num2>>num3;
                        double avg = (num1 + num2 + num3) / 3;
                        cout <<  "average is ="<<avg << endl;
********************************
Q24: the program that take the number and check that is it divisavle by 5 ?
                         int num;
                          cout << " enter a number:";
                          cin>>num;
                          if (num % 5 == 0){
                            cout << "Devisible and % is: ";
                            cout << num % 5;
                          }
                          else {
                            cout << "not Devisible AND % is : ";
                            cout << num % 5;
                          }

**********************************
Q25:gets two int number and shows wich one is small?
			 int num1,num2;
                          cout<< "enter two number: ";
                          cin>>num1>>num2;

                          if (num1>num2)
                          {
                              cout << num2 <<"is smaller";
                          }
                          else
                          {
                               cout<< num1<<"is smaller";

                          }
*********************************
Q26: write a program that checks if a number is in interval of [10 -20]?
                 int num;
                        cout << "enter a number:";
                        cin >> num;
                        if (num >= 10 && num <= 20){
                            cout << "number is included.";
                        }
                        else
                            cout << "not included.";
*****************************
Q27: enter a program that gets three numbers and show te largest?
                        int num1,num2,num3;
                        cout << "enter three numbers: ";
                        cin>>num1>>num2>>num3;
                        if(num1 > num2 && num1 > num3){
                            cout << "the biggest is " << num1;
                        }
                        else if(num2 > num1 && num2 > num3){
                            cout << "the biggest is " << num2;
                        }
                        else
                            cout << "the biggest is " << num3;
***********************************
Q28:getting the user info and say welcome?
                            string user;

                            cout<< "enter your name;";
                            cin>>user;
                            cout<< "welcome user " << user;


***************************************
Q29: write a program that shows difference between = and ==
			int num = 5;
                        if (num == 5){
                            cout << "true";
                        }
***********************************
Q30:write a program that reverses a number's values?
			/*string num;
                        cout << "enter a number: ";
                        cin >> num;
                        reverse(num.begin(),num.end());
                        cout << num;
*******************************************
Q31:  /*int a,b,c,max;

                         cout << "enter the first number:";
                         cin>>a;

                         cout << "enter the second number:";
                         cin>>b;
                         cout << "enter the third number:";
                         cin>>c;

                         max =(a>b)?((a>c)?a:c):((b>c)?b:c);

                         cout << "largest number is "<<max;
                         return 0;
****************************************
Q32: ABS of a number?

                     int num;

                         cout << "enter a number:";
                         cin>>num;
                         if (num<0)
                            num= -num;

                            cout << "abs is :"<<num;
                         return 0;
****************************************
Q33:program that find the sin of a degree?
                           double degree,radian;
                          cout << "enter the angle in degree:";
                          cin>>degree;

                          radian = degree*3.14159/180;
                          cout << "sin ="<<sin(radian);
                          return 0;

************************************
Q34: print the name and last name of a person?
                        string name="tawfiq ";
                        string lname="rezaee";
                        cout <<name +lname;
                         return 0;
**************************************
Q35: program that get a 8 number code and prin that code is accepted /if not :print error?

                      string password;
                         cout << "enter a password:";
                         cin>>password;

                         if (password.length()<8)
                            cout << "error:password must be at least 8 characters";
                         else
                            cout << "password is accepted.";
                         return 0;

****************************************
Q36: program that calculate the 3 root of a number and print out three time the root?

                          double num,root;

                         cout << "enter a number :";
                         cin>>num;
                         root=cbrt(num);

                         cout << root<<endl;
                          cout << root<<endl;
                           cout << root<<endl;
                           return 0;
*************************************
Q37: take a dicimal number and R O it?

              
                               double num;
                               cout << " enter a decimal number: ";
                               cin>>num;

                               cout << "rounded number="<<round(num);
                               return 0;

******************************************
Q38: enter a number that count the power 2 and 3 of a number?
                   double num;

                           cout << "enter a number:";
                           cin>>num;


                           cout << "square="<<pow(num,2)<<endl;
                           cout << "cube="<<pow(num,3)<<endl;
                           return 0;
************************************
Q39: program that use & and | on a number?
                    
                          int a, b;
                               cout << "enter first number:";
                               cin>>a;

                               cout << "enter the second number:";
                               cin>>b;

                               cout << "bitwise AND (&)="<<(a&b)<<endl;
                               cout << "bitwise OR (|)="<<(a|b);
                               return 0;
***********************************
Q40: program that use & on a address and print it?

                      
                               int num ;
                               cout << "enter a number:";
                               cin >>num;
                               cout << "value = "<<num<<endl;
                               cout << "address = "<< &num;
                               return 0;
****************************************************
Q41:program that shows the * and count%?
                      int a,b;
                               cout << "enter first number:";
                               cin >>a;

                               cout << "enter second number:";
                               cin >>b;

                               cout << "multiplication = "<<a*b<<endl;
                               cout << "remainder ="<<a%b;
                               return 0;
***********************************************************
Q42:take a number and chanage it to baionary?
                       

                        int num,binary[32],i=0;
                               cout << "enter a number:";
                               cin >>num;
                               while (num>0)
                               {
                                   binary[i]= num%2;
                                   num =num /2;
                                   i++;

                               }
                               cout << "binary =";
                               for (int j=i-1;j>=0;j--)
                               {
                                   cout << binary [j];

                               }



************************************************
Q43: a program that define a unsingned int and give it a negative number?

                         
                                   int n;
                              cout <<"enter a number:";
                               cin>> n;
                               unsigned int x= n;
                               cout <<"unsigned is ="<< x;
                               return 0;
*****************************************************
Q44:a program that calculate the given numbers?

                          int n;
                               double sum =0;
                               cout << "enter n:";
                               cin >>n;
                               for (int i=1;i<=n;i++)
                               {
                                   sum +=1.0/i;

                               }
                               cout << "sum ="<<sum;
                               return 0;




****************************************
Q45:a program tha print never complain and never explain?

                               cout << "never complain" <<endl;
                               cout << "never explain" <<endl;
************************************************************

Q46:a program that shows a person can drive?

                     int age;
                               cout << "enter your age:";
                               cin >>age;
                               if (age >=18)
                                cout << "you can drive";
                               else
                                cout << "sorry,you are under age!!";
                               return 0;
******************************************************

Q47: a program that show the short int and SHRT_MAX SHRT_MIN?



                          cout << "short int range:"<<endl;
                               cout << "MIN ="<<SHRT_MIN<<endl;
                               cout << "MAX ="<<SHRT_MAX<<endl;
                               return 0;
                               



**********************************
Q48:a program that compair the number wiht and with out qaws?
                       double a,b,c ;
                               cout << "enter a:";
                               cin >>a;
                                  cout << "enter b:";
                               cin >>b;
                                  cout << "enter c:";
                               cin >>c;

                               cout << "without parentheses (a/b*c)="<<a/b*c<<endl;
                               cout << "with parentheses (a/(b*c))="<<a/(b*c)<< endl;
                               return 0;
*****************************************************
Q49:a program that arange the numbers from rigth to left?

                                 int num ;
                               cout << "enter a number :";
                               cin >>num;
                               while (num >0)
                               {
                                   cout << num%10<<endl;
                                   num =num/10;

                               }
                               return 0;


*************************************************

Q50:a program that take user name and password from user?
      

                                    string name ,password;
                               cout << "enter name:";
                               cin>>name ;

                               cout << "enter password :";
                               cin >>password;

                               if (name =="admin"&&password=="1234")
                                cout << "login successful";
                               else
                               cout << "invalid name or password";
                               return 0;

**********************************************************



      














