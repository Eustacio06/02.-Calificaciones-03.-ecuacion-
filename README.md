# 02.-Calificaciones-03.-ecuacion

#include <conio.h>
#include <stdio.h>

int main ()

{
int x,y,z,j,calf;

printf("Dime tu primer calificacion ");
scanf("%d",&x);

printf("Dime tu segunda calificacion ");
scanf("%d",&y);

printf("Dime tu tercer calificacion ");
scanf("%d",&z);

printf("Dime tu cuarta calificacion ");
scanf("%d",&j);

calf=(x+y+z+j)/4; 

printf("tu calificacion final es %d",calf);
getch();
return 0;
}
