# turboo#include<iostream>
using namespace std;  
int main()
{
    int a,b,c,d,p,s,i;
    char ch;
    p=500;
    b=200;
    i=100;
    s=300;
    mm:
    	
    system("color  6a");
    cout<<"**************************************************RESTURANT MANGMENT SYSTEM************************************************"<<endl;
    
    cout<<"1.Menu"<<endl;
    cout<<"2.Sitting Area"<<endl;
    cout<<"3.Staff Management"<<endl;
    cout<<"4.Exit"<<endl;
    cout<<"enetr your choice";
    cin>>ch;
    if(ch=='1')
{
	 system("cls");   
    cout<<endl<<"          +++++++++++++++++++++++++++++++++++++++MENU++++++++++++++++++++++++++++++++++++++++++++++++     "<<endl;
    cout<<"1.Burger=200"<<endl;
    cout<<"2.Pizza =500"<<endl;
    cout<<"3.Ice Cream=100"<<endl;
    cout<<"4.Shake =150"<<endl;
    cout<<"5.Exit"<<endl;
    cout<<"Select your order:"<<endl;
    cin>>a;
    switch(a)
    {
	
            case 1: 
			 cout<<"selected order Burger:"<<endl;
			 cout<<"enter the number of items:"<<endl;
			 cin>>b;
			 cout<<"your order ready in 15 minutes:"<<endl;
			 cout<<endl<<"your total bil is="<<b*200<<endl;
			 break;
			       case 2:
			           cout<<"selected order Pizza"<<endl;
			            cout<<"enter the  number of  items"<<endl;
			            cin>>p;
			            cout<<"your order ready in 15 minutes"<<endl;
			            cout<<endl<<"your total bil is="<<p*200<<endl;
			             break;
			                  case 3:
			                    cout<<"selected order is ice cream" <<endl;
			                    cout<<"enter the of items"<<endl;
			                     cin>>i;
                                 cout<<"your order ready in 15 minutes"<<endl;
			                     cout<<endl<<"your total bil is="<<i*100<<endl;
			 
			                     break;
			                            case 4:
			                            cout<<"selected order is shake"<<endl;
			                            cout<<"enter the of items"<<endl;
			                            cin>>s;
			                            cout<<"your order ready in 15 minutes"<<endl;
			                            cout<<endl<<"your total bil is="<<s*150<<endl;
			 
			                           break;
			                                   case 5:
			                                   cout<<"praogram is END"<<endl ;
			                                   break;
			                                       default:
			                 
							                           cout<<"Invalid Choice"<<endl;
			                                           cout<<"please select the Right one......."<<endl ;
			                        
		
		
		}
		
}
//sitting area
else if(ch=='2')
{  
    system("cls");
    cout<<endl<<"    *******************************************SITTING AREA************************"<<endl;
   cout<<" 1.table no 1"<<endl;
   cout<<"2.table no2"<<endl;
   cout<<"3.table no 3"<<endl;
   cout<<"4.table no4"<<endl;
   cout<<"enter the number odf table"<<endl;
   cin>>c;
   switch(c)
   {
   	
   	case 1:
   		cout<<"table for family"<<endl;
   	    break;
   	    case 2:
   	    	cout<<"table for couple"<<endl;
   	    	break;
   	    	case 3:
			  
   	    		cout<<"table for single person"<<endl;
   	    		break;
   	    		case 4:
   	    			cout<<"table for date"<<endl;
   	    			break;

   	  }	
}
// staff managment
else if(ch=='3')
{
	
	system("cls"); 
	cout<<"***************************************STAFF MANGMENT*********************************************"<<endl;
cout<<"1.No  of Waiters"<<endl;
cout<<"2.No of Sweepers"<<endl;
cout<<"3.No of Cheff"<<endl;
cout<<"4. No of manager"<<endl;
cout<<"5.salary of per waiter"<< endl;
cout<<"6.salary of per sweeper "<<endl;
cout<<"7.salary of Cheff"  <<endl;
cout<<"8.salary of manager"<<endl;
cout<<"what you want to check"<<endl;
cin>>d;
switch(d)

{
	case 1:
		cout<<"There are ten waiter in resturant"<<endl;
		break;
		case 2:
			cout<<"There are five sweeper"<<endl;
			break;
			case 3:
				cout<<" Two cheff"<<endl;
				break;
			case 4:
				cout<<" One manger"<<endl;
				break;
				case 5:
					cout<<"Salary of per waiter = 12000 to 14000"<<endl;
					break;
					case 6:
						cout<<"Salary of per sweeper= 4000 to 5000"<<endl;
						break;
						case 7:
							cout<<"Salary of cheff is= 25000"<<endl;
							break;
							case 8:
								cout<<"salary of manger is = 40000"<<endl;
								break;
								
		
}

}


else if (ch=='4')

{
	
	return 0;
}
else 
cout<<"wrong input"<<endl;
goto mm;
return 0;			
}
