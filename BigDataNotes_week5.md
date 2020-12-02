# 5.0.0: Week 5 Introduction

null Weekly Introduction

Welcome to week 5! This week will focus on big data applications. We will start by looking at biases, exploring the effects of biases on big data analysis and discovering the techniques that can be implemented to avoid them. Next, we will look at the challenges in analysis when dealing with large datasets exploring how subsets can be implemented and utilised. Finally, this week we will investigate failures in big data including writing a report that analyses and identify the reasons for failure and ways in which they can be prevented.

As you work through this week’s content, consider the following questions:

  1.  What is the difference between conscious and unconscious bias?
  2.  How can you identify unconscious biases in yourself and others in the team?
  3.  What unbiased ways are there to generate subsets?
   4.  Are there any ways not discussed here that you could utilise subsets in your analysis?
   5. Are there any additional reason, not listed in the video, for big data systems failure?
  6.  What might be the extended impact on an organisation of a big data system failure?
 7.   Are there any circumstances where failure of big data may have an effect on a wide population?

 There are a number of reasons why big data systems fail and typically this starts with everybody involved blaming everybody else.  It is important to be able to evaluate all of the factors and determine the reasons for failure and what lessons can be learned to prevent similar failure in future.  This session will explore some common reasons for failure and techniques to overcome them.

While you watch this lecture, reflect on the below questions.

    Are there any additional reason, not listed in the video, for big data systems failure?
    What might be the extended impact on an organisation of a big data system failure?
    Are there any circumstances where failure of big data may have an effect on a wide population?

# 5.1.1 Subsets
- Simpsons paradox
has two elements to it. 
- data is not additive, and data sets are not
additive.
-  Essentially, what is true in a subset is not necessarily true
when you bring that data back together. 
-  if we took subset number one, let's say this is a campus
of a university, and on that campus, we have 80% men and 20% women in that campus.
- But we then have subset two. Subset two is of a different campus. So, we have campus two
and campus two has 80% women and 20% men. When we then bring those datasets
together, and feed them into our combined data set, our overall result would say that we
have 50% men and 50% women.
## which of our statistics, which of our results here would actually give us the true
reflection of the gender balance on campus? Some would say that the combined data set of
- 50/50 is a reflection of the university as a whole, which it is.
- But depending on what question we asked, and depending on what we're actually analysing,
the important figure could be around campus one or subset one, or it could be around
subset two or campus two. So, 
- something that is true in a subset is not necessarily true
when you bring it together. And it works the same the other way, if we took the combined
data set and then broke it down the other way, something that was true in the combined
data set does not necessarily mean that it filters down to all of the subsets that you might
create.
The other side of Simpsons paradox is that data sets are also subsets also not transitive.
So, what we mean by this is that 
- you cannot infer a result of one test from another
-  match one week, one of the season
Manchester United played Liverpool Football Club, and Manchester United won the game
one to zero.
-, Manchester United have beaten Liverpool i
- following weekend, Liverpool
go on to play against Everton Liverpool FC scoring to Everton scoring one. 
- Liverpool has
now beaten Everton
-  week three Manchester United are going to play Everton. 
- Does the
fact that Liverpool beat Everton and Manchester beat Liverpool mean Manchester will beat
Everton? 
 ### The answer is no. 
 - There are too many factors at play here. There are too many
unknown variables. And it's not a true reflection of what's going to happen in the future.
So, you cannot transfer one finding such as match one resulted in the outcome that
Manchester United is better than Liverpool and match two resulted in Liverpool beingbetter than Everton does not necessarily mean that Manchester United are better than
Everton.
So, given that subsets have these flaws, and are not additive, they're not transitive.
What uses do we have for subsets and why do we subset? I suppose the first thing is that it
is very, very helpful to be able to break down large data sets and break down big data into
smaller data to deal with it. Subsets are the perfect way to test a hypothesis against a
randomly selected subset. This does not work. If you go through and manually select data
that will support your hypothesis or data that will disprove your hypothesis, it must be
randomly selected for subsets to be used to test a hypothesis.
Subsets can also reveal interesting angles of investigation that you may not previously have
seen. If we took our original example of the two campuses at university, if we just looking at
the overall data set, we would have said that there was no gender problems on campus at
all, and that everything is 50/50 and nobody should do anything differently. But when we
actually break it down into the two campuses, when we break it down into those two
subsets, we can see that there is imbalances in both directions on campus, and that further
investigation may need to be carried out to understand within those subsets, what are the
causes? What might be the factors? Is it something to do with the courses that are on offer
in those different campuses? Is it something to do with the lecturers or something to do
with the way that the admissions are handled? Is it something to do with the nearby
schooling, all of these things suddenly become investigation avenues, when we break out of
our main data set into those subsets, which is the final sort of use here that that that I want
to highlight is that subsets can also provide further investigation avenues, when Big Data
Analysis fails.
So, what I mean by this is, sometimes you're looking at so much data, you're looking at such
big numbers, or you're looking at such a widespread variants that it's very, very hard to see
any meaningful pattern. And it's hard, or you're seeing so many patterns, that it's hard to
pick up on a thread that's worth following to its conclusion. So sometimes breaking that
large data set down into subsets can provide you with insight that will allow you an avenue
to go and make a start on to go and investigate when all your other leads may have dried up
or there's simply too many leads to be able to pick one to follow.
So, this concludes our session on subsets. Next we are going to be talking about failure in
big data systems.
