# bootcore
its short notes Of core-java



Language Fundamental
---------------------

Literal
--------
 
int x =10;

Integral Literals
-----------------
 1.decimal literals is allowed digits  0 to 9
 
ex: int x=10;
 2. Octal literals are 0 to 7
      its value should be prefixed with '0'


 3. Hexadecimal Literals alowed digits are 0 to 9 , a to f and A to F
     int x =0x10;
     int x1=0X10;


For Example
------------

class Test
{
    public static void main(String []args)
    {
        int x=10;//Decimal Literal
        int y=010; //Octal Literal
        int z=0X10; //hexadecimal Literal
     
       System.out.println(x+"-----"+y+"........"+z);

    }
}
  


Floating Literals
------------------

1. we can assigned floating point Literal by using suffix with 'f' or 'F'
     ex : float f1=123.456f,12334.5F;
2. flaoting points Literal even in scientific form also
     float f1=1.2e3f;

we can spacify floating Literals inonly deciaml form
 Its can not be Hexadecimal or Octal form
 and calso can not assign hexadecimal Literal to the integral types





Boolean Literals
----------------
 the only possible values in boolean datatypes are true/false

boolean flag =true; boolean flg=false;


Char Literals
--------------

char ch = 'a';// write
char ch1='ab';// wrong

charLiteral can be represented In unicode Literal 
char ch =oXbeaf;




            


