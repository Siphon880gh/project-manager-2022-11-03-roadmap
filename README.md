
## Note Rights: All rights reserved to UCB Haas and Project Manager Studio. This is not for public and is meant for study notes between classmates. 
## Note Please Contribute: Had not formatted the notes, so it's very crude. Feel free to contribute on this platform. Someone can format the notes or add more details. You can add comments to the lines.
## Note Experimental: I need to figure out a way to convert this to a more user friendly environment.  I don't have a formal process how we can share notes together, add comments, etc. Let's figure out the processes or any alternative platform. I've considered Google Doc but Obsidian allowed me to easily type notes as a note taker. and I would have to spend sometime combing through the text formatting. I had to export to Github due to time constraints which may not be the best solution for a study group.

# Product Roadmapping Study Notes (2022-11-03)
Customer-centric

![](https://i.imgur.com/fQmVEAe.png)
Old approach: Highest benefit, lowest cost, to make an impact
But the problem is you're disconnected from serving real human nees and goals. Alan Cooper (VS Basic) (And inventor of Persona)

![](https://i.imgur.com/QWLjctm.png)


Example: Segway. Originally wanted everyone using themselves. It ended up being security guards at malls, Disneyland, parking lots, etc

Example interview: If you've been given a segway for free, would you or would you not take it for work.
Doesnt look cool. How you park it? Can't carry things with it. Can't go on the freeway with it.

Segway: You're taller, cover long distances at slow speed. Not as clumy as bikes. Have a way to serve it (security guard are employees)

![](https://i.imgur.com/IoL8hxT.png)



![](https://i.imgur.com/e8dKhy4.jpg)

Color coding on the right helps explain how did they broke it down

Net Promoter Score surveys after App Store release under Web

There are markers that show deadlines for various events/tasks

Customer Conference before Q4 Release. Could be related to stocks too?

The goals aren't just technical, they include performance, user satisfaction, revenue, and  market

Each lane broken down by technology. The lanes usually imply there are different teams with resources in mind. The more parallel lanes, the more resources you have. Could be one PM that working on each lane (one PM overlooking mobile engineers, one PM overlooking web engineers, etc)

The shade uses how much percent is completed.

That is a roadmap. So this is like a gantt chart with progress tracking (progress and late statuses) and strategic goals (eg. User Satisfaction)? Darker shading is how much % done, and the dotted line / dot (?) if you're behind or ahead. Stategic goals like Mobile enabed, performance, user satsifaction are color coded in. So there's higher level strategies part of it too. Dependencies there too because App Store is right before Mobile payment options, both in red, so you see dependencies (App release then mobile payment options possible).

![](https://i.imgur.com/6DvEAGz.png)



But is not a gannt chart which doesn't have much but does add duration, start date, and tasks and subtasks

![](https://i.imgur.com/HtjuF7G.jpg)

Roadmap's audience (eg. Stakeholder/passionate customers, investors)
![](https://i.imgur.com/zHKfQr8.jpg)

Communicate at the right level / granularity for the right custmer
Timescale and task are minor decisions but dependent on the audience
Resource you might or might not have control over. As PM you might have control or you might have to ask for more resources

Roadmapping Tools: Vince Law every tool has a trade off between flexibility and efficiency (streamlined/convenient but less customization because you adhere to their philosophy which constraints your flexibility). Vince's personal preference is valuing flexibility over efficiency because planning in general is an attempt to predict the future which can change near term or long term so he builds most his maps on Google Sheet. He believes a lot of the tools are by PM's who got fed up with their companies' roadmapping but then don't realize their own philosophy is not adopted widely
^Biz idea: Notion of PM roadmapping tools.

Quarterly roadmaps up to a year better. Because multiyear usually more abstract and less tasks and follows just themes.

Prioritization techniques (in Roadmap)

You're gonna have to say No to a lot because you have constraints and have to allocate time/resources. One influence is what the CEO is feel most important. One job of PM is to be a good decision maker scrubbing away from subjectivity and make more bojective decisions

![](https://i.imgur.com/wzv4JHO.png)

![](https://i.imgur.com/wfzqBJd.png)

![](https://i.imgur.com/WO3cU8e.png)


Alignment and buy-in: Everyone agrees to how you make the decisions then they agree to the results. So you're convincing them of the process.

---


![](https://i.imgur.com/xTiwJFT.png)


You can ask your tech lead to also designate each feature so you have some ideas too. Tech might focus more on what's possible given the time constraints. Engineer might bring up techs that we need. Designer might talk about customer experience. PM may say viability and profitability. So ask everyone actually. A marketter may decide hailing a ride is the highest because they're marketting this as a driving app (Uber) (and marketing an easy to grasp concept that fills in a need that is easily empathized with)

![](https://i.imgur.com/RpP663k.png)

The framework is reuseable. If you ask other teams, you can have more alignment. But it might be subjective. But it might be ambiguous if multiple features are must, for exaxmple.

So while moscow is useful, you may want to use other frameworks

![](https://i.imgur.com/bnDmY1R.png)

Candy makes customer happy. Candy..etc is more about load balance.

Cost Benefit Matrix
![](https://i.imgur.com/8g2qXxO.png)

You'd multiply LoE or Cost to the Value/Benefit to get the Score. That's a  weight where Cost has magnifying effect. Your own columns you might add maybe by multiplying by higher or lower factor (for example 2xA + B, which is factor A is twice as important as B). Imagine even a "CEO wants" column that has a very heavy multiplication factor.

LoE ... level of effort
Maybe LOE can have decimals like 3.5 instead of 3, to not have duplicates and still be a metric. Or can have 1-10 instead of 1-5 which will have more granularity **and have more variability among the rows to help you make decision**. You can go even 1-100 but you lose some meaningfulness of it. This is called expansion. Fibonnaci sequence allows cumulative importance (odd method though) and allow more variability among rows.

ENhanced (you can always modify frameworks or combine them)
![](https://i.imgur.com/O35XKgo.png)

Force Rank is considering the Score column and the Moscow score to rank them, and is given intuitive numbers 1 to etc

You can add different columns like revenue, customer satisfaction, etc.

![](https://i.imgur.com/UkqUTpz.png)

Rice/Ice is from Intercom. Confidence is probablility effort will pay out or reealized. Is more sophisticated view into cost/benefit taking into consideration of confidence. Vince is not a personal fan because it has its place in certain decisions (medical devices or campaign processes that pose a risk would be appropriate) (if building a social media that fits and confidence is not a great factor because there's not much of a risk)

![](https://i.imgur.com/Wr2hJvz.png)

Teams with low hanging fruits will eventually run out of low hanging fruits and might go into distraction tasks. Then it's just focused on convincing stakeholders, "next sprint is 10 more features". Is not very strategic/viable to the business in the long run.

Low hanging fruits might not create a cohesive experience.

---

![](https://i.imgur.com/687V3Gf.png)

^When you acquire a planned some features and acquired a new tech and found out it can lead to more features, that's a valid way too. So we can prioritize by features or outcomes. And we can prioritize by tech enablement.

