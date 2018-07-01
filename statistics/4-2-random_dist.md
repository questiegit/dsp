[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

>> t = np.random.random(1000)

>> # Plotting PMF
>> random_pmf = thinkstats2.Pmf(t, label='random_pmf')
>> thinkplot.PrePlot(1)
>> thinkplot.Pmf(random_pmf)
>> thinkplot.Config(xlabel='random', ylabel='PMF')
