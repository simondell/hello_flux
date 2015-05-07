To wrap my head around Flux (and practice some ES6), I'm creating a very basic Flux application.

Rather than use Facebook's own dispatcher, I've tried to understand the essence of the architecture and created my own, even more naive implementation. It *doesn't* have `waitFor`, and *doesn't* use promises.

I started with a pair of React views/components which draw a series of boxes and highlighted one at a time, in order, in reponse to a "ticker". These are re-used in the example, but I've now lost the final "working" state of that code. Sorry. The basic Flux app should now allow starting and stopping the sequence. If I get bold and have time, I'll update it to allow changing the order.

The motivation for learning Flux this way was that the Facebook documentation uses a load of extra cruft that hides some of the essence of the architecture. Browserify is great, the coding patterns they've used are exciting and their overall approach is sound, but I felt it got in the way of learning the core ideas. I wanted to see if I had understood it properly.