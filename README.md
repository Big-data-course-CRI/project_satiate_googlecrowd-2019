# Master-Aire-2019
This is a beginner project of collecting, analyzing and visualising data.
Assessing the permeability of knowledge between students in the Master AIRE of CRI.

**1.The goal**

This is a beginner project of collecting, analyzing and visualising data. Assessing the permeability of knowledge between students in the Master AIRE of CRI.Inspired by Moreno 1986's sociogramme, I wanted to map out the relationship between student and see if there was any correlation with passing of knowledge between them as well as, assessing the level of potential permeability of knowledge bewteen students. Based on their past interaction and the status or their relationship, I wanted to evaluate how easy is for knowledge to be passed from on student to another. My goal was also to see which students are actively recipient/giver of mentorships and maybe see if some practical application could be devised from it, like integrating workshops or mentor status in the master.

**2.The process**

**A.The form**

I started by trying to find a way to organize all the criteria I had decided on and got self assessment from the google form. 15 students responded to my form. (Link to the form)

**I.Content of the form**
The form starts with a presentation of the study and what the participants are accepting to do and an example of sociogram:


Hello!
It takes 10-15min to fill!
This form is going to be used to map out the links and learning exchanges between students in the M1 AIRE Master, like Moreno 1986's sociogramme. You can check it below! he mapped out the reciprocity of desir from kids, from the same class,  aged 11 to 12 to sit next to each other (They had 2 choices max).
It will be ANONYMISED and available for all in ABSTRACT représentation, to discuss it and I will also share the process I used to map the network and weight (calculate how strong) the link and exchange between two people is.
It would help me tremendously in my Big Data assignement if you filled it.
Keep in mind that this is probably not going to be 100% accurate of the link and transference between people because there is only so much you can know with questions.
If you have any problem you can contact me at elodie.coquillat@cri-paris.org!
Elodie ~🌺

PS: if you want to send another response, and overwrite the first one,  please write the date and time next to your name in the first question to overwrite the first questionnaire!


Each of participants had to respond to the following questions:

1.In what Master are you?
-Lisc
-Lesc
-Disc

2.Are you part of any club?
-KnoMi
-Le CRI de la Nature
-Ikigai Club
-SynBio
-Knowledge4All
-L4S
-Launchpad Club
-Learning4Sustainability (L4S) and CRI Launchpad
-Theater
-Music Club
-Multicultural
-Other


*Question 3 and 4 where ask for the Lisc, Lesc and Disc student in 3 seperate and consecutives parts of the form, to make reading the heading easier, as well as to not overwhelm the student with the amount of questions visible at once.*


3.What is your relationship with that student?
-Thats me
-I know them
-I don't know them
-We share a class together
-We are friend
-We are close friend
-We are best friend

4.How did you learn with them? you can select multiple answers.
-Thats me
-They helped me with a difficulty I had in a class
-They taught me a subject
-I taught them a certain subject
-We had a project together but we each had our task
-We had a project together and we learnt from each other
-We share a specific interest and discuss them
-We don't

5.Are you actively sharing knowledge and information on the various master group chat? 
-yes
-no

6.Which group chat?
-The one for your track
-The one for the whole master
-Both

7.What kind of knowledge?
-Related to an ongoing class
-Things you find interesting
-Related to the functionning of the master (room number, change in planning, etc)

8.Do you want the mapping to be anonymous?
-yes
-no


**II. Goal of each question**

Questions - What I wanted to assess:

1.In what Master are you?
Physical proximity during studies, Closeness of subject of interest

2.Are you part of any club?
Physical proximity during studies, Closeness of subject of interest

3.What is your relationship with that student?
Sympathetic feelings,

4.How did you learn with them? you can select multiple answers.
How prone are they to share/receive  knowledge

5.Are you actively sharing knowledge and information on the various master group chat? 

*How prone are they to share knowledge. This question comes from my experience of one specific student sharing many link during and after class to reference the professor cited or reference from his personnal knowledge..*

6.Which group chat?
Openess to student that are not in their track

7.What kind of knowledge?
Nature of the knowledge

8.Do you want the mapping to be anonymous?
Consent to be identified in the study

**3.The outcome**

-Google form results

I removed the names of students, since a majority of them didn’t want to be named and replaced them with a random list from http://listofrandomnames.com/ 

