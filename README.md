# <SCRIPT Type='text/javascript'>
window.addEventListener("load", myInit, true);
function myInit(){
function removeunwanteddata()
{
   var td = document.getElementById("roottable1").style.whiteSpace = "nowrap";
   var string=td.myTrim();
   alert(string);
}
function myTrim()
{
 return value.replace(/^\s+|\s+$/g,"");
}
}
  
