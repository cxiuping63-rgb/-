---
create_Time: <% tp.file.creation_date(YYYY-MM-DD) %>
---
tp.file
· < tp.file.title >
· < tp.file.creation_date()

tp.date
.< tp.date.now("YYYY-MM-DD")
.< tp.date.tomorrow("YYYY-MM-DD")
.< tp.date.yesterday("YYYY-MM-DD")

tp.system
·< tp.system.prompt(“请输入作者”)>
*< tp.system.suggester(["to-read", "reading", "done"], ["to-read", "reading",
"done"], true, 'status')>