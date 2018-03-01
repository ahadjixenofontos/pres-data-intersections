<font size="28" color="#008080"> Mirror, mirror, on the wall, <br>is my study valid at all?  </font>

<br>
Athena Hadjixenofontos, PhD
<br>
<font size="6">Director of Engagement</font>
<font size="6">Center for Computational Science</font>
<font size="6">ahadjixenofontos@miami.edu</font>
<br>

Note:
Hello, my name is Athena Hadjixenofontos, I'm very happy to be here, representing what we now call data science, thank you for taking time out of your day to listen to us talk.

---

@title[Gentoo penguins]

<img src="images/chick_chase.png">

Note:
Prepare video here, starting at minute 1:50. Keep sound off.
http://channel.nationalgeographic.com/wild/videos/chick-chase/

We're about to watch a video of gentoo penguins. A little bit of context, this penguin right here is the parent, and these two are the chicks. 

As we're watching, please think of a phrase or a sentence to describe what they're doing, and if you want write it on your notepad

Okay, so who described what these penguins are doing as a fed up parent running away from the constant demands of the chicks?
Who described this as learning through play? Perhaps the parent is teaching the chicks how to get away from a predator?

I would suggest, that these interpretations of penguin behavior may be colored by your experience of the world. 
If you’re a mom and had a rough morning with the kid you may attach the first interpretation to this behavior. 
If you are a student you may see it differently.
If you are an evolutionary biologist you may see it as the mom making sure that only the fittest offspring get fed. 
All you actually see is penguins running.

---

@title[Anais Nin]

<img src="images/spotlight.png" height="300">

*We don't see things as they are, <br> 
we see them as we are.* 
<br> <br> <font color="#008080"> - Anais Nin </font>

Note:
Anthropomorphism is one example of seeing things not as they are, but as we are. 

In the context of data science, extending inference beyond where it's due, adding meaning that may or may not be warranted, is something that comes up not only when interpreting the observations, but as we'll see, in many other places as well. 

+++

@title[Empiricists]

*... it is impossible for us to **think** <br> of any thing, which we have not antecedently **felt**, either by our external or intenal senses.* 
<br> <br> <font color="#008080"> - David Hume </font>

Note:
It would be an omission to go on without at least acknowledging that "what can I know" is a question asked by many great thinkers. This model of how knowledge is generated, of observations leading to interpretations which generate to knowledge about how the world works, has a long history with many contributors. 

Epistemology is the field of philosophy that asks some of these most difficult and fascinating questions. There are a few main schools of thought: the empiricists  insist that the ultimate source of all knowledge is observation. Hume was one of them, claiming that the knowledge cannot be gained based on something innate, but that is forms a posteriori, based on your set of experiences. It is impossible for us to think of anything, which we have not antecedently felt, either by our external or internal senses. 

+++

@title[Rationalists]

*Vulcanians don't speculate, <br>I speak from pure logic. <br>If I let go of a hammer on a planet that has <br> positive gravity, I need not see it fall <br>to know that it has in fact fallen.* <br>
<br> <font color="#008080"> - Mr. Spock </font>

Note:
The rationalists, on the other camp, if you subscribe to such camp divisions, insist that some knowledge is accessible by intuition alone, and other knowledge can be deduced from intuition, using the rules of logic. 

Spock here expresses an idea that originated with Plato and Pythagoras, that there is an objective reality that can be accessed through logic. 
The position that you choose to take has implications for your decisions in all stages of data analysis. I am not so much concerned with the truth of who is right, but more concerned with which of these positions serves us best when we work with data. That's the first take away. 

+++

@title[Water cycle]

<img src="images/water-cycle.jpg" height="340">

Note:
I personally don't view intellectual intuition as something innate, but rather as something that is developed through observation. Scientists, being human beings, cannot escape the biases introduced by the very specific way in which humans perceive the world, process information and reach conclusions. 

