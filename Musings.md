# Design Considerations

Choosing to go native Android. Could go with React JS and HTML 5 but I just want something that works sooner than later. Considering a web based application where there is a central data source, etc. Thinking it through, it is best to have the data local and sync/backup on the cloud as needed. Later a web app could be developed to also work on the same data source, but that's another item.


## Can ICalendar format work?

It can define most the objects that we want. We could hijack some fields for application specific content without much trouble. If this is done, then you can use your own calendar app to handle notifications and alarms, etc. At least at the beginning, then with time develop a built in calendar.

For scheduling ical has to work.



# Architecture

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

