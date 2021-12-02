///implemente um sistema onde o usuário entre com 5 valores, depois mais 5 e junte os valores final.

#include <iostream>
using namespace std;

class junta{ 		/// nome da classe;																	
int vetor[6];	
int vet1[6];	
int vet2[12];																			
int i;	
public: 

/// metodo para acesso fora da classe

vet01(int vet[6]);               /// declaração do metodo
vet02(int vet[6]);
vet03(int vet[12]);  																	
};

///ação do metodo 
int junta::vet01(int vet[6]){	 /// declara os valores do primeiro vetor														
	for (i=0;i<6;i++){
    		cout << "Digite o numero do primeiro vetor " << i << endl;
    		cin >> vetor [i];
					}
					}
					
int junta::vet02(int vet[6]){	 /// declara os valores do segundo vetor														
	for (i=0;i<6;i++){
    		cout << "Digite o numero do segundo vetor " << i << endl; 
    		cin >> vet1 [i];
    }
	}
	
int junta::vet03(int vet[12]){
   
for (i=0;i<6;i++){				///	traz os valores do primeiro vetor
			vet2[i] = vetor[i];
}
for (i=6;i<12;i++){				/// traz os valores do segundo vetor e exclui o primeiro vetor
			vet2[i] = vet1[i-6];
}
for (i=0;i<12;i++){				/// imprime os valores do primeiro e do segundo vetor
		cout << vet2[i] << " ";
}
}
int main(){ 																			
	int vet[6];			
	junta vetts;		
	vetts.vet01(vet);		
	vetts.vet02(vet);
	vetts.vet03(vet);
		}