As we saw with the penguins, having a sharpened intuition by repeated contact with a topic, like the evolutionary biologist, may help us get closer to the truth, if such a thing exists. As soon as you switch environments, or perhaps type of data, the intuition needs to be built up again.  

There are lots of layers to the philosophical debate, which I'm not qualified to take apart, so we'll leave this discussion here. 

The second take away is that the foundations of data science, as a science, have a long and rich history in multiple fields, which is often overlooked because the term "data science" itself is so new. 

+++

@title[Take aways]

###  <font color="#008080">Take away </font>

<br>
- What are the implications of our philosophical positions for how we carry out data science? 
<br> <br>
- The term data science is new, but that may reflect popularity more than it reflects history.  

Note:
When I say that who you are shows up in the data analysis decisions that you make, I am referring to your collection of experiences, observations, as well as your interpretations of those observations and any meaning you may have attached to them. 

---

@title[The dangers of popularity]

<img src="images/sexiest_job.png">

Note:
The context in which data science operates has changed now that its popularity has sky rocketed. In 2012, Davenport declared data scientist to be the sexiest job of the 21st century, a fact that has some positive and some negative consequences. 

+++

@title[Positive impact]

There are currently **130,838** packages on PyPI, <br>the Python Package Index. 

Note:
One positive consequence is that data is accessible to absolutely anybody, there are lots of open data, lots of online courses for teaching yourself programming and statistics, two of the most basic tools of data analysis. The costs associated with computing have dropped, as the infrastructure gets better. Lots of open source libraries have been developed that implement algorithms that used to be inaccessible. A few years ago, what I thought was clearly the best choice for making publication quality figures was ggplot2, an R package, but now I can no longer say that as a plethora of graphing packages have become available for lots of different environments. This is great! The data/technological revolution is upon us. It's cheap, the tools are accessible, and there is a lot of raw material. 

+++

@title[Negative impact]

Which questions can the data answer? 

Note:

Whether or not these data are suitable for answering specific questions depends on the quality, type of data, how extensively it covers variables that are relevant. Those are separate questions. Those are the questions that have to do with the science part of data science. 

Which brings me to the flip side, if you'll allow me this one binary of positives vs negatives. One negative consequence of the popularity of data science is that we now have a responsibility to at least try to convey not only the code you need to write to analyze data, but also concepts that are perhaps more abstract but very, very important concepts.

+++

@title[Tools vs science]


Are we putting too much emphasis on tools? 

Note:
I would dare suggest the observation that the data science training community has a tendency of placing a lot of emphasis on the tools: "you need to learn python, you need to learn how to use specific libraries such as tensorflow, numpy, nltk, and scikit-learn, you need to learn how to use Tableau, and extract-transform-load engines like Alteryx". I think that this emphasis on the tools ends up giving people, particularly those who haven't had any previous research training, the false sense of security in their data analyses, while key concepts that have to do with the science part of data science remain in the dark.  

+++

@title[The reason for tool emphasis]

Science is not only about the tools. 

Note:
It seems unreal that I even feel the need to make this statement, but after thinking about it for a while I think that emphasis on tools can be justified. Learning how to use a tool is something that you can something you can teach yourself through a MOOC, or through participating in Kaggle competitions. Whereas learning how to problem solve like a scientist, meaning questioning every step that you take and every number that you come up with, is perhaps more difficult to learn online. 

There are also subtler distinctions, data scientists are not software developers and they are not analysts, even though they use similar tools. I won't go into a point by point comparison, but if you're interested we can talk about this later. 

---

@title[Learn from the pros]

<img src="images/venn_diagrams_data_science/Slide1.jpeg">

Note:
So who are these people? Who are data scientists, and can we study them to help us keep the science in data science?

There is a myriad definitions of data science. This one is my definition. It's biased in that it highlights the interdisciplinarity of data science above all else that goes into it. It also reveals data science to be a heterogeneous collection of multiple fields, depending on the data that you have. Another point that flows from this view is that the disciplinary knowledge is essential. 

