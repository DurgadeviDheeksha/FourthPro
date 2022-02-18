Integration Testing?
What is integration testing? The basics explained!
If you develop software, you surely aim to create a well-thought-out app logic and workable features to support it. 
Integration testing is an essential step on the way to releasing an app with thought-out logic and flawless performance.

The name suggests that during integration testing we examine the integration of different elements. 
What these elements are and why is it so important to verify their integrity – all in today’s post. 

What Is Integration Testing? 
Let’s start with a formal definition. Integration testing is a type of testing meant to check the combinations of different units, 
their interactions, the way subsystems unite into one common system, and code compliance with the requirements.

Related: Types of Software Testing – Everything You Need to Know to Test Your Software From Beginning to End

For example, when we check login and sign up features in an e-commerce app, we view them as separate units. 
If we check the ability to log in or sign up after a user adds items to their basket and wants to proceed to the checkout, 
we check the integration between these two functionalities. 

For integration testing, the team uses components that have already been tested as separate units. 
A QA team groups these units into sets and checks them in accordance with the test plan.

Integration testing is performed using the black box method. This method implies that a testing team interacts with 
an app and its units via the user interface – by clicking on buttons and links, scrolling, swiping, etc. They don’t need to know how code works or consider the backend part of the components.

integration-testing-modules-scheme
Differences Between Integration and Unit Testing
unit-testing-vs-integration-testing
Integration testing and unit testing are two levels of software testing, where a unit is the basic one 
and integration is the sequential one.

Unit testing implies checking the smallest functioning parts of code separately. Integration testing goes further:
 we look for errors that happen when units start interacting. The fact that units have successfully passed the tests 
at the previous stages doesn’t guarantee that they will work well together. 

Therefore, any problems arising when we assemble several smaller parts into a subsystem can be associated with the 
particularities of the interaction between these units. The earlier we notice something abnormal, the lower will be the cost of a mistake.

Unit testing is the initial stage of the QA process. It prepares the functionality to the following stage which is integration testing.
 Without passing the former and verifying that units perform correctly, we cannot proceed to the latter and start putting them together. 

Related: Importance of Unit Testing: How It Aids Development Projects

If integration testing is the first chapter of the story (or the pilot of a TV show), unit testing is a prequel. 
As a rule, software engineers run unit testing at the earlier stages of product development. 

To wrap it up, unit testing is the examination of the smallest functional parts of code.
 Integration testing is the examination of the smallest possible combinations of those parts. 

Why Do We Need Integration Testing? 
IT specialists are well aware of how unpredictable code can be, even if it seems perfectly written. Besides, there are dynamic projects, 
where pre-approved requirements can lose their relevance and change – that’s especially true for Agile projects.

Changing Requirements & Software Testing
The reasons for sudden changes in a project may be different. Sometimes requirements are poorly designed form the beginning, 
and software development reminds wandering in the dark. A team has to discover that something doesn’t match the project logic
 and adjust the features on the go. 

Other reasons for sudden changes are: 

unforeseen problems, including developers ignoring some of the initial requirements, design defect, and test case failures;
marketing aspect – the revision of marketing strategies, a new approach to competitive response, etc.;
missing stakeholders, who decide to leave a project without handing things over to a person who remains in charge, or stakeholders
 who are decision-makers but don’t enter into details;
very optimistic deadlines or budget that doesn’t match actual resources; 
some product development life cycles not addressed (here come the incomplete requirements and gaps in logic). 
Sometimes the reason for a change can be as simple as a productive brainstorming session. Sometimes a team suddenly finds 
a better idea on how to continue with the development and gets a green light. It happens because of new technologies emerging,
 new people joining the team, or just a sudden new perspective.

Changing Requirements Affect Product Features
Let’s say, the changes aren’t very serious – just one feature modified. But this feature consists of several units –
 units that haven’t been tested individually or as an interactive system. In such a fast-paced environment, 
developers risk missing something. A QA team is their backup ready to find the flaws. 

For example, we are testing an e-commerce app. Just before the release of a new build, a marketing department 
signs an agreement with a popular delivery platform that was frequently requested by users. This delivery method wasn’t
 mentioned in the initial requirements.

