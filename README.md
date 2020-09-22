<div align="center">

## Basic Date & Time Script


</div>

### Description

This code only puts the current Date & Time on your website. IT's very simple, BUT I haven't found it anywhere else on this site, so I decided to put this script up for you!
 
### More Info
 
Basically nothing, just copy/paste.

That this script takes the current time from the IIS server the .asp file is on and prints it to your web-page. This measn the date&time isn't the same as your country as long as the server isn't in the same country as yours.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Daniel Larsson](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/daniel-larsson.md)
**Level**          |Beginner
**User Rating**    |4.6 (23 globes from 5 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__4-1.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/daniel-larsson-basic-date-time-script__4-6398/archive/master.zip)

### API Declarations

You can use this script free, no copyrights, since it's very very simpel.


### Source Code

```
<html>
<body>
<%
Dim DatumTid
DatumTid=Now
%>
The current date and time is: <%=DatumTid%>
</body>
</html>
```

