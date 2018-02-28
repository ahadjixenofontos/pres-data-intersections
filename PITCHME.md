### <font color="#008080"> How to build a data analysis pipeline </font>

<br>
Athena Hadjixenofontos, PhD
<br>
Director of Engagement
<br>
Center for Computational Science
<br><br>
ahadjixenofontos@miami.edu
<br>

---

@title[1. Gentoo penguins]

![Gentoo chick chase video](https://www.instagram.com/p/BfY0z66AtIG/?hl=en&taken-by=natgeotravel)

Note:
We're about to watch gentoo penguins, and try to interpret their behavior. Here's some context that may be useful. The penguin in the front is a parent, and the penguin in the back is the chick. 

What do you think they’re doing?

Those are colored by your experience of the world. YOUR experience
If you’re a mom and had a rough morning with the kid you may see it as the mom is running away. 
If you are a student you may see it as the chick playing with its parent and at the same time learning how to get away from predators by mimicking its mom.
If you are an evolutionary biologist you may see it as the mom making sure that only the fittest offspring get fed. 
All you actually see is penguins running.

Anthropomorphism is one example of seeing things not as they are, but as we are. 

---

@title[2. Anais Nin]

<img src="images/spotlight.png" height="400">
<div align="right">
> We don't see things as they are, we see them as we are. 
> <br> <font color="#008080"> - Anais Nin </font>
</div>

Note:
We will spend the remainder of this talk exploring examples of how this shows up in the various stages of data analysis. 

---

@title[3. Hume quote]

> ... it is impossible for us to **think** of any thing, which we have not antecedently **felt**, either by our external or intenal senses. 
> <br> <font color="#008080">David Hume </font>

Note:
Before we go on, I need to acknowledge, that of course, this is not a new idea, but rather one that is related to the theory of knowledge. Epistemology is the field of philosophy that asks what I think are some of the most difficult and most fascinating questions, such as "what can we actually know?". There are a few main schools of thought: the empiricists who insist that the ultimate source of all knowledge is observation, and the rationalists who insist that intellectual intuition of clear and distinct ideas is the ultimate source of all knowledge. 

My personal favorite, Karl Popper, stands both in neither camp and also somewhere in the middle, believing that both observation and reason have important roles, but perhaps that those roles are somewhat different than both empiricists and rationalists claim they are. 

My perhaps naive view is that intuition is developed through observation, and that scientists, being human beings, cannot escape the biases introduced by the very specific way in which humans perceive the world, process information and reach conclusions. 

As we saw with the penguins, having a sharpened intuition by repeated contact with a topic, like the evolutionary biologist, may help us get closer to the truth, if such a thing exists. As soon as you switch environments, or perhaps type of data, the intuition needs to be built up again. 

---

@title[4. Why is this important?]



Note:
I do not intend for this to be just another talk on how biased algorithms are cheating you of a good credit score or on avoiding blind faith in data, which of course we should do. 

But I think the context is important. The popularity of a field which we now call data science has sky rocketed. "Data scientist is the sexiest job of the 21st century" which has some positive and some negative consequences. 

The positive consequences is that data is accessible to absolutely anybody, lots of open data, lots of online courses to learn programming, one of the most basic tools of data analysis. Lots of open source libraries have been developed that implement algorithms that used to be inaccessible. This is great! The data revolution is upon us. 

Whether or not you can answer specific questions you care about with the quality and type of data that is available is a separate question. 

On the flip side, the fact that data and ways to analyze it is open to absolutely anybody also means that we now have a responsibility to at least try to convey not only what kind of code you need to write to analyze data, but also more abstract but very, very important concepts,

I think that I'm observing a tendency of placing a lot of emphasis on the tools: "you need to learn python, you need to learn how to use specific libraries such as tensorflow, numpy, nltk, and scikit-learn". I think that this emphasis on the tools ends up giving people the false sense of security in their data analyses, while key concepts that have to do with the science part of data science remain in the dark.  

---

@title[5. Lots of ways to learn about tools]


Note:
The emphasis I think can be justified. Learning tools is something that you can do through a MOOC, and through participating in Kaggle competitions. Learning how to problem solve like a scientist, meaning questioning every step that you take and every number that you come up with, is perhaps harder to learn online. 

As Director of Engagement for CCS, I meet a lot of people, most of whom are in some way related to data science. The only ones I've seen who have both the tools and the science are those who've gone through a PhD, or worked in the R&D department of a company. Either way, we are talking about researchers, not hackers and not software engineers. 

---

@title[6. Learn from the pros]

<img src="images/venn_diagrams_data_science/Slide1.jpeg" height="600">

Note:
So who are these people? Who are data scientists, and what can we learn from them about keeping the science in data science?

There is a myriad definitions of data science. This one is my definition. It highlights the interdisciplinarity of data science. The field changes depending on the data that you have. 

I'm not talking about analysts here, there's a big difference between the question "how many dolls did we sell this quarter?" and ""

---

@title[7. What is data science?]
<img src="images/venn_diagrams_data_science/Slide2.jpeg" height="600">

---

@title[8. Who am I?]

<img src="images/venn_diagrams_data_science/Slide3.jpeg" height="600">

Note:
Of course, this view is most definitely biased by my training in both graduate school and postdoctoral positions, as a computational geneticist. This is who I am, my version of data science is at the intersection of statistics, computer science, and genetics. So take it with a grain of salt. 

---

@title[Stages of data analysis 1]

<img src="images/data-analysis-overview.001.jpeg" height="600">


Note:
For the rest of the talk, we will examine the stages of data analysis, and what it really means to proceed through them as a data scientist.

A big part of keeping the science in data science, is being aware of your biases, your assumptions, the ways in which you've shaped the questions you are asking based on your collection of previous thoughts and experiences, and based on your five human senses and your human reasoning. 

This comes in very early on while you are still designing the way you'd like to answer a question. 

---

@title[Problem definition]

Catalyze collaborations was a problem that was stated through my CCS glasses
Once we saw things through other people’s eyes (faculty who don’t want to be told to collaborate and other admins) the problem was reframed completely and became diffferent than what we originally thought it was

---

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


---

> Beware of bugs in the above code; I have only proved it correct, not tried it.
> Donald Knuth


Note:
These are the words of Donald Knuth, author of The art of computer programming, a legendary book from 1968, communicating the difference between math and buggy reality. 

What gets lost when you abstract away the messy, physical world? You need to be aware. 

The fact that programming languages are much less ambiguous than natural languages makes it even more critical that we code with a conscious awareness of the biases that our code could introduce. 


---

@title[CCS Data Scholars]

Note:
I am very excited that what we've come to call data science is so popular. I am not alone in thinking that this "trend" won't go away. For that reason, last summer we hosted 18 girls through a partnership with a local non-profit organization called Educate Tomorrow, which works with foster care and similarly disadvantaged youth 
We created a program for them to at the very least expose students to the various facets of data science early on, and at most, hopefully, inspire them to incorporate a data-mindset in the way they view the world around them, and to incorporate programming in their toolset. 


---

@title[Projects across disciplines]

Note:
A key feature of this program is to showcase how data science can be married to almost any other discipline. If you're into literature, as this audience knows all too well, you can open up a whole world of questions that you can ask by picking up the tools. Same if you are into questions that have to do with "where" as represented by spatial data, or images. 

---

@title[Image project]

In our image processing project, the main question we were asking was whether it's better to smile or not to smile in the selfies that you post to social media. 

---

Rorshack test in psychology
You see what you are

In the expanse episode of the imaginary worlds


---

Note:
Maps reflecting the points of view of the people making them
Exercise in selection
Omitting and emphasizing certain details
Your decisions are responsive to your motives for making the map

Cuban exile community’s map highlighting conflicts

Map from the Castro government highlighting assassination of school teachers

Instead of representing reality they are proposing a reality

The agendas of the agents are being played out

Rob
Kichin

The Data Revolution: Big Data, Open Data, Data Infrastructures and Their Consequences

Assumption of sea faring

---

“A lot can depend on little things.” Daniel Messinger on the idea of relying on neural networks to understand and combat the replication crisis in psychology



---

@title[Rabbit hole paths]



Note:
Visualizing the rabbit hole which is actually an ant colony
The route you take through the colony depends on what drew you which is affected by your biases
You create a route based on who you are rather than what it actually is

Stephanie Yahn credited with idea

---



Datum is latin for given, but when you are working with data, there's nothing that's given
It's all in the eye of the beholder

Tim Norris 