Developers can postpone changes for several weeks until the next sprint or implement the feature quickly, 
including it in the scope of tasks for the nearest sprint. So, the team needs to add one more option to delivery methods, 
tie several payment options for it, connect the platform’s API for order status tracking, etc. 

The process starts with small steps: checking whether a new option appears on the list of delivery methods. The team needs 
to run a unit test to make sure it does. Then, we need to verify users can proceed to the next step after choosing this 
type of delivery. That’s integration testing. 

Without either of them, we cannot be sure that this new feature works. Thus, there’s a chance that customers won’t be 
able to use a new delivery method a company has already started promoting. 

Benefits of Integration Testing
Integration testing allows dividing code into blocks that consist of several units and check the parts of software gradually
 before assembling them all into a complete system. It means that all the systems will be properly revised, regardless of when,
 how, and why they have been created. 

Verification of software integrity is essential since only functional and highly-performing builds should be allowed to
 proceed to the further stages of testing. Otherwise, finding bugs will become more difficult and take more time. 

If you need to outline the advantages of the integration testing in a nutshell, here they are:

Simultaneous testing of different modules is very convenient, practical, and cost-efficient.
Integration checks can take place at any stage of the SDLC. 
It is a lifesaver for a team involved in projects with constantly changing requirements or logic that is under review after
 development has started.
Unlike other types of tests, integration can cover any amount of program code in one sprint (thanks to the different 
approaches we’ll explain in the following section). 
Types of Integration Testing
When we speak about the types of integration testing, we usually mean different approaches to this level of software examination.
 There are five commonly used practices of effective integration testing. Let’s take a look at the basics, 
briefly outlining the pros and cons of each. 

integration-testing-types
Bottom-to-top testing
It starts at the lowest levels of software under test. QA engineers gradually move to the top of the hierarchy.
 We apply bottom-to-top testing when all units involved in the examination are ready. 

Pros:

Can be applied at the early stages, since the examination of the critical functionality starts with the low-level units. 
If a particular unit stops functioning, a team can fix an error right away.
Minimal identification and troubleshooting time is required.
Cons:

The checkup of all the modules takes quite a lot of time, for you cannot submit a product to release until it passes the entire
 testing process from the lowest to the highest units.
If the software consists of many small low-level units that are very difficult to implement, it may take longer to complete 
the testing process.
Top-to-bottom testing
This is the opposite approach. It starts with the top-level modules and moves down. If some units are not ready yet,
 we use stubs – units that act as a temporary replacement. They give the same output as the one you get in an actual product, 
so code becomes suitable for integration testing even with some elements still missing. 

Pros:

It is easy to detect malfunctions and errors in the system.
Important units are checked first, and only then we move to lower-order units.
Testing requires less time compared to other approaches.
Cons:

If core logic is embedded in the lower-level units, it cannot be tested in the first place until the examination of other units finishes. 
The use of stubs becomes mandatory on all subsequent projects.
Big bang testing
A QA engineer starts testing after all modules are assembled into a wholesome system or at least its major part.
 It means that integration testing starts when code writing is finished and the first version of a product is ready for the release. 

It can be time-saving since a team doesn’t pause the development to check every unit. However, test cases should be flawless.
 Otherwise, decomposing a massive amount of code into units will just become a mess. 

Pros:

Good for testing small systems. 
Allows finding errors very quickly, and thus saves a lot of time.
Cons:

It may be difficult to find the source of defects since all units form a wholesome system. 
If a system consists of numerous units, reviewing all the implemented features can take a lot of time. 
Hybrid/Sandwich testing
In this case, the logic of top-to-bottom and bottom-to-top approaches are integrated as much as possible. Thus, 
we get a hybrid model, where top units are tested separately, while low-level units are examined after 
the integration with upper-level units.

Pros:

Ideal for large long-lasting projects.
Cons:

The price of such testing is very high since units of different levels pass the check simultaneously. 
Incremental testing
One more approach suggests more frequent checkups. A QA team examines integrated units after a development team finishes
 writing code for every new feature. In other words, after adding a new unit to a system, we pass its complete check. 