I think of the ubiquity of tools as analogous to have all the drills, lumber and nails that you need, and the development of the technical skills as analogous to knowing how to put them together to build a house. In this analogy, the disciplinary knowledge perhaps representes an architect and urban planner who can make sure that the thing you are building makes sense. 

+++

@title[What is data science?]
<img src="images/venn_diagrams_data_science/Slide2.jpeg">

+++

@title[Who am I?]

<img src="images/venn_diagrams_data_science/Slide3.jpeg">

Note:
My field is statistical genetics, sometimes also called computational genetics. So this view of data science is most definitely biased by my training over lots of years of graduate school and postdocs. This venn diagram reprsents who I am, the specific manifestation of data science is at the intersection of statistics, computer science, and genetics. I'd be curious to hear about how you would describe yourself in this framework, even if you need to switch out statistics and computer science for other disciplines.

---

@title[Stages of data analysis]

<img src="images/venn_diagrams_data_science/Slide4.jpeg" >

Note:
This is one way to think about the stages of a data analysis. Broadly speaking, these are analogous to any other project, so I'm hoping that you'll be looking for parallels with your process as we go through the rest of this talk.

One thing I'd like to note is that in practice this process is never so clean and linear. It is often the case that once you start getting to know the data you realize that you are missing key information, variables that you don't have data on and which may be key in allowing you to reach meaningful conclusions. Spending a good amount of time in the design phase, and running small pilot studies are two way to try to prevent that from happening. Notice that these actions have little to do with the technicalities of the tools, and more to do with a critical awareness of the strengths and limitations of your design. 

This middle piece right here, getting to know and trust the data, is also why I am not a fan of ETL engines that automate that process. If that's a topic that you're interested in we can talk more about it later. 

+++

@title[Stages of data analysis 1]

<img src="images/venn_diagrams_data_science/Slide5.jpeg" >

Note:
There is a lot that goes into each of these broad stages. The details of the bullet points here are not important, but what I'd like to point out is just how much of the effort is spent on the early stages. When we think about data science we often think of it as synonymous with the generating results stage, and you most definitely can jump right in and generate results that don't make sense. There's a lot of literature on lying with statistics, so we won't go into that now. Jumping to the results stage too early is just one way to lie with numbers, whether deliberately or not. 

Many times graduate students will generate these models, without digging deep inside them. I think this observation holds particularly well for fields like the biological and social sciences. There appears to be a fear of numbers, a mystical mist that we think is where numbers live, and that we can't understand them. That fear is costing us greatly, because you are less likely to touch something that you are afraid of. 

+++

@title[Stages of data analysis 1]

<img src="images/venn_diagrams_data_science/Slide6.jpeg">

Note:
In any case, For the rest of the talk, we will examine a just a couple of the stages of data analysis, and what it really means to proceed through them mindfully and critically.

Please note again that these stages are not linear, there should be all kinds of arrows pointint from most places to most others, all kinds of iterative processes, which I'm omitting for clarity. 

I'll use some of my own projects as examples. 

---

@title[Refine the question]

<font color="#008080"> DESIGN: Refine the question </font>



Note:
One of the major decisions to make in the design phase is defining the question that you'd like to ask, while taking into account the information that is available. 
I'll use one of the projects that a PhD student from Modern Languages and Literatures, Elena Bonmati, is currently working on. I'll briefly but explicitly describe our path through these ideas. 

This question: are you asking the right question, is a cheeky one, because to answer it you need to define "right". 

+++

@title[Collaborations]

<font size="6" color="#008080"> DESIGN: Refine the question </font>

can we identify pairs or teams to work on collaborative research projects? 

