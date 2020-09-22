<div align="center">

## Browser window vibrator or Screen shaker


</div>

### Description

This code will shake or vibrate the browser window.

To see an example of what this code can do! go to

http://www.imagineer-web.com/MasterKey/vibrate.htm
 
### More Info
 
To see an example of what this code can do! go to

http://www.imagineer-web.com/MasterKey/vibrate.htm

Make sure you add the call vibrate(x)in your

HTML body. For example onload = "vibrate(10)"


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ayman Elbanhawy](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ayman-elbanhawy.md)
**Level**          |Beginner
**User Rating**    |4.9 (54 globes from 11 users)
**Compatibility**  |Java \(JDK 1\.1\), Java \(JDK 1\.2\)
**Category**       |[\.JS files](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/js-files__2-77.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ayman-elbanhawy-browser-window-vibrator-or-screen-shaker__2-2077/archive/master.zip)

### API Declarations

```
<body onLoad="vibrate(10)">
<!-- To see an example of what this code can do! go to
http://www.imagineer-web.com/MasterKey/vibrate.htm
-->
```


### Source Code

```
<!-- The following script vibrate the screen upon loading page -->
<!-- To see an example of what this code can do! -->
<!-- http://www.imagineer-web.com/MasterKey/vibrate.htm -->
<SCRIPT LANGUAGE="JavaScript1.2">
<!-- Begin
function vibrate(x)
 {
 if (parent.moveBy) {
 for (a = 10; a > 0; a--) {
  for (b = x; b > 0; b--) {
  parent.moveBy(0,-a);
  parent.moveBy(-a,0);
  parent.moveBy(0,a);
  parent.moveBy(a,0);
  }
 }
 }
 }
// End of vibrate code -->
</script>
```

