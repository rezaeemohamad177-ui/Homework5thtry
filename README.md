# Homework5thtry
...
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
 /*char ch;
   cout<< "enter a character:";
   cin>>ch;
   cout << "ascii code="<<int(ch)<<endl;
   return 0;*/
*****************
Q4:perimeter of a aquare?
    /*double side;

   double perimeter;
   double doubled;

   cout<< "enter side of square:";
   cin>>side;
   perimeter =4*side;
   doubled = perimeter*2;

   cout << "perimeter ="<<perimeter<<endl;
   cout << "double perimeter="<<doubled<<endl;

   return 0;*/
*******************
Q5:rectangle with lenght and width?

      /* double length,width,area;
       cout << "enter length:";
       cin>>length;
       cout << "enter width:";
       cin>>width;
       area=length*width;
       cout << "area of rectangle ="<<area<<endl;
       return 0;*/
********************
Q6: power of a number ?
/* double base,power,result;
        cout << "base number:";
        cin>>base;
        cout << "enter power number:";
        cin>>power;
        result =pow(base,power);
        cout << "result="<<result<<endl;
        return 0;*/
**************************
Q7: by using pi constant, result be the area of circle?
  /*double radius,area;
         cout << "enter radius:";
         cin >>radius;
         area = pi*radius*radius;
         cout << "area of circle="<<area<<endl;
         return 0;*/
****************
Q8:showing a text with getline?
  
              /* string sentence;
               cout << "enter a sentence:";
               getline(cin,sentence);
               cout << "sentence="<<sentence<<endl;
               return 0;*/
***********************
Q9: SQTR of a number, getting the number by user?
 

               /*double number, result;
               cout << "enter a non negative number:";
               cin>>number;
               result =sqrt(number);
               cout << "square root ="<<result<<endl;
               return 0;*/
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
     /*int a, b;
                  cout << "enter the first number:";
                  cin>>a;

                  cout << "enter the second number:";
                  cin>>b;
                  int greater=(a>b)? a:b;
                  cout << "greater number:" <<greater<<endl;
                  return 0;*/
*****************************
Q13: getting the name and age of user and print out a welcome text?

                  /*string name;
                  int age;

                  cout << "enter your name:";
                  cin>>name;
                  cout << "enter your age:";
                  cin>>age;
                  cout << "welcome "<<name<< "!"<<endl;
                  cout << "you are "<<age<< "years old."<<endl;
                  return 0;*/
********************************
Q14: arrange the three number from the big up to small?
 /* int a,b,c,temp;


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
                    return 0;*/
*******************************************
Q15:  using the size of showing the size of int?

                    /*cout << "size of int:"<<sizeof(int)<<"bytes"<<endl;
                    return 0;*/
***************************************
Q16:  a program that calculate the math question?

                    /*cout << "size of int:"<<sizeof(int)<<"bytes"<<endl;
                    return 0;*/

                    /*int a,b,c;

                     cout << "enter first number:";
                     cin>>a;

                      cout << "enter second number:";
                      cin>>b;

                      cout << "enter third number:";
                      cin>>c;
                      int result = a+b*c;
                      cout << "result ="<<result<<endl;
                      return 0;*/
***********************************
Q17: a program that count everything of a sentence?
 /* string text;

                      cout << "enter a text:";
                      getline(cin,text);
                      int count=text.length();
                      cout << "total characters:"<<count<<endl;
                      return 0;*/
*******************************
Q18: program that calculate the question?
                   
                       /* double result;

                       result= 1-2.0/4*3+2;
                       cout << "result=" << result<< endl;
                       return 0;*/


*******************************
Q19: program that take the radius and print the area?
  
                       /*double r, area;
                       cout << "input radius: ";
                       cin >> r;
                       area = 3.14 * r * r;
                       cout << area;*/

******************************
Q20: program that take 4 number and print each of them by individual?
                     /* string number;
                       cout << "enter 4 digit number:";
                       cin>>number;
                       cout << number[0]<< endl;
                        cout << number[1]<< endl;
                         cout << number[2]<< endl;
                          cout << number[3]<< endl;
                          return 0;*/
**********************************
Q21: use the ~ on a number?
                        /* int num;
                        cout << "enter a number: ";
                        cin >> num;
                        cout << ~num << endl;*/
*********************************
Q22:wirte a program that gets oponion of a user about a product include the sppaces?
                      /*string text;
                        cout << "enter the product name:";
                        string product;
                        getline(cin,product);
                        system("cls");
                        cout << product<<endl;
                        cout << "enter your oponion:";
                        getline(cin,text);

                        cout << "fedback:" << text<<endl;

                        return 0;*/
**********************************
Q23: write a program that shows average of three numbers?
                      /*float num1,num2,num3;

                        cout << "enter three numbers :";
                        cin>>num1>>num2>>num3;
                        double avg = (num1 + num2 + num3) / 3;
                        cout <<  "average is ="<<avg << endl;*/
********************************
Q24: the program that take the number and check that is it divisavle by 5 ?
                         /* int num;
                          cout << " enter a number:";
                          cin>>num;
                          if (num % 5 == 0){
                            cout << "Devisible and % is: ";
                            cout << num % 5;
                          }
                          else {
                            cout << "not Devisible AND % is : ";
                            cout << num % 5;
                          }*/

**********************************
Q25:gets two int number and shows wich one is small?
			/* int num1,num2;
                          cout<< "enter two number: ";
                          cin>>num1>>num2;

                          if (num1>num2)
                          {
                              cout << num2 <<"is smaller";
                          }
                          else
                          {
                               cout<< num1<<"is smaller";

                          }*/
*********************************