### Based on Learning from Data

#### Types of Learning 
##### Supervised Learning 
<p>
	When the training data contains explicit examples of what the correct output should be for given inputs, then we are within the supervised learning set­ ting that we have covered so far. Consider the hand-written digit recognition problem (task (b) of Exercise 1 . 1) . A reasonable data set for this problem is a collection of images of hand-written digits, and for each image, what the digit actually is. We thus have a set of examples of the form ( image , digit ). <br />
	<b>Active Learning</b> <br />
	- where the data set is acquired through queries that we make. Thus, we get to choose a point x in the input space, and the supervisor reports to us the target value for x. As you can see, this opens the possibility for strategic choice of the point x to maximize its information value, similar to asking a strategic question in a game of 20 questions. <br />
	<b>Online Learning</b> <br />
	- where the data set is given to the algorithm one example at a time. This happens when we have stream­ ing data that the algorithm has to process 'on the run'. For instance, when the movie recommendation system discussed in Section 1.1 is deployed, on­ line learning can process new ratings from current users and movies. Online learning is also useful when we have limitations on computing and storage that preclude us from processing the whole data as a batch. <br />
</p>
<p>
	When the training data does not explicitly contain the correct output for each input, we are no longer in a supervised learning setting.
</p>
##### Reinforcement Learning
<p> 
	The training example does not contain the target output, but instead contains some possible output together with a measure of how good that out­ put is. In contrast to supervised learning where the training examples were of the form ( input , correct output ) , the examples in reinforcement learning are of the form <br /> ( input , some output , grade for this output ).	
	<br />
	<b> Importantly, </b> the example does not say how good other outputs would have been for this particular input. <br />
	The reinforcement learning algorithm is left with the task of sorting out the information coming from different ex­amples to find the best line of play.
</p>
##### Unsupervised Learning 
<p>
	In the unsupervised setting, the training data does not contain any output information at all. We are just given input examples x1, · · · , xN. 
	Unsupervised learning can be viewed as the task of spontaneously finding patterns and structure in input data. For instance, if our task is to categorize a set of books into topics, and we only use general properties of the various books, we can identify books that have similar prop­erties and put them together in one category, without naming that category. <br />
	Indeed, unsupervised learning can be a precursor to supervised learning. In other cases, it is a stand-alone technique.
</p>
