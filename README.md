int Fib(int n)
{ int a=1,b=1,temp;
if(n==1||n==2)
{
return 1;
}
else
{
for(int i=3;i<n;++i)
{
temp=a+b;
a=b;
b=temp;
}
return temp;
}
