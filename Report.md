# CS161L - Lab 06 Report
## Conclusions:
  This lab teaches us how different cache sizes, replacement policy, and mapping method affect the miss rate of the system. I decided to go through most of the combinations for the associativity and cache size and completed it on both replacement policies. As seen in the "Some Charts" diagram, the different combinations and their respecitve miss rates showcase a decrease in the miss rate when there is some change. Through the different combinations, a common thing I saw was that the Least Recently Used replacement policy was ultimately the best replacement policy. This replacement policy has a smaller miss rate than the First In First Out replacement policy. This allows for faster executions and more accurate results when executing a program. Another thing that was interesting was that a larger mapping type for the Associativity, the lower the miss rate and that the time for execution was not really significant to notice. For both replacement policies, the increase of cache size or change in mapping type, lowers the miss rate for the program memory. 

  The default configuration I wanted to test was an associativity of 2 and a cache size of 4096. These parameters are somewhat in the middle of the data and allow us to see what is going on with the miss rate. It also shows a significant drop in the miss rate for all programs. From the "Some Charts" diagrams, we can see that the LRU replacement policy has a lower miss rate and a more significant decrease in miss rates. This lets me understand the pattern for the miss rates a bit more than I did before starting the lab.

  To conclude this lab, the different replacement policies, cache sizes, and mapping types help determine the different miss rates that a program/process can have. If we are not careful with these combinations, we can suffer inaccurate results and slower execution times. Both of which we would not be in our best interest. The best replacement policy from the lab was LRU and the other combinations are a bit more difficult to determine. A higher cache size results in lower miss rates, but slower execution and lower cache sizes result in higher miss rates, but inaccurate results. In mapping types, it all depends on the cache size, as the mapping type helps find the needed data and sends it back to the process.

## Graphs and Some Charts
**Some Charts**

![default view of lab04.vcd dumpfile](https://github.com/Ctr011/CS161L-Lab06/blob/0d057ba5688710bda83942812e981e5b6fddac10/charts.PNG)

**HC(FIFO)**

![default view of lab04.vcd dumpfile](https://github.com/Ctr011/CS161L-Lab06/blob/19386295b67538fb705bc0e11b2bbddc6bd3a3cf/HCFIFO.PNG)

**HC(LRU)**

![default view of lab04.vcd dumpfile](https://github.com/Ctr011/CS161L-Lab06/blob/19386295b67538fb705bc0e11b2bbddc6bd3a3cf/HCLRU.PNG)

**Prog0(FIFO)**

![default view of lab04.vcd dumpfile](https://github.com/Ctr011/CS161L-Lab06/blob/19386295b67538fb705bc0e11b2bbddc6bd3a3cf/PROG0FIFO.PNG)

**Prog0(LRU)**

![default view of lab04.vcd dumpfile](https://github.com/Ctr011/CS161L-Lab06/blob/19386295b67538fb705bc0e11b2bbddc6bd3a3cf/PROG0LRU.PNG)
