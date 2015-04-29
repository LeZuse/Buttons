# Inline SVG example

The svg-builder directory in this project, contains a complete inline SVG build workflow. It requires you to have an understanding of things like Grunt and a bit of comfort with the command line. You may also want to do a bit of reading to get some background on inline SVG works. Here are some hand-picked posts to get you started:

- Icon Font vs. SVG – this is the one that convinced me it was time to try using inline SVG in a production system.
http://css-tricks.com/icon-fonts-vs-svg/

- Using SVG – just a great overview on SVG in use.
http://css-tricks.com/using-svg/

- SVG Use External Source – information on caching SVG by using an external defs file.
http://css-tricks.com/svg-use-external-source/

- Swapping Icons – some very practical tips on how to, well, swap icons.
http://css-tricks.com/swapping-svg-icons/

- All CSS-Tricks articles tagged "svg" – since Chris has become a bit of curator on the topic, this is useful too!
http://css-tricks.com/tag/svg/

Ok…ok, the tl;dr is to hit the terminal and type:

```
git clone -b svg-inline-experiments --single-branch https://github.com/LeZuse/inline-svg.git inline-svg && cd inline-svg && npm install && pushd svg-builder && npm install && grunt && popd && grunt dev
```

And then go ahead and have a look at the Gruntfile.js
