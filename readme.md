this is a junk repo that will go away. just testing some junk.

basically index.html is a dumb shim with an embedded svg animation that on domready starts an rAF loop, waits 3 seconds, and then dynamically injects a script tag with a src set to a 1 mb js file. when that completes, it injects a link tag with an href to a 1mb css file. you can follow along with the console.log events but the animation completely halts once the js is loaded. thusly jank!
