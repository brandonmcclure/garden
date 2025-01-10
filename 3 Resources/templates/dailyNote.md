
# <% tp.file.title %>

<%* tR += "#" %>journal

<< [[<% tp.date.now("YYYY-MM-DD", -1, tp.file.title, "YYYY-MM-DD") %>]] | [[<% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>]]>>

## Tasks Planned Today

```tasks
(due before <% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>) OR (scheduled before <% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>)
not done
path does not include Reminders
group by priority
```
***
## Today's Reminders
```tasks
(due before <% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>) OR (scheduled before <% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>)
not done
path includes Reminders
```
***
## Tasks Completed Today
```tasks
done <% tp.date.now("YYYY-MM-DD", 0, tp.file.title, "YYYY-MM-DD") %>
hide due date
hide recurrence rule
hide done date
heading does not include Daily Routine
heading does not include Daily Review
```
***
## Daily list of stuff to do

- [ ] wake up, brush teeth and wash face
- [ ] sleep

***

## Stream of notes
