#include<stdio.h>
int main()
{

    int i,n=15,j;

    for(i=1;i<=15;i++)
    {
        int sum=0;
        while(1)
        {
            scanf("%d",&j);
           if(j==-1)
                break;
                sum=sum+j;

    }
    printf(" %d no. customeer ordered total %d ites\n",i,sum);
    }

}
