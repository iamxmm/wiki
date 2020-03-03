if the github don't have china message verification, you could follow the follow code in console.

var option = new Option("China +86","+86");
option.selected = true;
document.getElementById('countrycode').options.add(option, 0);
