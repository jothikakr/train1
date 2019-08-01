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
More



package varanum;package varanum;


public class Varanum {
import java.util.Scanner;
   
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
       
       String days[]={"Monday","Monday","Monday","Monday","Monday","Tuesday","Tuesday","Tuesday","Tuesday","Tuesday","Wednesday","Wednesday","Wednesday","Wednesday","Wednesday"};
       double times[]={06.04,09.04,12.04,15.04,19.04,06.04,09.04,12.04,15.04,19.04,06.04,09.04,12.04,15.04,19.04};
       int passenger[]={22,119,64,177,21,22,111,87,193,22,11,107,93,162,42};
       
       /*displayiing the data*/
       System.out.println("Days\t\tDeparture times\t\tNumber of passenger");
       for(int i=0;i<5;i++)
       System.out.println(days[i]+"\t\t"+times[i]+"\t\t\t"+passenger[i]);
       
       System.out.println("\nDays\t\tDeparture times\t\tNumber of passenger");
       for(int i=5;i<10;i++)
       System.out.println(days[i]+"\t\t"+times[i]+"\t\t\t"+passenger[i]);
       
       System.out.println("\nDays\t\tDeparture times\t\tNumber of passenger");
       for(int i=10;i<15;i++)
       System.out.println(days[i]+"\t\t"+times[i]+"\t\t\t"+passenger[i]);
       
       /*finding the most popular train*/
       int max = passenger[0];
       int in = 0;
       for(int i=0;i<15;i++){
        if(passenger[i]>max){
            max=passenger[i];
            in=i;
            }
       }
       System.out.println("\nThe day and time of most popular train: "+days[in]+"\t\t"+times[in]);
       
       /*finding the least popular train*/
       int min = passenger[0];
       int inp = 0;
       for(int i=0;i<15;i++){
        if(passenger[i]<min){
            min=passenger[i];
            inp=i;
            }
       }
       System.out.println("\nThe day and time of least popular train: "+days[inp]+"\t"+times[inp]);
       
       /*finding whether the 6.04 train is more popular than 9.04 train*/
       int avgtr1=(passenger[0]+passenger[5]+passenger[10])/3;
       int avgtr2=(passenger[1]+p
