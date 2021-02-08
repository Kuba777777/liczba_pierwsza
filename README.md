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



