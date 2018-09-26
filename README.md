# tarea3
#include <stdio.h>

void ordenaArreglo(int *array, int size);

int main()
{

 ordenaArreglo( {5,2,4,7,9,1} ,6 )  
}

void ordenaArreglo(int *array, int size)
{
 int i, j, temp;
 
 for(j=0; j<size-1; ++j)
 for(i=j+1; i<size; ++i)
 
 if(*(array+i)< *(array+j))
 {
    temp=*(array+j);
    *(array+j)= *(array+i);
    *(array+i)= temp;
 }
 
}
