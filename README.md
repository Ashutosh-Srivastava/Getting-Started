# Getting-Started
import java.util.*;
class combining_two_arrays
{
public static void main()
{
int i,j,m,n;
Scanner sn =new Scanner (System.in);
System.out.println("enter limits of array A");
m=sn.nextInt();
System.out.println("enter limits of array B");
n=sn.nextInt();
int a[]=new int[m];
int b[]=new int[n];
int c[]=new int[m+n];
for (i=0;i<m;i++)
{
System.out.println("enter array A");
a[i]=sn.nextInt();
}
for (j=0;j<n;j++)
{
System.out.println("enter array B");
b[j]=sn.nextInt();
}
for (i=0;i<m;i++)
{
c[i]=a[i];
}
for (j=0;j<n;j++)
{
c[i]=b[j];
i++;
}
System.out.println(i);
for (i=0;i<(m+n);i++)
{
System.out.println(c[i]);
}
}
}

