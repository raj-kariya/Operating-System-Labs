# Operating-System-Labs
# Page-Replacement-Algorithms-Simulation-Comparision
In this project different Page Replacement Algorithms of Operating System is simulated in table form and we find compare this 3 algorithm by finding the hit and fault rates which tells that OPT is best.  
# Algorithms :
1) First In First Out(FIFO) : This algorithm replaces the oldest page in memory—the page that has been in memory the longest—when a new page needs to be loaded.\
2) Optimal Page replacement(OPT) : This algorithm replaces the page that will not be used for the longest period of time in the future. Although it provides the best performance, it is impractical in real scenarios because it requires future knowledge of the reference string. \
3)  Least Recently Used (LRU): This algorithm replaces the page that has not been used for the longest period of time. LRU assumes that pages used recently will likely be used again soon, so it keeps these in memory. 
# Description(OS Lab 9): 
i. Enter the refference string without any spaces then press "SIMULATE" button. \
ii. First enter the no. of Frames availabe. \
# Explanation : 
In operating systems that use paging for memory management, a page replacement algorithm is crucial. This algorithm decides which page should be replaced in memory when a new page needs to be loaded.
1) Page Fault: A page fault occurs when a program tries to access a page that is not currently in memory. The operating system must then load the required page from disk into memory.

2) Page Hit: A page hit occurs when the page a program tries to access is already present in memory, allowing the program to proceed without delay.

3) Memory Management Unit (MMU): The MMU is a hardware component responsible for the runtime mapping of virtual addresses to physical addresses. It plays a critical role in memory management, enabling efficient access to memory.



# References
Simulation link :- https://nicomedes.assistedcoding.eu/#/app/os/page_replacement \
Algorithm Link : https://www.google.com/amp/s/www.geeksforgeeks.org/page-replacement-algorithms-in-operating-systems/amp/ 
