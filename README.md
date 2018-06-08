# SimpleDemo
This is a demo repo to show integration of PHP and React

# Generating Build In React

Fisrt you need to generate the build for your react application if you are using `create-react-app` along with `yarn` you just
need to run:

`yarn build`

or if you are using `npm` then you can run


`npm run build`

which will create a forlder called `build` or `dist` by default 

Now as of this writing this the directory where javascript and css other media resides is called `static` which resides inside your build directory;

# Integrating it with PHP

Just create a simple `<div id="root">` inside your php script put the css file that is generated in `static` dir in the head section in  and make sure you put the javascript after `<div id="root">`

ofcourse you can you can have anything in php before or even the `div` though your overall page style might need change to accomodate what you integerated react.





