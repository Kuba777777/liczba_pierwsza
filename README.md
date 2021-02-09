# liczba_pierwsza
to jest to z liczba pierwsza tylko wrzucam kod z rozpoznawaniem liczby parzystej 




#include <stdio.h>
#include <stdlib.h>

int main()
{
	int liczba;
	printf("podaj liczbe calkowita: ");
	scanf("%i",&liczba);
	if (liczba%2) printf("\n Podano liczbe nie parzysta."); 
	else printf("\n Podano liczbe parzysta.");
	
	
	return 0;
}



Nowa wersja!!!!!!!!!!!!!!!!!!!!

Zrobiłem na podstawie tego co mi wysłąłeś.



#include <stdio.h>
#include <stdlib.h>
#include <math.h>



int main(){
	int TestPierwsza(int liczba);
	int liczba;
	int r = sqrt(liczba);
	int i = 2;
	printf("Podaj liczbe: ");
  	scanf( "%i", &liczba);

	if (liczba==1) printf("\n 1 nie jest liczba ani zlozona ani pierwsza");
	else  do
	if (TestPierwsza(liczba)) printf(" to liczba pierwsza");
  		else printf(" to liczba zlozona");



return 0;


}
