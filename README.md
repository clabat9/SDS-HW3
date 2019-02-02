# SDS-HW3

# Bayesian Networks


![alt text](https://www.the-tls.co.uk/s3/tls-prod/uploads/2018/06/Thomas-Bayes.jpg)

This work is an introduction to [Bayesian Networks](https://en.wikipedia.org/wiki/Bayesian_network).

For some strange turn in the history of science, (many) astrophysicists are real Bayesian “evangelists” that use, misuse and
push the old Reverend into their data analytic games as soon as they possibly can. This little_tiny_exercise inspired by a not
so old paper, is just one example of what can be done.
We all know what a star is, and we all know that they form and evolve in decently well-understood way. The Hertzsprung–
Russell diagram where we graph each star in terms of its brightness against its temperature (color), was one of the tools that
led astronomers to speculate about stellar evolution: stars, while fusing hydrogen in their cores, collapse from red giants to
dwarf, and then, in the course of their lifetimes, move down along the so called main sequence, a prominent diagonal band
that runs from the upper left to the lower right of the H-R diagram.

Now, the problem we are tackling here is an old one, strictly related to these issues: determining the stellar initial mass function
(IMF). The IMF plays an extremely crucial role in shaping stellar population: it determines the probability distribution of the
mass at which a star enters the main sequence; it regulates the relative abundance of massive versus low-mass stars for each
stellar generation; it influences most observable properties of stellar population and galaxies, and it is also required as input in
some models of galaxy evolution.

For an astrophysicist the ultimate goal would clearly be to infer the IMF from first principles, but here we content ourselves
with an empirical, data driven alternative: fit the IMF using a lognormal distribution as suggested by Zaninetti but in a
Bayesian framework using OpenBUGS/JAGS.

## Script and Other files descriptions

1. __`HW3.rmd`__: 
	This R  markdown contains all the useful chunks to get the proposed requests, deeply commented to have a clear view of the logic behind.

2. __`HW3.html`__: 
	This html files contains the presentation of the markdown.
  
3. __`model.odc`__: The BUGS model.

4. __`Deep-Sky_Bayes.odc`__: The BUGS data and inits.
