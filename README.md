# pwnd-time-to-hack

Two of the biggest security problems is password reuse and weak passwords. It's not difficult to understand why these happen. The average user has no idea it's a problem. Yes, security people understand it but not regular people. So I was thinking about what could be done to help that situation.

1. Before the password is registered to the user check that password against a wordlist and a password strength checker
2. Alert the user that their chosen password is on a list of pwn'd passwords (even if we don't use that terminology)
3. Alert the user to how long it would take to brute for their chosen password
4. Ask the user if they are sure they still want to use that particular password.

This would not only serve to increase the strength of passwords but also give the user a nugget of education in a quick, easily digestable way.


