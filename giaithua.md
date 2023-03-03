#include<stdio.h>
#include<conio.h>
#include<math.h>
using namespace std ;

/*long  Tich ( int a ,S )
{
    if( a < 0)
        return 0;
    else 
     for (int i=1 ; i< a ; i++ )
     S = S *i ;
};*/ 

int main ()
{
    int a;
    int s=1 ;

    printf("nhap vao a ");
    scanf("%d", &a) ;

    if( a < 0)
        return 0;
    else {
     for (int i=1 ; i< a ; i++ )
     s = s *i ;
    }

    
    printf("tong la :%d", s );
    getch();
    return 0;

}
