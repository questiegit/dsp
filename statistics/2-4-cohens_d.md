[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

>> print((firsts.totalwgt_lb.mean()-others.totalwgt_lb.mean())/np.sqrt((len(firsts.totalwgt_lb)*firsts.totalwgt_lb.var()+len(others.totalwgt_lb)*others.totalwgt_lb.var())/(len(firsts.totalwgt_lb)+len(others.totalwgt_lb))))
>> # The weights of firstborns vs other borns are within 0.1 lb std dev of each other
>> # The weights of firstborns are slightly less than the otherborns, which is why the Cohen's coefficient is negative
