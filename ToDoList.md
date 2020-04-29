29/4/2020 

The original code keeps adding to the database and therefore has duplicate entries.

We should remove entries when fail2ban unbans the IP by adding a -remove command line option and possible also compliment it with an -add
