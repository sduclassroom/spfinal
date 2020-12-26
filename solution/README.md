### spfinal solution

***
* Name: Adilet Saparbay
* Email: 180107194@stu.sdu.edu.kz
* Variant: [20](../variants/variant20.md)
* Solution: [./top](./top)
***


'cut' works like split, will divide problems
then there is 'sed' to remove
then 'grep' to exclude lines that are
then we will sort
then we have two columns 'reference' and the name of the application and we will be the brother of the application from it
Then the applications have versions of the numbers i will erase them with 'sed'
And we will again sort 
then with "uniq -c" will group
for example:
mozilla 
mozilla
chrome
if it's worth it
will change:
mozilla 2
chrome 1
next will sory by numbers and by names
and  have a number that was originally given
when write /top.sh 5 the first take 5 this nubmer
then awk the first begin well count total
for example:
mozilla 2
chrome1 will be,general be 3 and this 3 will be count
in the second  will be used to divide by this number and calculate the percentage
printf used to output data by formatting
next chorme 1, mozilla2
will output
mozilla 2 66%
chorome 1 33
found percentage of division by total