**The results of the google form can be found in the repositary in csv format.**

Before having the dataset, my goal was to give weight to the sympathetic links between students by simply dispatching the answer of quetsion 3.(What is your relationship with that student?) on a scale from 0 to 

---------------- 

Thats me = 0

I don't know them = -1

I know them = 0

We share a class together = 2

We are friend = 2

We are close friend = 2

We are best friend = 3

------------------------

I decided on these value arbitrarily. My problem was, how to know if someone is more likely to share knowledge, learn from someone, depending on their closeness?
Does sharing a class makes you more prone to share knowledge with all your classmate than if you are note in the same course, but you are best friend? 

I tried to attribute coefficients to the past event where student had exchanged knowledge as such:

----------------------

Thats me = 0

They helped me with a difficulty I had in a class = 2

They taught me a subject = 2

I taught them a certain subject = 2

We had a project together but we each had our task = 1

We had a project together and we learnt from each other = 4

We share a specific interest and discuss them = 4

We don't = 0

-----------------------
My intuition was that if a student has helped another, has been taught  or they reciprocally helped each other then they have a propensity to being helpfull, or at least offer back help to the student that helped them thus making them more likely to help their fellow student in the futur. 

This method was too unmathematical to produce a usable and clean dataset to be used with GEPHI, since every manip and replacement was done by hand. So after giving up on working on the result of my google form I decided to rework the already existing graph from google with illustrator and experimenting with different type of graphs, to assess character traits in students, regarding social types and learning style. These are still arbitrary, but more understandable from a sociological standpoint.

**4.Results**

They can be found in pdf form in the folder of this repositary.
This led me to identify the following types:

*Social type*

- Average social student: they are considered a friendly relationship with almost all the population

- Not very social student: they are unknown or predominently a considered a classmate by the population

- Very social student: they are strongly categorized as friend, close friend or best friend by the majority

- Partially social student: they have close relationship to a group in the population but are merely known or even unknown to the rest of the population

*Learning style*

- Solo: they predominently have no learning relationship with the rest of the population

- Social: they have a learning style that is based on shared interest

- Mutual: they learn in settings of mutual exchange, like group project, teaching to one and being taught



_**Conclusion**_

This project is only a first approach to what data analysis is. It mostly allowed me to see different types of profiles and learning styles, but also highlights all the parameters that need more refinement and precision to be objective and quantitative:

- Are my questions tragettingthe right variables?

- Is my phrasing unbiased ( on respondant decided to not qualify their relationship with 3 other people, one systematically put best friend to all the classmate of her specialty)

- I assessed the learning style and Social type visualy, if I had the skills to quantify properly with statistics each traits, would the number verify my assessements?

- My sample size is very small, 15 persons only, is a not representative of the french system since we are in an english speaking setup with multicultural students: do I need a preliminary study to assess how their background might be a variable that correlates to learning style, rather than the ties they have with their classmates?

*A study on helpfulness or solidarity is needed to better assess how much impact each event I listed has on the propensity of one student to help another. Then maybe better questions could be:*

- Does the subject consider they have valuable skills? (notion of self efficacy)

- Are they good at sharing (what is good sharing)?

- Are they willing to share?

- What relationship make a mutual exchange more likely?

Also studying the dispersion of knowledge could be interesting:

- What knowledge is being shared?

- How much?

- At what rate?

- Through which student?

And from this draw conclusion on what organisation makes an efficient and self sustainable campus, where information can circulate better, where co-learning is actually happening.

From this it would be interesting to study how different types of knowledge meet and merge, mutate and become interdisciplinary, by considering these unit of knowledge as meme, as Richard Dawkins defined it. Since our campus is interdisciplinare, I wonder if there is collaboration from different field of knowledge between students.

And if there isn't, how can we test ways to bring it about?



------------------------------------------------------------------------------------------------------------------------------------

**Skills needed to start Data Analysis and Network Analysis and making a project on Github**

- Understanding of how github works

- Basic editing skills for the read.me file

- Theoretical understanding of what a Network is

- Knowledge of Mathematical Probability and statistics

- Research methodology

- Data collecting or scraping skills

- Python skills for Data cleaning

- Or R skills for Data cleaning

- Understand how Gephi works and to what model each setup refers to analize what is happening in network
