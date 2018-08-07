# Extreme Programming: Overview

## Introduction

In software development, life cycles are processes defined and utilized to achieve a high quality product by providing structure and consistency.  Life cycles are considered an important aspect of software engineering because "process is king". In general, the steps in a software life cycle include: <sup>2</sup>

1. Feasibility; Development of a Business Plan
2. Requirements Analysis and Specification
3. Design
4. Implementation and Integration
5. Operation and Maintenance

Software life cycles fall into one of two categories: traditional or agile. Although traditional software life cycles, such as Waterfall, are still implemented in organizations, agile life cycles were developed with the aim of developing better software by improving upon the negative qualities of traditional cycles. Human communication and collaboration are the main focuses in which agile life cycles address the shortcomings of traditional life cycles. An agile life cycle that clearly illustrates these qualities is extreme programming. An overview of this method is detailed in this essay.

## History

In 1996, Kent Buck created extreme programming during his time as project lead on the Chrysler Comprehensive Compensation System that was for a payroll system in SmallTalk. There were two previous failures to this project, and they could not have a third failure. Kent discerned that: <sup>4</sup><br>

 > Software development fails to deliver, and fails to deliver value. This failure has huge economic and human impact. We need to find a new way to develop software.

This observation was Beck's driving force for refining software development methodology. He strongly believed that the failures of software development are corrected by taking standard programming practices to the "extreme". In his book,_Extreme Programming Explained_, he recalls his revelation. <sup>4</sup><br>

> When I first articulated XP, I had the mental image of knobs on a control board. Each knob was a practice that from experience I knew worked well. I would turn all the knobs up to 10 and see what happened. I was a little surprised to find that the whole package of practices was stable, predictable, and flexible.

To realize his vision, Kent proceeded to recruit a "dream team" of very experienced developers. First, the team demanded that an employee of Chrysler join the team so that any questions or concerns were answered to immediately. When the client provided requirements about functionality , user stories, the team minimized the amount of documentation by writing these on index cards so that there was not a lot to be written. This worked well, because the client was always there to clarify anything missing or unclear on the index card. Potential test cases that could be used were written on the back of the user story cards. Moreover, the team wrote and ran tests everyday, because if the software was developed first, then it was likely that no tests would be written afterwards. After success, the manners in which this team worked together defined Kent's methodology of extreme programming. <sup>3</sup><br>


## Executing Extreme Programming

 Fourteen simple practices characterize extreme programming, and are generally straightforward to implement. The following list describes each of these practices.

1. **The Planning Game** : Plan the time line of the next release by estimating all user stories in terms of points and determine what needs to be worked on according to priorities and point estimates. The plan is constantly updated to reflect unexpected or under/overestimated circumstances. Business and technical factors are considered in the estimates.

2. **Short Cycles**: Working software should be released every two weeks or less. When discussing what current tasks should be of focus, the amount of knowledge available for each task should take about two weeks. This is important, because if the cycle is longer (i.e. months), it likely that there is no scope for what needs to be done over the period.

3. **Metaphor**: Guide development and illustrate system with a shared story that functions as a common theme. The benefits of this practice are

4. **Simple Design**: System design should be as simple as possible, only consisting of the most basic thing that works for the given requirements,  and any unnecessary complexity is immediately removed.

5. **Acceptance Tests**: User stories are documented according to test cases that meet desired functionality.

6. **Refactoring**: The code for the system is constantly restructured to eliminate any repetitiveness, increase simplicity, and allow flexibility without altering any of the behavior. In other words, the "clutter" is removed from the design continuously.   

7. **Pair Programming**: Production code, which is the code used by the customers, is written by pairs of programmers working together. Each pair has one computer and one keyboard such that one person types while the other person monitors. The person monitoring is thinking about higher level design and watching for defects and errors, since the person typing cannot see these things easily.<br>

8. **Collective Ownership**: The system belongs to the team, and no developer is solely responsible for any module. Any pair can improve any module.

9. **Continuous Integration**: The system is integrated and built everyday each time a task is completed. Integration problems are addressed early and continuously through this practice.

10. **Sustainable Pace**: Supports a 40 hour work week so that the team remains fresh and because working overtime to meet goals indicates that the scope needs revision or there is another problem. This also supports the emphasis of simplicity in extreme programming.

11. **Customer Team Member**: A representative from the client is a member of the development team. This allows questions and ambiguities to be cleared quickly and

12. **User Stories**: The requirements about functionality written in brief statements from the client's point of view. This means that they are written with minimal technical terms and without high level computer science terms.

