<!-- Notes Day 2 -->
<p>
<b>Feasibility of Learning</b> <br />
Learning pro­duces a hypothesis g to approximate the unknown target function f. If learning is successful, then g should approximate f well, which means Eout(g) ~ 0. However, this is not what we get from the probabilistic analysis. What we get instead is Eout(g) ~ Ein(g). We still have to make Ein(g) ~ 0 in order to conclude that Eout(g)~ 0.
<br />
We cannot guarantee that we will find a hypothesis that achieves Ein(g) ~ 0 but at least we will know if we find it. Remember that Eout (g) is an unknown quantity, since f is unknown, but Ein(g) is a quantity that we can evaluate. We have thus traded the condition Eout (g) ~ 0, one that we cannot ascertain, for the condition Ein(g) ~ 0, which we can ascertain. 
<br />
The feasibility of learning is thus split into two questions:<br/>
1. Can we make sure that Eout(g) is close enough to Ein(g)? <br/>
2. Can we make Ein(g) small enough?
</p>

#### Training versus Testing

The out-of-sample error Eout measures how well our training on D has gener­alized to data that we have not seen before. Eout is based on the performance over the entire input space X. Intuitively, if we want to estimate the value of Eout using a sample of data points, these points must be 'fresh' test points that have not been used for training. \
The in sample error Ein, by contrast, is based on data points that have been used for training. It expressly measures training performance, similar to your performance on the practice problems that you got before the final exam. Such performance has the benefit of looking at the solutions and adjusting accordingly, and may not reflect the ultimate performance in a real test. \
<!-- End Notes Day 2 -->