Note:
So here is what we were interested in answering. There's quite a bit of literature by now that suggests that one of the key components of innovation is interdisciplinarity. That is one of the founding principles of the Center for Computational Science, as an interdisciplinary hub for research. If it is indeed true that there is a relationship between innovation and interdiciplinarity, this sounds like a good question to ask, right? One that many people would like to know the answer to. 

Please take a minute and come up with as many weaknesses in this question as you can find.

+++

<font size="6" color="#008080"> DESIGN: Refine the question </font>

@title[Caveats]

But what about...
- available data
- distance between disciplines
- relevance of pairing to an actual problem 
- etc.

Note:
UM has 3,129 faculty members, and 911 additional staff researchers, so the space of possible pairs is very large. How do we propose to reduce that space into the pairs, or teams that make sense to put togeher? What data can we use to answer this question, and what is an appropriate range of disciplines to consider: should pairings between music researchers and a political scientists be identified, or only more conventional pairings that may be more likely to work out, such as marine scientists and computer scientists? Wait a minute, to answer that question we need some kind of measure of the relationships between disciplines! Not all pairings are going to make sense together, particularly in the absence of a problem to which the disciplines will apply themselves. 

+++

@title[Project flowchart]

text of recent faculty publications
<br>
|
v
<br>
areas of expertise in tools and domains
<br>
|
v 
<br>
relationships between disciplines

Note:
I find it useful to actually get my hands on some data that may, at a first glance, be suitable for answering this question. I know that I am incredibly lucky to be able to do this at no real cost, thank you data revolution. In this case, we decided that we would use text from recent faculty publications that we could access through the programmatic interfaces to various databases, use that text to infer the researcher's areas of expertise with text clustering and topic modeling, then create network diagrams that may help us visualize existing relationships between researchers from different disciplines. 

The question is still pretty vague, but it has already transformed, to "What can we learn about interdisciplinary teams in our organization, based on recent publications?", which is a fundamentally different question than where we started. That's okay, I need to be clear that there's nothing wrong with the question evolving, as long as you are acutely aware of the fact that it has evolved. 

+++

@title[Refined question]

Refined question

Note:
Catalyze collaborations was a problem that was stated through my CCS glasses
Once we saw things through other people’s eyes (faculty who don’t want to be told to collaborate and other admins) the problem was reframed completely and became diffferent than what we originally thought it was
Now it is "how does the organizational structure of the university reflect the work that is being done in practice" which is a reflection of me feeling like I don't belong in any one discipline 
This is something about me that is taking flesh as a project

+++

@title[Abstract to concrete]

Take away:
Translating the abstract to concrete involves a series of decisions. 
<br>Those decisions are, to a certain extent, arbitrary. 

Note:
Once your question has been translated to the concrete, does it still reflect the general idea behind the abstract question? Often times the answer to that is no and you need to be able to evaluate both the probability that the answer to that is no, and how it impacts the inference that you can make.

+++

Perhaps this is just the way science goes.

Note:
Were those initial decisions mistakes? Is it possible to have gotten to the point we got to without having gone through the process that got us here? I don't know. This is a larger question that touches on the idea that science is "self-correcting", because this process of refinement doesn't only happen within a study, but between studies. After all, where we break up a project into a publishable piece is also an arbitrary decision. This idea that science is self-correcting invokes commentary on the public perception that scientific studies produce contradictory results, so how do you know what to trust? One study shows that a compound is carcinogenic, the next study shows that it's harmless - as a consumer, what do you believe? Diet studies are notorious, but this phenomenon is not exclusive to them. 

The question "what can I trust?" makes sense in the context of "there is one correct answer that you should be able to find out through one study", because it assumes that there IS something to trust, which is a very elementary view of how science works. In reality, the "answer" that you get is at best only applicable to a very specific set of circumstances, and varying levels of confidence. Data is messy. Working with it requires being comfortable with not knowing things, which is not a space that is comfortable for many people. Perhaps it's okay that it's messy. 

---

@title[Identify sources of bias]

Controls and confounders
Code bugs

