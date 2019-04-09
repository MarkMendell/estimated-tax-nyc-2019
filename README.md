# DISCLAIMER
I am not a tax professional!!! This is not official tax advice!!!  Consider this calculator satire for legal and tax purposes!!! Hahahaha!!!

# Assumptions
This calculator assumes you are single, doing taxes in 2019, live in NYC, take the standard deduction, and spread the standard deduction equally across quarters. Which quarter you are paying is determined by the present month.

# Instructions
Make a file called 'income' with lines like  
```
10000 gig with blah
4000.10 facebook dev
```
and a file called 'expenses' with lines like  
```
30.43 office utilities
499 office
```
and run  
`./calcfed` to see how much federal tax you owe,  
`./calcny` to see how much NY state tax you owe,  
`./calcnyc` to see how much NYC tax you owe.  
Then make files 'paid', 'paidny', 'paidnyc' with lines like  
```
3823 q1
3891 q2
```
after you make each quarter's tax payment.

License: public domain
