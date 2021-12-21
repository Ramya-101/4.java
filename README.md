# 4.java
class program4
{
public static void multiple ()
{
for(int j=1;j<10;j++)
{
count=0;
for(i=0;i<size;i++)
{
if(a[i]%j==0)
{
count++;
}
}
System.out.println(j+":"+count);
}
}
public static void main (String []args)
{
Scanner scn=new Scanner (System.in);
int size=scn.nextInt;
int[]a=new int[size];
System.out.println("enter value");
for(int i=0;i<size;i++)
{
a[i]=scn.nextInt();
}
for(i=0;i<size;i++)
{
System.out.in(a[i]+",");
}
multiple ();
}
