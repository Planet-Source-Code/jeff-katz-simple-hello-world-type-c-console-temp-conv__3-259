<div align="center">

## Simple Hello\-World Type C\+\+ Console Temp\. Conv\.


</div>

### Description

Converts Either Fahrenheit to Calcius or Calcius to Fahrenheit, Good For Beginners. | If You Like It, Vote Highly For It!
 
### More Info
 
Must be a console application


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Jeff Katz](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/jeff-katz.md)
**Level**          |Beginner
**User Rating**    |4.0 (20 globes from 5 users)
**Compatibility**  |C\+\+ \(general\)
**Category**       |[Complete Applications](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/complete-applications__3-7.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/jeff-katz-simple-hello-world-type-c-console-temp-conv__3-259/archive/master.zip)

### API Declarations

iostream.h, conio.h


### Source Code

```
#include <iostream.h>
#include <conio.h>
double ctof(double x);
double ftoc(double x);
void ftocf();
void ender();
void ctoff();
int op;
void main ()
{
op=0;
cout<<"Select an Option:"<<endl;
cout<<" 1 for F to C"<<endl;
cout<<" 2 for C to F"<<endl;
cout<<" 3 To End"<<endl;
cin>>op;
if(op==1) ftocf();
if(op==2) ctoff();
if(op==3) ender();
}
void ctoff()
{
int x;
cout<<"Enter Degrees Celcius to Make Into Fahrenheit:"<<endl;
cin>>x;
cout<<"Result: "<<ctof(x)<<endl<<endl;
main();
}
void ftocf()
{
int y;
cout<<"Enter Degrees Fahrenheit to Make Into Celcius:"<<endl;
cin>>y;
cout<<"Result: "<<ftoc(y)<<endl<<endl;
main();
}
double ctof(double x)
{
	return ((x*1.8)+32);
}
double ftoc(double y)
{
	return ((y-32)/1.8);
}
void ender()
{
	cout<<"Press Any Key to Exit"<<endl;
	getch();
}
```

