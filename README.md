# circulo_2
class
using namespace std;

class punto{
	public:
		
		float h,k;
		

	};



class circulo{
	
	public:
		punto x , y ;
		float radio ;
		float area (){
			float pi=3.14, S;
			S=pi*(radio*radio) ;
			return S;
		}
		
};
int main() 
{
	circulo A;
	cout<<"\t\t CIRCULO "<<endl;
	cout<<"Ingrese h: "<<endl;
	cin>>A.x.h;
	cout<<"Ingrese k: "<<endl;
	cin>>A.y.k;
	cout << "Centro  (" <<A.x.h << "," <<A.y.k << ")" << endl;
	cout<<"\nIngrese el radio: "<<endl;
	cin>>A.radio;
	cout << endl << "Area del circulo = " << A.area() << endl;
	

	
return 0;
}
