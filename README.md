# working-with-
#include <iostream>
using namespace std;
int main()
{
    int i,ch, sum=0, num[5];
    cout<<"Enter the 5 numbers\n";
    for(i=0;i<5;i++)
    {
    cin>>num[i];
    }
    cout<<"Enter your choice";
    cin>>ch;
    switch(ch)
    {
        case 1: cout<<"Sum Using For Loop";
                for(i=0;i<5;i++)
                {
                    sum=sum+num[i];
                } 
                cout<<"sum is:"<<sum;
                break;
        case 2: 
                sum=0;
                while(i<=5) {
                    sum =sum + num[i];
                     i++;
                cout<<"sum is"<<sum;
                     }
            break;
    }

    return 0;
}
