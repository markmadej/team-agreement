# team-agreement
Wow.  I never thought I would want to do project management as a hobby.  But here we are.

## WTF is this?
I've reached the point where:
1. I feel that, in theory, I could build an app (or any project) from scratch and do all of the work myself.
1. I know in reality that if I want to build anything of serious complexity, I'll need to rely on others to help.
1. I know that even very small teams work much better with a clear, understood, and evolvable set of rules.
1. I have been on a team that tried to create a team agreement and failed due to bad attitudes, and that was frustrating.  We can do better.  
1. I know that I will gain value from this even as a 1 person team.  

This repo contains a set of rules that the team finds important enough to discuss and adhere to.  This will include guidelines on process (how issues are created, what steps they flow through, etc).  There may be some technology-specific things, there will be more general things.  Whatever the team finds to be relevant and important will be included within this repo.  Anything defined in this repo should welcome a challenge or question from a team member, and anything can be changed via PR.  

## High-level repo facts
1. Members of my team are expected to:
    * Familiarize theirselves with this documentation
    * Propose new ideas and improvements when they :lightbulb:
    * Adhere to the rules defined within this repo
1. You are a respected member of this team, if you'd like to participate.  Let's make this the best team we possibly can.
1. This team agreement is intended to be used across any / all repos that I am collaborating with others on.  Creating a standard process will make it smoother to contribute across multiple projects.
1.  This format looks like trash now.  Feel free to improve it, or I'll get to it at some point.  :) 

## Slack
We have our own Slack team for communication purposes.
* [Link to our team in Slack](https://app.slack.com/client/TPKCZLC5D/CPHH6M0F2)
* [Link to join the team](https://join.slack.com/t/teamsuperalph-5me1488/shared_invite/enQtNzk5MTIwNjczMzQ4LWI2MDc1Y2QyYjFlZTBjNzdmODYyNTkzYzk3ZTNlODg3ODNlNTg3ZmVjZmQyNDU3MWY2MTQ3Y2IzMDg3ZGQyMGU) - will expire on November 16th 2019, need to generate a new link after that or manually invite people via Slack.

## 2 Fast 2 Furious
With a single or very small number of engineers working in these repos, we should strive to make the process as friction-free as possible.  There may be steps we can take out of the process that provide good value with minimum risk (especially for systems that are not in production yet, etc).  This comes with the caveat that when, inevitably, someone fucks it up for everyone, then we can't have nice things anymore and this section will need to be be amended.

This section contains the 2 Fast 2 Furious set of rules intended to help us move as fast as possible.

WARNING : In most cases (or all cases if you prefer), it's better to just follow the standard process.  These rules are not recommendations.  They're giving you the ability to skip some redundant steps when it's clear that they don't add value.
1. Fuck applying labels (see next section) if you're working on something that you:
    * Are confident you will complete during your current work session
    * Don't think they will add value (but it should be very obvious that it won't or we'll have to change this)
1. Go ahead and commit directly to master for non-controversial documentation changes.  
    * Howevever, please add a short commit note that you specifically thought about this and didn't think it was necessary.
1. Go ahead and commit directly to master for non-controversial and fully-functional code changes.
    * This will be one of the first rules we probably need to change.  But who knows, if we're all super responsible, then maybe not.
    * This situation would include:
        * You believe you are a smart enough engineer to make this decision, knowing that this privilege will be taken away as soon as someone fucks it up.
        * This is not intended to be done as a standard everyday process, but I think it will be useful to get things moving fast.

## Github Issues, and labels to help track our progress
We will use Github Issues to track ideas and things we are working on.  It's free, it's integrated into Github, it's simple.  

### Labels
Just as we would in Jira during a normal sprint at work, we should apply labels (equivalent to Jira status) to each item.  This is a comprehensive list of each label, its purpose, and its color (a little extreme but it will be nice to have consistency across repos).

* ![#FF0000](https://placehold.it/15/ff0000/000000?text=+) `#FF0000` **Blocked** : This issue is blocked for some reason (see comments).  
* ![#E0E0E0](https://placehold.it/15/e0e0e0/000000?text=+) `#E0E0E0` **Needs Grooming** : This issue requires more grooming before work can begin.  
* ![#3333FF](https://placehold.it/15/3333ff/000000?text=+) `#3333FF` **Ready For Dev** : This issue has well-defined AC and is ready for dev work. 
* ![#00FF00](https://placehold.it/15/00ff00/000000?text=+) `#00FF00` **In Progress** : This issue is actively being worked on.  
* ![#FF9933](https://placehold.it/15/ff9933/000000?text=+) `#FF9933` **Ready For Review** : This issue has a PR that is ready for review. 
* ![#000000](https://placehold.it/15/000000/000000?text=+) `#000000` **Closed** : This issue has been closed (see comment for resolution details).
 
### Markdown
[Markdown](https://www.markdownguide.org/basic-syntax/) should be our standard for documentation syntax across all repos (if possible). 
