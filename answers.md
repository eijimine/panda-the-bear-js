1.
var image = document.querySelector('body > aside > img');
undefined
image
<img src=​"images/​self-portrait-grassbg.jpg" alt=​"Self Portrait" title=​"Self Portrait" class=​"profile-image">​
image.src = "https://www.sitebuilderreport.com/assets/facebook-stock-up-446fff24fb11820517c520c4a5a4c032.jpg"
"https://www.sitebuilderreport.com/assets/facebook-stock-up-446fff24fb11820517c520c4a5a4c032.jpg"

1b.
var image2 = document.querySelector('#left-image > img');
undefined
image2
<img src=​"images/​clouds-man.jpg" alt=​"Man Walking on Ice" title=​"Man Walking on Ice">​
image2.src = 'https://images.pexels.com/photos/34164/pexels-photo.jpg?h=350&auto=compress&cs=tinysrgb'
"https://images.pexels.com/photos/34164/pexels-photo.jpg?h=350&auto=compress&cs=tinysrgb"

2.
var header1 = document.querySelector('h1.highlight');
undefined
header1
<h1 class=​"highlight">​Panda The Bear​</h1>​
header1.innerText = 'Eiji'
"Eiji"

3.
var header2 = document.querySelector('#employment > h3');
undefined
hearder2
VM1717:1 Uncaught ReferenceError: hearder2 is not defined
    at <anonymous>:1:1
(anonymous) @ VM1717:1
header2
<h3 class=​"info-title">​<i class=​"icon-suitcase">​…​</i>​" &nbsp; Employment"</h3>​
header2.innerText = 'Unemployment';
"Unemployment"

4.
body.style.background = "blue";
"blue"

5.
var high = document.querySelectorAll('.highlight');
undefined
for (var i = 0; i < high.length; i++) {
  high[i].style.backgroundColor="blue";
}
"blue"

6.

var font = document.querySelectorAll('h1');
undefined
for (var i = 0; i < font.length; i++) {
  font[i].style.fontFamily="monospace";
}
"monospace"

7.
var round = document.querySelectorAll('a.action-icon-bg');
undefined
round
(2) [a.action-icon-bg, a.action-icon-bg]
round.forEach(function(i) { i.style.backgroundColor = "purple" });
undefined

8.
var form = document.querySelector('input#name.contact-info');
undefined
form
<input type=​"text" name=​"name" class=​"contact-info" id=​"name" placeholder=​"Name">​
form.placeholder = "identify yourself";
"identify yourself"

9.
var form2 = document.querySelector('textarea#message');
undefined
form2
<textarea name=​"message" id=​"message" placeholder=​"Message">​</textarea>​
form2.placeholder = "state your business";
"state your business"

10.
form.value = "your nemesis";
"nemesis"

11.
var email = document.querySelector('input#email.contact-info');
undefined
email
<input type=​"email" name=​"email" class=​"contact-info" id=​"email" placeholder=​"Email">​
email.value = "koalathebear@gmail.com";
"koalathebear@gmail.com"

12.
var button = document.querySelector('input#submit');
undefined
button
<input type=​"submit" name=​"submit" id=​"submit" value=​"Submit">​
button.value = "En garde!";
"En garde!"

13.
var button = document.querySelector('input#submit');

button.disabled = true;
true

14.
for (var i = 0; i < info.length; i++) {
info[i].innerText = "";
}
