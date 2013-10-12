# lasagna.html

This is a quick math worksheet generator I built for my friend and coworker Seth. His kids are home-schooled. He once mentioned that his daughter loves math worksheets and does math problems faster than he can write them. So a bit of coding and a few days later, here we are.

## About the Code

I tried to make the entire thing self-contained. It's mostly like that, except for a call to an externally-hosted jQuery and jQuery UI script. Beyond that, everything is in *lasagna.html*. Nothing in it is server-side; all the query strings are parsed and dealt-with in JavaScript.

## About the Generator

Problems drag and drop to where you want them. Settings panel doesn't print. By default, all problem types and all operators have an equal chance of showing up and base numbers don't go any lower than 2 or higher than 10. That means if you see a higher number, it's usually the result of acting on two lower numbers. *(e.g. 45 might show up if you're multiplying 4 by 9.)* You can change the minimum, maximum, and problem types and operators using the types displayed, or **all** as a shortcut.

		Problem types:
		basic, basic3, xvar, ifvar, story, frac, time, longdiv, deciper OR all
		Operation types:
		plus minus times div

## License

[Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-nc-sa/3.0/) for the code and my story problems. There's a story problem or two by Bri Luginbill in there too, under the same license.
