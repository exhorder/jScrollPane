# jScrollPane - cross browser custom scroll bars

jScrollPane is a [jQuery](http://www.jquery.com/) plugin which allows you to replace a browser's default scroll bars (on an element which has **overflow: auto**) with a HTML structure that can be easily skinned using CSS.

To see a bunch of examples of jScrollPane in action please visit the [jScrollPane website](http://jscrollpane.kelvinluck.com/). All of the code for the website is available from this repository so please feel free to download and use it!

## Issues

Please feel free to make Bug reports against project but if you are making Issue in this project please read below.

### Every Issue should have these

 - Brief topic which describes Issue
 - Short explanation about bug
 - Provide Browser info (version and platform) which have been used
 - Provide working example about Issue (JSFiddle or similar)

### It would be nice to have these

 - Debug help about Issue if needed
 - Issue owner stays active until Issue is closed

## Contributing

There is a simple [grunt](http://gruntjs.com) based build script which will help to produce a minified version of
jScrollPane if you make any modifications and want to submit a pull request. You can find it in the `build/` directory.

To use it, make sure you have [node](http://nodejs.org/), npm and the `grunt-cli` module installed first:

```
npm install -g grunt-cli
```

Then:

```
cd build
grunt
```

Please remember to update the changelog in the comment at the header of both JS files when submitting a pull request.

## Pull Request

These lines below may sound harsh or stop you making Pull Request. Please do Pull Request! This is very friendly project.
These are just here because my time is *very limited*. So If you read lines below we all get along with less stress.

Please feel free to make Bug reports against project but Before making Pull Request please run your code against newest JSHint.
*Code with errors against JSHint won't be integrated or reviewed!*.

Please also understand as Pull Request are made there is no time line or promise for that is would ever get integrated.
This Volunteer organization and I do this when I have time. Remember everyone can help to review Pull Request.

If there is changes needed to make in Pull Request it's up to Pull Request owner to make sure they are corrected.

### Pull Requests should at least have these
 - Pull Request should at least contain topic what it's changing
 - brief explanation why this should be integrated and what have been changed
 - if there is new initialize properties they they should be documented to documentation
 - if this Pull Request generates new functionality which ain't having example that should be provided.

## License

jScrollPane is dual-licensed under the [GPL 2 license](https://github.com/vitch/jScrollPane/blob/master/GPL-LICENSE.txt) and the [MIT license](https://github.com/vitch/jScrollPane/blob/master/MIT-LICENSE.txt).
