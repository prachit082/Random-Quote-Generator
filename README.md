# ||Random-Quote-Generator||
Quote Generator in HTML, CSS &amp; Javascript

## Preview
[**CLICK HERE FOR LIVE DEMO**](https://prachit082.github.io/Random-Quote-Generator/)

###
 In this Random Quote Generator, as you can see in the preview, there is a quote that will be changed randomly, a button, and some icons.
 
 __Each time you click on the new quote button, you’ll get a new quote. You can also convert a quote to speech, copy a quote, or share a quote on Twitter by clicking the given button.__
<br>
To show random quotes, I used a free API named quotable **(https://quotable.io/random)**. You can use any other API for this project.
Let’s understand the main JavaScript codes and concepts behind creating this random quote generator. In the JavaScript codes,
<br><br>
***First:***  *I called a randomQuotes() function on the new quote button clicked. Inside this function, using the quotable API I fetched the random quotes and showed them on the Quote App.*
<br><br>
***Second:***  *For the **TTS (Text To Speech)** functionality, there is no external API is used and it’s possible with the Web Speech API of JavaScript.*
<br><br>
***Third:***   *To copy the quote, I used the **writeText()** property of the navigator object. For sharing to Twitter, I passed the quote text in the Tweet URL, and using the **window open()** method, I opened this URL in the new tab.*

### I hope you’ve liked this random quote generator and understood the basic codes of it. 

