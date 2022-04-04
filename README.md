# KrnlAutoBypassCode
Press f9 for DevTools (Chrome) and go on 'Console' and copy this.

//Use Inspect on all Websites.

with Reffer:
window.open("https://cdn.krnl.ca/getkey.php", "", "noreferrer=no");
setTimeout(function(){
    window.open("https://cdn.krnl.ca/getkey.php", "", "noreferrer=no");
}, 15000);
setTimeout(function(){
    window.open("https://cdn.krnl.ca/getkey.php", "", "noreferrer=no");
}, 30000);
setTimeout(function(){
    window.open("https://cdn.krnl.ca/getkey.php", "", "noreferrer=no");
}, 45000);
setTimeout(function(){
    window.open("https://cdn.krnl.ca/getkey.php", "", "noreferrer=no");
}, 60000)

With no Reffer: 
window.open("https://cdn.krnl.ca/getkey.php", "", "noreferrer=yes");
setTimeout(function(){
    window.open("https://cdn.krnl.ca/getkey.php", "", "noreferrer=yes");
}, 15000);
setTimeout(function(){
    window.open("https://cdn.krnl.ca/getkey.php", "", "noreferrer=yes");
}, 30000);
setTimeout(function(){
    window.open("https://cdn.krnl.ca/getkey.php", "", "noreferrer=yes");
}, 45000);
setTimeout(function(){
    window.open("https://cdn.krnl.ca/getkey.php", "", "noreferrer=yes");
}, 60000)
