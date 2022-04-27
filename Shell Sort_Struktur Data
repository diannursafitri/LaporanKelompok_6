#include <iostream>
#include <conio.h>
using namespace std ;

int main (){
	//deklarasi array
		int array;
	
	// input panjang array
	cout << "masukan panjang array:";cin>> array;
	int arr_sorting [array], a,k,j,i,t ;
	
	cout << endl;
	
	//input data array
	cout << "masukan data" <<array<< " Data yang akan diurutkan ;" << endl ;
	for (i=0 ; i<array;i++)
	{
		cout<< "data ke-" << i+1<<" :";
		cin >> arr_sorting [i];
	}
	cout << endl ;
	
	//data yang akan diurutkan 
	cout << "data :"<<endl;
	
	cout << endl;
	
	for (i =0 ;i<array ;i++){
		cout << "\t"<<"[" <<arr_sorting[i]<< "]";
	}
	cout << endl;
	
	//proses pengurutan data
	for (i= array / 2;i> 0; i=i /2){
		for (j=i;j <array ; j++){
			for (k=j-i; k>=0; k=k-i){
				if (arr_sorting[k+i]>=arr_sorting[k])
				break ;
				else {
					
					t = arr_sorting[k];
					arr_sorting[k]=arr_sorting [k+i];
					arr_sorting [k+i]= t;
				}
			}
			
			cout << endl;
			
			cout << "pengulangan shell sort" << i << " :" ;
			for (a = 0 ; a <array ; a++) {
				cout << "\t" << "[" << arr_sorting[a]<< "]";
			}
 		}
	}
	cout << "\n" << endl;
	
	//hasil pengurutan
	cout << " data yang telah diurutkan dengan algoritma shell sort:" <<endl;
	
	cout << endl ;
	
	for (i=0 ; i <array; i++){
		cout << "\t" << "[" << arr_sorting [i]<< "]";

	}
	
	getch();
}
