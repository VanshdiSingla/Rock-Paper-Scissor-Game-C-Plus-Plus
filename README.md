# Rock-Paper-Scissor-Game-C-Plus-Plus
This Repository contains the most famous game  . 
<br>
#include<iostream>
using namespace std;

int main()
{
    cout<<"For Rock Press r"<<endl;
    cout<<"For Paper Press p"<<endl;
    cout<<"For Scissor Press s"<<endl;

    char r1;                //first person turn
    cout<<"Enter response of first person ";
    cin>>r1;

    char r2;
    cout<<"Enter response of second person ";
    cin>>r2;

    if((r1=='r'&&r2=='p')||(r1=='p'&&r2=='r'))
    {
        cout<<"Paper Wins ";
    }
    else if((r1=='r'&&r2=='s')||(r1=='s'&&r2=='r'))
    {
        cout<<"Rock Wins ";
    }
    else if((r1=='p'&&r2=='s')||(r1=='s'&&r2=='p'))
    {
        cout<<"Scissor Wins";
    }
    else
    {
        cout<<"Invalid Inputs";
    }
    return 0;
}
