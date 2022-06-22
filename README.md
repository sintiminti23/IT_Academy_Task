Task 1 / Regular Expressions:

*current time in format hh:mm:ss

~$ date | grep -oE "([0-9]+:[0-9]+:[0-9]+)"

*ipv4 address

~$ ifconfig | grep -oE '[0-9]+\.[0-9]+\.[0-9]+\.[0-9]+'

*whole paragraph of test text

~$ ifconfig | grep '(?<=^|\n).+?$'






