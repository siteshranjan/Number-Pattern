# Number-Pattern
Number-Pattern Programe
12345
4321
123
21
1


int main()
{
    int i,j,k;
    for(i=5;i>=1;i--)
    {
        if(i%2==1) k=1;
        else k=i;
        for(j=1;j<=i;j++)
        {
            printf("%d",k);
            if(i%2==1) k++;
            else k--;
        }
        printf("\n");
    }
    return 0;
}

