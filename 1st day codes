# csa0318
# 1ST QUESTION 
# C Program to Insert an element
# at a specific position in an Array

#include <stdio.h>

int main()
{
	int arr[100] = { 0 };
	int i, x, pos, n = 10;

	// initial array of size 10
	for (i = 0; i < 10; i++)
		arr[i] = i + 1;

	// print the original array
	for (i = 0; i < n; i++)
		printf("%d ", arr[i]);
	printf("\n");

	// element to be inserted
	x = 50;

	// position at which element
	// is to be inserted
	pos = 5;

	// increase the size by 1
	n++;

	// shift elements forward
	for (i = n - 1; i >= pos; i--)
		arr[i] = arr[i - 1];

	// insert x at pos
	arr[pos - 1] = x;

	// print the updated array
	for (i = 0; i < n; i++)
		printf("%d ", arr[i]);
	printf("\n");

	return 0;
}
*************************************************************************************************************
# 2ND QUESTION
# SEARCHING AN ELEMENT IN ARRAY
#include <stdio.h>

int main() {
    int arr[] = {1, 2, 3, 4, 5};
    int n = sizeof(arr) / sizeof(arr[0]);
    int key = 3;  // The element you want to search for

    int found = 0;

    for (int i = 0; i < n; i++) {
        if (arr[i] == key) {
            found = 1;
            break;
        }
    }

    if (found) {
        printf("Element found in the array.\n");
    } else {
        printf("Element not found in the array.\n");
    }

    return 0;
}
****************************************************************************************************************
# 3RD QUESTION
# DELETING ELEMENT FROM ARRAY

#include <stdio.h>  
#include <conio.h>  
  
int main ()  
{  
      
    int arr[50];  
    int pos, i, num;
    printf (" \n Enter the number of elements in an array: \n ");  
    scanf (" %d", &num);  
      
    printf (" \n Enter %d elements in array: \n ", num);  
      
  
    for (i = 0; i < num; i++ )  
    {   printf (" arr[%d] = ", i);  
        scanf (" %d", &arr[i]);  
    }  
      
   
    printf( " Define the position of the array element where you want to delete: \n ");  
    scanf (" %d", &pos);  
      
    
    if (pos >= num+1)  
    {  
        printf (" \n Deletion is not possible in the array.");  
    }  
    else  
    {  
      
        {  
            arr[i] = arr[i+1]; // assign arr[i+1] to arr[i]  
        }  
          
        printf (" \n The resultant array is: \n");  
          
      
        for (i = 0; i< num - 1; i++)  
        {  
            printf (" arr[%d] = ", i);  
            printf (" %d \n", arr[i]);  
        }  
    }  
    return 0;  
}  
*******************************************************************************************************************
# 4TH QUESTION
# LINEAR SEARCH
#include<stdio.h>
int main()
{
   int arr[]={44,55,66,77,88);
   int size=sizeof(arr)/sizeof(arr[0]);
   int key=44;
   for(int i=0;i<size;i++)
   {
       if(key==arr[i]
       {
           printf("position of key %d\n",key,i);
      }
  }
}
**********************************************************************************************************************
# 5TH QUEESTION
# BINARY SEARCH
#incldue<stdio.h>
int main()
{
   int arr[]={1,2,3,4,5,6,78,90};
   int size=sizeof(arr)/sizeof(arr[0]);
   int key=3;
   int low,high=size;
   mid=(low+high)/2;
   if(key==arr[mid]
   {
     break;
    }
    if(key<arr[mid])
    {
      high=mid-1;
    }
    else
    {
       low=mid+1;
    }
  }
  printf("position of key %d is %d\n",key,mid);
}
*****************************************************************************************************************************
