---
layout: leap_day_theme
title: Coderetreat 中国 - Let's commit together LCT vs code-review
---

## Intro

Code-review really [can make or break your team](https://medium.com/swlh/code-reviews-can-make-or-break-your-team-a3cfdcc15de1).
I have seen code reviews "in meeting room" that were printing 30-50 pages, sitting in a meeting room without computers, asking developer to comment written code page by page.
Yes it is useful, especially once in a big while with external adviser. The problems:

- it often runs longer than initially planned 1 hour
- it is hard to remember all comments and change appropriately. And almost infeasible to check that it was done.
- after a round nobody wants to repeat it again. So the practice just dies.

And then there's question of code quality. I believe in

- The only valid measurement of code quality: WTFs per minute

![](http://blog.codinghorror.com/content/images/uploads/2009/02/6a0120a85dcdae970b012877707a45970c-pi.png)

that saying politely is how much strange pieces the code have. ([ref2](http://blog.codinghorror.com/whos-your-coding-buddy/))

## Code review with GitHub PR

GitHub made great step forward with Pull Request. Yes, looking on the code before merging is actually code review.

It is awesome for distributed team, especially in different time zone, when you can't do a call and share screen.

But when sitting together in the same room do LCT

## Let's commit together 让我们一起提交

Before committing I am looking for a team mate to look at my code for 3-5 minutes. Anyone free to sit in front of PC.
Then by using IDE to show code changes, I go through them and explain what was the goal and why it is done this way.
If there's no question we commit.
If there are questions we add notes as comments and still commit.
If there are big problem we don't commit, but it never happens because we ask questions during the day when in doubt.

### How to review LCT

- stay within 3-5 minutes
- try to understand, ask questions if you don't know the task/story
- the goal is to have it committed, not to break
- ask to get control of mouse/keyboard, but see that the person stays in good mood about it
- add your comment as `//TODO` comments, then they are easy to find via IDE or static analysis tools like Sonar
- if you really feel like changing, then say so and ask to commit first (locally e.g. with `git` commit without `push`)
	and start changing until person gets understading to continue or to reject

## within Agile

LCT is done 1-2 time per developer, as everyone is advised to finish and commit at the end of day.
On the morning stand-up I will repeat what I did (I just practiced presenting yesterday) and who reviewed.

Good luck! 祝你好运！

<a href="https://cn.linkedin.com/pub/paul-verest/10/645/105">Paul Verest</a> 伟保罗

![](images/people/Paul_Verest_140x140.jpg)

[Edit this page / 编辑此页](https://github.com/coderetreat-china/coderetreat-china.github.io/edit/master/lets-commit-together-LCT-vs-code-review.md),
[website problem / 告知网站问题](https://github.com/coderetreat-china/coderetreat-china.github.io/issues)
