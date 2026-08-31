# C Bubble Sort implementation

```c
#include <stdio.h>
#include <stdlib.h>

#define SIZE 10

void swap(int *x,int *y);
void buble_sort(int a[], const int n);
void display(int a[],int size);

void main()
{
    int a[SIZE] = {8,5,2,3,1,6,9,4,0,7};
    int i;

    printf("The array before sorting is:\n");
    display(a,SIZE);

    buble_sort(a,SIZE);

    printf("The array after sorting using bubble sorting algorithm:\n");
    display(a,SIZE);
}

void swap(int *x,int *y)
{
    int temp;
    temp = *x;
    *x = *y;
    *y = temp;
}

void buble_sort(int a[],const int size)
{
    int i,j;
    for(i=0; i<(size-1); i++)
    {
        for(j=0; j<(size-(i+1)); j++)
        {
            {
                if(a[j] > a[j+1])
                    swap(&a[j],&a[j+1]);
            }

        }
    }
}
void display(int a[],const int size)
{
    int i;
    for(i = 0; i < size; i++)
        printf("%d ",a[i]);

    printf("\n");
}
```





# References

* https://www.learnc.net/c-algorithms/c-bubble-sort/
