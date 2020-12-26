### spfinal solution

***
* Name: Adilet Saparbay
* Email: 180107194@stu.sdu.edu.kz
* Variant: [20](../variants/variant20.md)
* Solution: [./top](./top)
***


### Explanation

1)'cut' works like split, will divide problems

2)There is 'sed' to remove

3)'Grep' to exclude lines that are

4)We will sort

5)We have two columns 'reference' and the name of the application and we will be the brother of the application from it

6)The applications have versions of the numbers i will erase them with 'sed'

7)And we will again sort 

8)Then with "uniq -c" will group

For example:

* mozilla mozilla chrome if it's worth it

* will change: mozilla 2 chrome 1

9)Next will sorT by numbers and by names


10)And  have a number that was originally given


11)When write /top.sh 5 the first take 5 this nubmer


12)Then awk the first begin well count total

For example:

* mozilla 2

* chrome1 

will be,general be 3 and this 3 will be count in the second  will be used to divide by this number and calculate the percentage


13)printf used to output data by formatting


14)Next chorme 1, mozilla2 will output

* mozilla 2 66%

* chorome 1 33%

Found percentage of division by total








