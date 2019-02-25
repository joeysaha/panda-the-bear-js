PART 1
EX:
const img = document.querySelector('.profile-image');
img.src = 'https://placebear.com/300/300';

1.
const img = document.querySelector('#left-image img');
img.src = 'https://placebear.com/299/299';

2.
const txt = document.querySelector('.bio-info-value');
txt.innerHTML = 'Joey';

3. document.querySelector('#employment h3').innerText = 'something else';

4. const bodyText = document.querySelectorAll('body section div p');
bodyText[1].setAttribute('style', 'color:blue');

5. const tot = document.querySelector('body');
tot.setAttribute('style', 'color: orange');
OR
const tot2 = document.querySelectorAll('.highlight');
for (let i = 0; i < tot2.length; i++) {
  tot2[i].setAttribute('style', 'color: blue');
}

6. const font1 = document.querySelector('h1');
font1.setAttribute('style', 'font-family: monospace');

7. const round1 = document.querySelector('.action-icon-bg');
round1.setAttribute('style', 'background-color: black');

8. const field = document.querySelector('#name');
field.setAttribute('placeholder', 'Identify Yourself');

9. const field2 = document.querySelector('#message');
field2.setAttribute('placeholder', 'State Your Business');

10. const field3 = document.querySelector('#name');
field3.setAttribute('value', 'your nemesis');

11. const field4 = document.querySelector('#email');
field4.setAttribute('value', 'koalathebear@gmail.com');

12. const field5 = document.querySelector('#submit');
field5.setAttribute('value', 'En garde!');

13. const field6 = document.querySelector('#submit');
field6.disabled = true;

14. const location1 = document.querySelectorAll('.bio-info-value');
location1[1].innerText = 'Undisclosed';
location1[2].innerText = 'Redacted';

PART 2
1. const time1 = document.querySelector('.bar-default');
time1[2].remove();

1. const pik = document.querySelector('#right-image img');
const portcont = document.querySelector('.portfolio-container');
portcont.appendChild(pik.cloneNode());

2. const pik = document.querySelector('#right-image img');
const portcont = document.querySelector('.portfolio-container');
for (let i = 0; i < 10; i++) {
  portcont.appendChild(pik.cloneNode());
}

3. const container1 = document.querySelector('.bio-info');
const container2 = document.createElement('li');
container2.classList.add('bio-info-item');
container2.innerHTML = '<span class="bio-info-title">Update</span>';
const container3 = document.createElement('span');
container3.classList.add('bio-info-value bio-info-phone');
container3.innerText = Dec 25, 2008;
container1.appendChild(container2);
container2.appendChild(container3);
