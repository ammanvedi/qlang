qlang
=====

qq bro

works with following


```c
dict a = [| 1:"one", 2:"two", "three":3 |] ;
int b = 10;
string c = "hello world!";
person d = "Shin", "Yoo", 30;
char e = ’a’;
list f = [ ’a’, ’b’, ’c’, ’d’ ];

def list reverse (list l) 
{
	list l2 = [];
	int i = 0;
	
	while (i < len(l)) do 
	{
		l2 = l[i] :: l2;
		i = i+1;
	}
		return l2;
}

void main{

	foreach ( ab : x)
	{ 
		print x;
	}
	
	print "hello", 0, 0.1, abc, 'a';
	read x;
	
}
```