# BUGS

The answers file for mariadb-secure-installation needs to be updated if the
questions asked by the script change.  How this will play out is that the OS
will get updated, then later this role will get reinstalled, and things will go
horribly wrong because the questions were unexpectedly different.  Worse,
things might go subtly wrong, like undermining security while keeping
stability.  Find a different way to automate this script, or find out how to
skip it.