Pros: 

Testers find defects early and in smaller assemblies, so they reduce the cost of a mistake. 
It is easy to find the cause of the defect thanks to a step-by-step examination. 
Cons: 

It can require creating stubs for tests and thus get time-consuming. 
If you are a tester, consider all the pros and cons to decide which approach suits your goals better. If you are a product owner, 
don’t worry about tech moments and let us decide on the approach. We can keep you updated about the details like this if it is
 helpful in any way. 

Challenges of Integration Testing
We’ve told a lot about how integration testing works and what advantages it brings. As usual, benefits come with some challenges. 
There are several factors that can make integration testing more complicated than you expect. Here are some examples of such situations: 

If too many people participate in code writing, and each has a different style, it makes it difficult to understand the logic of units. 
A combination of diverse factors (databases, platform, environment, etc.) can complicate the testing. 
Integrating two legacy systems is rarely seamless, as well as integrating a new system into the existing one. 
If a system meant for integration are developed by different teams, they can be incompatible.
Different approaches and testing combinations can make it difficult to choose the most efficient model.
How to Do Integration Testing?
There is a simple algorithm a QA team can apply to run integration tests. Here is what the sequence of our actions typically looks like: 

Write a test plan.
Create test cases and use cases.
Run tests after unit integration.
Detect errors.
Retest the functionality after bug fixing. 
Repeat the testing cycle until all bugs are fixed.
There are two criteria that allow a QA team to conduct effective testing. And by effective testing, we mean detection of all 
the defects and shortcomings. So, testers should: 

Understand product structure and be aware of how units interact.
Be familiar with project peculiarities to be able to write good test cases, analyze the results correctly, and choosing 
between manual and automated testing.
Integration Testing Example
Let’s say, you have a fitness app with personalized training and meal plans. We won’t go into details regarding functionality. 
The core features of a similar app are: 

signing up / logging in the system; 
viewing available workouts and meals; 
choosing a personalized plan; 
tracking the progress. 
At the initial stages of product testing, the team develops user registration and authorization logic. These are pages with forms for 
entering login and password or signing in via social media accounts. 

After passing verification successfully, a first-time user should be redirected to the page that requests entering certain 
personal parameters for customization. If the flow appears to be different, there is an error in the system. To find and fix this
 bug, we run integration tests. 

Integration Testing Tools
Jasmine – a tool that uses JavaScript frameworks, simple syntax, runs on all browsers and is perfect for testing JavaScript code. 
VectorCAST – simple and transparent technology used for testing important business systems. 
FitNesse – an open-source project that supports all major languages, highly adaptable, and doesn’t require an additional installation. 
These are only some of the widely used tools you can see on the majority of popular lists. There are also Rational Integration Tester,
 Protractor, Selenium, and many more programs that simplify integration testing and boost its efficiency. 

Related: Integration Testing Tools and Practices to Start Using Today

The choice of a tool depends on the programming language, payment options, project specifications, and tester’s preferences. 

Integration Testing Tips 
Always study software architecture and app design to prioritize the units and their combinations correctly. 
Always have a clear integration test strategy with test cases and test data outlined in it. The information should be easy to understand
 to all members of a QA team. 
Write test cases to cover all interface features. It should be a precise examination since the interface is the point of user interaction.
Don’t select test data on the go. Prepare the mock data before you proceed to actual tests.
Keep project documentation handy. Approach developers with questions regarding the functionality if something is not mentioned in the 
documents or is poorly described.
Make sure the development team has checked all the modules properly before handling software for you. 
Don’t neglect automation. It can be a real time-saver and deliver more accurate results. 
Bottom Line
Integration testing is the second step in the hierarchy of testing levels. Following unit testing, it introduces a more complicated 
task for a QA team: to examine how to separate units work together and whether they work at all. 

Integration testing allows detecting bugs at the early stages, thus reducing the cost of an error and accelerating product delivery. 
And if you decide to skip this part, you risk missing a critical bug that will deteriorate the user experience or make you reschedule 
the release date.
