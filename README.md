# continue-and-break...together

#include <iostream>
#include <iomanip>

using namespace std;
int main()

{
	int n= 1;
	char c;
	
	for ( ; ; n++)
	
		{
			cout<<"loop : "<<n<<endl;
			cout<<"continue ? <y | n> ";
			
			cin>>c;
			
			if ( c=='y') continue;
			
			break;
		}

	cout<<"Total Of loops: "<<n<<endl;
}

