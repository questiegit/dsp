[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

>> pmf = thinkstats2.Pmf(resp.numkdhh, label='actual')
>> thinkplot.Pmf(pmf)
>> thinkplot.Config(xlabel='Children under 18', ylabel='Pmf')
>> biased_pmf = BiasPmf(pmf, label='observed')
>> thinkplot.PrePlot(2)
>> thinkplot.Pmfs([pmf, biased_pmf])
>> thinkplot.Config(xlabel='Children under 18', ylabel='PMF')
>> print('Actual mean', pmf.Mean())  #Actual mean 1.024205155043831
>> print('Observed mean', biased_pmf.Mean()) #Observed mean 2.403679100664282
