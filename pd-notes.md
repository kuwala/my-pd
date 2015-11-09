
10/27/15
I think I have Discovered a bug with pd-extended 0.43.4
If you send a message list [ 13 0 (
to a [ select 13 ] it wont work but if you send it
to a [ select 13 5 ] it will work.

In this case suspect that more arguments in a select
allow it to select from a list but if there is only 
one the select expects a float