13. **Open Workplace**: The entire team works in close proximity such that pairs work near each other so that they can help each other and provide awareness of current state of affairs.

14. **Test-Driven Development**: The only production code written is to make failing test cases pass. The process entails first writing the test case, make sure it fails, and then write code that allows the test to pass. This practice is beneficial because bugs are caught early and test cases are produced that would not have been written if they were created after developing software.

## The Benefits

Although each agile method tends to have its own unique organization (such as arranging the work day and team), they all share the common goal of delivering value to the customer for the software system each iteration. Adopting the customer's perspective clearly indicates that working code is preferable to status reports. The benefits of practicing of extreme programming reflect this philosophy of agile methods.

In traditional life cycles, there was no estimation by the programmers and typically only the customer was involved in setting a time line. The customer would provide the desired software system's functionality and determine a scope based on their priorities, even if they did not have any knowledge or experience of what the process might require. In extreme programming, the planning game forces the team to plan early and choose tasks with their respective deadlines before starting to work on something. Even though unexpected circumstances mean that it's impossible to always be accurate in estimates, with time the team becomes more and more comfortable with estimating iterations and this builds confidence and trust with the customer.

Regular availability of the customer allows for questions, ambiguities, and changing requirements to be quickly and accurately communicated to the team. In most traditional life cycles, the customer is only able to do so every so often, and this leads to misinterpretations and mistakes that could have been easily fixed early on. Additionally, the availability of the customer gives rise to the nature of user stories in extreme programming. Less time is spent creating and maintaining documentation of requirements and tests because they are concisely written in the most simple terms. This also allows user stories to serve as reminders of conversations regarding functionality rather than long and complicated documentation that programmers would be forced to sift through.

Studies in the early 2000s determined that pair programming significantly reduced the project's defect rate and that team efficiency was hardly impacted. The defect rate was reduced because the person watching their partner type could simultaneously identify defects as they are introduced. Although many assumed that efficiency would decline because half as many people were producing software, but the study determined that the same efficiency was achieved and even that the bug rate was lower too.

Lastly, the use of metaphors is imperative for overall team morale. Metaphors provide common themes for the team to be creative and share jokes throughout the process with things such as module names or t-shirts. An example of the use of metaphor is how OS 10 manages packages with Homebrew. With this package utility, "casks" are installed, "brew taps" add packages outside of the master repo, and other things such as upgrades are "brewed". <sup>5</sup>


## The Basic Problem

Extreme programming aims to eliminate risk at all levels of the development process. A few examples of risk are schedule slips, system go sour (cost of making changes an/or high defect rate demands system replacement), business changes, and staff turnover. <sup>4</sup>

Because I haven't implemented anything remotely close to an agile life cycle in a few years, I have first hand experience that supports the reasoning and benefits of extreme programming. First of all, I have had countless schedule slips on account of a non-existent planning game and simple design hindered by excessive complex thinking. On the day of delivery for many of my customers, I had to tell the customer that their order wouldn't be ready, or even worse, ceased communication because I feared disappointing in face to face communication. Moreover, I struggled to maintain a sustainable pace in the way that one might prefer a 5K race over a marathon <sup>3</sup>. Instead of working in short cycles, my releases were inconsistent, and I gradually delivered less and less often over the years. Similarly, I resisted resistance pair programming and open workspace was not preferable. This resulted in numerous mistakes, complicated design, and blowing off other tasks as pressure increased. Additionally, I can't even remember the last time I refactored, so now I have 3 TB of external hard drive storage and three computers with clutter in multiple copies.<br>

Other consequences I have experienced from my lack of agile/extreme programming habits include decreasing performance to the point of consistent failure, deteriorating trust between my customers and I, noticeable social awkwardness in professional settings, and a really mediocre essay detailing differences between programming languages for a particular customer. The most substantial consequence was the staff turnover from my teammates' increased hatred for the program. In sum, the following figure should come up under a Google search for "Tanya Schulz".

![check online](https://github.com/tcschulz/Essays/blob/master/trainwreck.png "Depiction of agile planning's importance of iteration and change <sup>3</sup>")


## Sources

[1]: https://en.wikipedia.org/wiki/Extreme_programming#History <br>
[2]: Kenneth M. Anderson, "Software Life Cycles", 2016. <br>
[3]: Kenneth M. Anderson, "Introduction to Agile Methods", 2016. <br>
[4]: http://index-of.co.uk/Etc/Extreme%20Programming%20Explained.%20Embrace%20Chan.pdf <br>
[5]: https://wilsonmar.github.io/macos-homebrew/

### Author
Tanya Schulz
