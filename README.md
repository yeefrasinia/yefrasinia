# yefrasinia

using namespace std; 

using BinaryOperation = int (*)(int,int);
int sum(int a,int b)
{     return a+b; }
int accumulate(int arr[],int i,int last, int init) 
{      for(; i&lt;last; ++i)   
{         if(arr[i]%10==3)  
{             init = init+arr[i];      
}  
}     return init;  } 
int main() {   
int arr[10]= {123, 644, 124, 56, 133,12,334,556,1333,343};   
BinaryOperation op = sum;     auto a = mysum(12,34);     
cout &lt;&lt; a &lt;&lt; endl;  
return 0; }
