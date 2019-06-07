---
name: Bug report
about: Create a descriptive and helpful report to get an issue fixed quickly.
title: "[??] Descriptive Issue Title"
labels: ''
assignees: ''

---

Please keep issues to **bugs** and **feature requests** - if you're stuck on config or setting up or something simple, use the [Google Group](https://groups.google.com/forum/m/#!forum/Redis-db) or post on [Stack Overflow](https://stackoverflow.com/questions/tagged/redis) instead.

**TL;DR:**
Remember when writing an issue that you need to convince others to spend time working on the problem - try and explain why it is important, and make it as easy as possible for others to understand and reproduce the issue.

You'll see there are sadly many unclosed and un-addressed issues here. Often, this is because there isn't enough detail, and potential contributors aren't able to spend the large amount of time themselves to work out what your problem is.

When naming your issue, try and use a descriptive title (e.g. "Crash when you divide by infinity" not just "Crash") and if applicable, tag the particular type or system in square brackets like [Streams] or [Cluster]

**Describe the bug**
A clear and concise description of what the bug is.
Are you running Redis yourself, or using a hosted version (RedisLabs, AWS, etc.)?
What system are you running the server on?
What version of Redis? Cluster, replicas or single-instance?
How are you talking to Redis? What programming language, libraries, network?

**Steps to Reproduce**
Someone should be able to read this bit and end up with the same problem.
List the steps it takes to go from a brand-new, empty server to the problem you're seeing.
Give specific commands, example data etc.

**Expected Behaviour**
If it's not obvious, *why* is that happens when you follow the **reproduce** steps wrong? What should have happened?

**Logs**
If applicable, add the Redis server crash dump, or other logs here.

**Additional context**
Add any other context about the problem here.
If you're comfortable doing so, try to find parts of the source code that might be causing the issue.
