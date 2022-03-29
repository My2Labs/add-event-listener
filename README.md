# Add Event Listener

Using the browser console, attach an event listener of any type to [this page](http://www.republiquedesmangues.fr/). Be creative! Here is one example (click the mango after running this code):

const mango = document.querySelector('#mangue');
mango.addEventListener('click', function (event) {
  mango.style.animation = `spin`
  mango.style.background = `#ff004d`
  mango.style.animationDuration = '10000ms'
  mango.style.animationIterationCount = 'infinite'
  mango.style.animationTimingFunction = 'linear'
})
