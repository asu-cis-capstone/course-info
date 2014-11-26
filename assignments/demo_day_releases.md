
###Release 0.1 (due 9/4)

For the first release, you need to work out the kinks of using Git and GitHub, and develop a README file which represents what you've learned from the first meeting(s) with your client, and prepare a "demonstrate-able" scaffolding for your project.  The README file should contain at least three sections:

- Overview: a brief "elevator pitch" about what you're doing and why
- Team: a list of your names and github account names.  You can include clients, too.
- TO-DO: a to-do list or "product backlog" (see *The Elements of Scrum*, pp. 99-100); don't worry about how long it is, but try to get a sense of the client's priorities and make sure first things are first

You will give a demo in class on 9/4.  This can be a wireframe web site, PPTs or diagrams, or something else, but you need to be able to share your progress with your teammates and get their feedback and suggestions.  You'll have 4-5 minutes plus a bit of time for questions.

The files for your demo should be committed to the GitHub repository I will create for your team -- master branch.  If you can't get that done before class, I'll help.

Grading criteria: good demo (1) + visible progress (1) + README (1) + files (1) + can take questions (1)

###Release 0.2 (due 9/18)

By the second release, I'm looking for demonstrate-able software.  If its a website, you should be able to fire it up in a browser and click around the links.  If it's a mobile app you should be able to show it working on an actual device or an emulator.  

Non-software projects (like digital marketing or data analysis) can be creative in how they demo what they've done, but it should be communicated well enough that you could present it to the client and he'd understand what he was seeing.

This release should be committed as v0.2 to the master branch of your repo.  I will not look at other branches, so you should follow a branching workflow that keeps intermediate changes out of `master`.  If you have things that aren't code, but are necessary to replicate the project, those should be in the GitHub repo as well.  I'm specifically thinking about databases here.  You can't commit the database, but you can commit a text file containing the CREATE TABLE and INSERT statements to re-create the database.  Come ask me for help if you need it.

Grading criteria:  good demo (1) + visible progress (2) + TO-DO updates (2)

###Release 0.3 (due 10/2)

Demonstrate your project again, giving particular attention to progress that's been made since last time.  If the improvements are invisible (like database improvements on the back-end) then you can take some time to talk about those, too, but remember to tell us why those are important.  (IE what's the business value of doing that?)

Commit the release and tag it as v0.3.

From this point on, when I check the updated README file (due the following tuesday), I want you to also include a burndown chart.  This is a simple line chart showing the size of the remaining product backlog (either the # of items, or the total "size" in story points).  You should have at least one data point for each release (so, 3 data points at this time), or you could get really sophisticated and put a point on the chart for every change in the README.

Grading criteria:  good demo (1) + visible progress (2) + TO-DO updates (1) + burndown chart (1).

###Release 0.4 (due 10/16)

Give another demonstration focusing on progress since the prevous verson.  Commit the code and tag it v0.4.  Update the README file and burndown chart by the following tuesday night.

From this point onward, the project repo should include a folder called `tests` and there should be some documentation in the README file about 'how to test' or **'how to run the tests'**.  Tests may be automated scripts or may be written documentation of manual test procedures.  These may be "validation" tests, i.e. user tests or A/B tests that test whether the product serves the customer's needs, or "verification" tests that make sure the software is of good quality, doesn't have bugs, etc.  Whatever type of testing you do, you must document how to carry out the tests.

Grading criteria:  good demo (1) + visible progress (1) + tests (1) + TO-DO updates (1) + burndown chart (1).

###Release 0.5 (due 10/30)

Same as previous.

###Release 0.6 (due 11/13)

In this release, in addition to telling us how you are testing your product, you need to provide the *results* of those tests (and ideally, show that they are passing!).  If you are doing automated tests, you might look into a continuous integration method that runs your tests automatically every time you commit changes.  Either way, the results of your tests should be highly visible -- either in the README file, or in some other top-level file in your repo.

You are strongly encouraged to review your documentation and add to it.  You might create a project web page.  (Look into the GitHub Pages feature, in which every GitHub project can get a free web page hosted right in the repo.)  Or you might re-style the README, or even create a Wiki within GitHub.  These efforts are a big part of making your project "presentable" to the client and to others who will look at it, such as recruiters who are checking out your resume.

Grading criteria:  good demo (1) + visible progress (1) + tests *with results* (2) + README updates (1).

###Release 1.0 (due 12/2)

The "capstone project showcase" will occur on Dec. 2 in the MU.  You'll have a table and numerous guests (faculty, staff, students, and friends of the IS department, including recruiters) will be invited to see and hear about your work.  At this point you'll want to have a working demo of the product as well as a product website and a finalized README file.  You may want to prepare other things like documentation (e.g. user manual, or a product demo video).  Dress professionally or uniformly (company logo t-shirts anyone?) and be prepared to talk to strangers about your work.  You can make posters, handouts, or other materials if it will enhance your presentation.

Grading criteria:  good demonstration (4) + product in shippable form (2) + tests pass (1) + README updates (1)
