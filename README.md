package trainservice;
import java.util.Scanner;
public class Trainservice;
public static void main(String[] args){
Scanner sc=new Scanner(System.in);
int x=0;
String [] day={"Monday "," Tuesday "," Wednesday "};
double [] time={06.04,09.04,12.04,15.04,19.04};
int [] [] pr={22,119,64,177,21,22,111,87,193,22,11,107,93,162,42};
int input=sc.nextInt();
switch(input)
{
case1: System.out.print(" Day      Departure time     Number of passengers ");
for(int i=0;i<3;i++)
{
for (int j=0;j<5;j++)
{
for(int k=0:k<5;k++)
{System. out.print(" "+day[i]+" "+time[j]+" "+pr[j][k]);
}
}
}
max=pr[0][0];
min=pr[0][0];
String d1,d3;
double d2,d4;
for (int i=0;i<3;i++)
{
for(int j=0;j<5;j++)
{
if(max<pr[i][j])
{
max=pr[i][j];
d1=day[i];
d2=time [j];
}
if(min>p[i][j])
{
min=p[i][j];
d3=day[i];
d4=time[j];
}
}
}
System. out.print(" The most popular train runs on"+d1+"at"+d2+"with"+max+"passengers ");
int A1=pr[0][0]+pr[1][0]+pr[2][0];
int A2=pr[0][1]+pr[1][1]+pr[2][1];
if(A1>A2)
System.out.print (" The 06.04 train is more popular than the 09.04 train");
else if(A1<A2)
System.out.print("The 09.04 train is more popular than the 06.04 train");
else
System.out.print ("The 06.04train is equal to the 09.04 train");
if(pr[0][0]>pr[1][0])
System.out.print("The 06.04 train on Monday is more popular than the 06.04 train on Tuesday ");
else if(pr[0][0]<pr[1][0])
System.out.print(" The 06.04 train on Tuesday is more popular than the 06.04 train on Monday ");
else
System.out.print(" The 06.04 train on Monday and Tuesday are equally popular");
for(int i=0;i<3;i++)
{
for(int j=0;j<5;j++)
{System.out.print("The" +time[j]+"train on day[i]+"have below 50 passengers ");
}
}
}
int x1=pr[0][2]+pr[1][2]+pr[2][2];
J=x1/3;
System.out print(" The average number of passengers travelling on 12.04 train over the three days is"+J);
break;
case2:
System.exit (0);
break;
default: System.out.print("Invalid");
}
}
}





