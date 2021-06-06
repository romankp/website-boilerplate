# website-boilerplate

> Just playing around with a basic website boilerplate so I don't have to repeatedly set up the same initial solution for simple home projects, when I want to poke around some vanilla JS and don't need to leverage a framework or bundler. The goal is to slowly bring in quality-of-life tooling without complicating initial setup.

The gruntwork here will be done via NPM commands, Babel (for any esoteric cross-browser compatibility issues that I may not know off the top of my head), and LESS (because I really love nested targeting).

The directory structure is pretty standard for SPAs and node apps. I think it makes sense to keep the index.html file in the dist directory, along with the other public output, since it doesn't need to be processed in any way in this instance.

## TO-DO

- ~~Implement babel~~
- ~~Basic index.html~~
- Implement LESS
- NPM command refinement

## Possible/Probable Future Additions

- Basic webserver
- PWA implementation
- Favicons?
