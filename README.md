# Challenge for Software Engineer
Thank you for your interest in LivingSocial. To help us get to know you better (technically) please spend a few hours going through this assignment.

We appreciate your time spent.

## Submission Instructions
1. Fork this project on github.
2. Complete the project as described below within your fork.
3. Push all of your changes to your fork on github and submit a pull request. 
4. Email your recruiter or send an email to [dev.challenges@livingsocial.com](dev.challenges@livingsocial.com). **Remember to include your github username so we know who you are!**

## Alternate Submission Instructions (if you don't want to publicize completing the challenge)
Instead of submitting a pull request just create a patch file with your solution and email it to the email address above.

# Project description
LivingSocial sends a lot of email and so we're very cautious of not getting onto any spam lists for major email carriers. Spam list companies try and trick us by signing up for our services with honeypot emails and seeing if we'll send email. Let's create an http api that is passed an email and returns if the email is a spammer email or not.

We program in Ruby, Scala and Clojure (in that order). We use Rails, Sinatra, Play!, Blueeyes as web frameworks. Please choose some combination of these to submit your application as it will be the most helpful.

	Input looks like:
	{"email": "dev.challenges@livingsocial.com"}
	{"email": "iamaspammer@example.org"}
	
	Output is:
	{"email": "dev.challenges@livingsocial.com", "score": "valid"}
	{"email": "iamaspammer@example.com", "score": "invalid"}
	
## Valid emails should...
1. Be a reasonable format (probably a regex here)
2. Be at least 10 characters
3. Have at least 6 distinct characters
4. Not have more than 3 blocks of 2 characters

## Other requirements
1. The webservice should enforce content-types for input and output.
2. Your application should be easy to set up and should run on either Linux or Mac OS X.
3. You should be able to configure the tolerances above.
4. Your application should have some tests.
5. Your application should be mostly your work. If you use a gem / jar to do everything you're not showing us very much.
6. Your application should have an idiomatic build process for your language.


## Evaluation
Evaluation of your submission will be based on the following criteria. Additionally, reviewers will attempt to assess your familiarity with standard libraries as well as with language idioms.

1. Did your application fulfill the basic requirements?
2. Did you document the method for setting up and running your application?
3. Did you follow the instructions for submission?