# Design Considerations

Choosing to go native Android. Could go with React JS and HTML 5 but I just want something that works sooner than later. Considering a web based application where there is a central data source, etc. Thinking it through, it is best to have the data local and sync/backup on the cloud as needed. Later a web app could be developed to also work on the same data source, but that's another item.


## Can ICalendar format work?

It can define most the objects that we want. We could hijack some fields for application specific content without much trouble. If this is done, then you can use your own calendar app to handle notifications and alarms, etc. At least at the beginning, then with time develop a built in calendar.

For scheduling ical has to work.



# Architecture

When starting the app for the first time:

I. Collect info like name, password, etc. to create a profile.
II. Self Evaluation
  1. Mission Statement (Revision tracking) Review at regular intervals
    a. Values - Clearly list what is most important to you.
    b. Roles - List which roles you fill in life that are most important
    b. Vision - How would you like to be described at your funeral? 
    c. Purpose - What do you 
    
  2. Freeform self evaluation - Complete at regular intervals
    a. What is going well? - List specific evidence of . 
    b. What is going poorly? - List specific evidence. 
    c. What has changed? - Write down what you have learned and how your point of view has changed. Identify beliefs or opinions that you maintain that you are unsure of.
    d. What can I do to change - Identify things that are in your control. Identify things that are not in your control. 



At the top there exists a personal mission statement (Optionally a vision statement as well). Nice to have some sort of guide to help develop this mission statement. Focus on principles vs centers. "To be a good father/worker/neighbor/etc. i will have \[some principle\]" I.e. Define what you want to become.

At the next level there are goals. Goals should align with the overall mission. Goals can be grouped into categories (work/health/financial/custom/etc.) Goals can be ranked/weighted by importance. Goals should be SMART. It would be nice to have some sort of visual representation to show how priorities are distributed across categories to attain a life balance. I.e. Define what you intend to accomplish along the road to becomming.

At the next level are tasks. Tasks should not be inherently linked to goals. There are tasks that have to get done that don't have anything to do with your goals. I.e. tasks should be tagged by a goal.

How do you measure goal progress? Sometimes you will be able to list all the task breakdown for a goal. You could track number of tasks (Scrum style) like a burndown. Some goals will be very quantifiable. e.g. run a marathon, where progress could be measured in distances attained. I think I like the scrum style more. A burndown chart is pretty good. What about a sprint?

Handling subtasks is tricky. Order tasks that must be sequential is a bit tricky too.


Takeaways from GTD vs. Eisenhower square - The GTD system is entirely consistent with the urgent/important matrix. The whole GTD syntax seems a bit overkill though. One problem with GTD is that there are countless "less than 2 minute" tasks that are not important (and probably not urgent) that need to get done and then baloon out of proportion once begun. Ultimately there needs to be some enforcement of how tasks are prioritized and scheduled. GTD has a good system but can be simplified as well.

This brings up the next critical component, planning sessions. There needs to be guided planning to help select the correct tasks, how to break down bigger tasks, etc. Perhaps (As opposed to sub tasks), a tasks can be divided. E.G. Write a book -> Write first half, and second half. This could be presented nicely though. E.g. if the tasks estimation is too great, by clicking "breakdown", it asks "What steps are required to achieve this task?" You create a list or two or more item titles. Then, the app cycles through each item in the list to flesh out the details.


What about recuring tasks and habits? Recurring tasks should all have a fixed timeframe (and really should give a notifcation when on the last one). Some recurring tasks aren't going to be an end in and of itself, e.g. attend class, or do rounds at work. Better, recurring tasks are goal centric. E.g. exercise daily. I like the idea of a reminder "Did you __ today?" similar to most habit tracker software.  Really though, it is silly to record "How many pushups/pages read/steps walked/etc." You know how much you are supposed to do, just need to know if it happened or not. 

Goals are not an accounting of how much or how many of a thing you have done. An appropriate goal is relevant to your mission. Therefore, tasks to achieve that goal aren't simply, do a tasks X number of times, or achieve X of some thing. 

Journal is a must. Nice to have markdown support. "Captain's log."

Need to look at a franklin planner system and model this similaraly.

## Insights into the psychology behind this

The goal of this app is to be a tool to facilitate self-improvement.

Self-improvement is defined as becoming a beter individual in reality (not just from one person's point of view). People generally are motivated to improve themselves.

### Self-evaluation motives

https://en.wikipedia.org/wiki/Self-evaluation_motives

It has been well studied and shown that people generally want to understand who they are. Ultimately, one must know themself to effectively understand who they want to become.

Why would someone want to evaluate themselves? The motivation to self-evaluate is broken into three sub-motivations.

* Self-Enhancement - the desire to maintain a positive self image. People want to feel imporant; like they are enhanced.
* Self-Assesment - the desire to obtain an accurate vieow of the self wether positive or negative.
* Self-Verification - the desire to confirm previously held beliefs about one's self wether desireable or undesireable.

The better question is why *should* someone evaluate themselves?

If we make the assumption that self-evaluation is effective, than tautologically we will find the answers to the important questions about ourselves. 

#### Self-Enhancement
This is a controversial one. On one hand, it is good to evaluate youself positively, to see the good in yourself, and to have a good self-esteem. On the other hand, people generally hold unrealistic views of themselves and think they are superior than they really are. The notion of a "healthy optimism" or "high self-esteem" has been shown with substantial evidence to be a good thing. To be able to identify the good in one's self is good. However, generally people aren't very realistic in their self-enhancement and fall into three illusions:

* Above-average effect - unrealistically believing that one's self is better than average.
* Illusions of control - overestimating the effect people have on the outcomes of their circumstances. (e.g. if I throw the dice just right, I can get them to turn up how I want)
* Unrealistic Optimisim - incorrectly evaluating future outcomes positively ignoring past evidence or without evidence at all.

When undergoing self-evaluation, whether deliberate or not, people will self-enhance even if percieved that this is pridefull and selfish, it's going to happen do some degree. Self-evaluation in for this purpose has an impacton a persons feelings and thoughts about themselves, however in regard to characteristics that are unmodifiable.

#### Self-assesment
People want to know the truth about themselves. People want to know where they stack up. This is satisfied by highly diagnostic information and evidence. Self-evaluation for this purpose is associated with a change in behavior, especially in regard to characteristics that are modifiable.

#### Self-Verification
People tend to have a deeply fixed perceptions of the world and seek to verify their believes regardless of if they are positive, negative, or true or false. The more firmly held a belief, the more people prefer diagnostic information regarding that belief. People like to say "Aha! I knew it." People tend to disregard information that goes against what they believe about themselves, more so if they feel like that characteristic is unmodifiable.

Self-evalauation for this purpose is associated with a change in how one thinks about themselves, albeit conditionally.


7 habits does a great job of putting this in lay terms, e.g. Circles of influence, paradigm shifts, etc. Perhaps 7 habits implies that sucessful people are more prone to be motivated by self-assesment rather than by self-enhancemnt/self-verification.

Regardless of why someone might want to evaluate themself, the question still remains of *how* can this evaluation be done? I think it is important to take into consideration these motivations and try to curb self-enhancement and self-verification toward self-assesment.