Note:
Bias is a huge subject. Sometimes there are things you can do to mitigate it and sometimes not. For example, if I'd like to identify patients with multiple sclerosis, I might go to a neurodegenerative disease clinic. That makes it really easy for me to grow my sample to a good number, but the patients that I identify that way may be different from a random sample from the population. 

Perhaps their symptoms are more severe, if they needed to be seen by a group of specialists in a specialized clinic rather than doctors at the neurology department of a hospital. I'm also probably over-representing the patients who have access to health insurance, and under-representing those who do not. 

So you see some fundamental statistical concepts, samples and populations, come into play, and are really important for interpreting any results I generate from that study. 

Let's also relate this to our previous topic, refining the question. The original question was "Is there a difference between non-Hispanic white patients and Hispanic patients in the clinical characteristics of multiple sclerosis?" The question I'm actually answering is ""



+++

@title[Controls]

Should you smile in the selfies you post to social media?


Note:
Controls are essential to make sense of your observation
How tall is tall? 
Is there really a difference between two groups?
All else needs to be held constant. 
The things that you think of, the variables you choose to collect data on 
may depend on your point of view. 
Someone else, with a different set of biases may select a different set instead. 

For ML approaches you may be tempted to say 
"well, this doesn't apply, because it's the algorithm that chooses relevant features, not a human"
Howeevr, the human still determines what is available for the algorithm to learn from, which is how we are ending up with racist AI

We have all heard of the example of google gorrilla
We are making the AI in our image

On controls
Can you find more positive sentiments on good weather days vs bad weather days? 
Compare books by country based on their average days of subshine per year
Or a non-fiction or fiction books which were written throughout a year, if we have the info on when the authors started writing and make assumptions about how many words they wrote per day

+++

@title[Threats to the results]

What are the threats to the validity of your results? 

Note:
Both selection bias and controls are threats to the validity of your results, if you cling tightly to the general form of the research question that you are looking into, you will be expressing inaccuracies. 

+++

@title[Threats from logical errors]

Beware of bugs in the above code; I have only proved it correct, not tried it.
<br> <font color="#008080"> -  Donald Knuth </font>

Note:
These are the words of Donald Knuth, author of The art of computer programming, a legendary book from 1968, communicating the difference between math and buggy reality. 

What gets lost when you abstract away the messy, physical world? You need to be aware. 

The fact that programming languages are much less ambiguous than natural languages makes it even more critical that we code with a conscious awareness of the biases that our code could introduce. 


---

@title[Variable transformation]

Variable transformation 

Note:

+++

@title[PCA of IMSGC study]

<img src="images/ms-pca.jpg" height="550">
<br>
<span style="font-size:0.4em">Sawcer et al. 2011, Nature Genetics </span>

Note:

+++

@title[]

Your social views may impact how you treat key variables. 

Note:
If you think back to the time before PCA was used to correct for genetic ancestry, 

Race is a very socially charged topic, for lots of good reasons. Since your views on race can influence how you treat it as a variable in your data analysis, you need to be aware of the connections between your social stance and the results of your study. 

Who you are comes up again.  

---

@title[Rabbit hole paths]

Rabbit hole image

Note:
Visualizing the rabbit hole which is actually an ant colony
The route you take through the colony depends on what drew you which is affected by your biases
You create a route based on who you are rather than what it actually is

Stephanie Yahn credited with idea

+++

@title[Ant hill paths]

Ant hill cross section image

Note:


+++

“A lot can depend on little things.” 
<br>
<br>
 - Daniel Messinger 

Note:
on the idea of relying on neural networks to understand and combat the replication crisis in psychology

+++

@title[Rorshack]

Rorshack test in psychology

Note:
You see what you are

In the expanse episode of the imaginary worlds

+++

Datum is latin for given, but when you are working with data, there's nothing that's given
It's all in the eye of the beholder

Tim Norris 

