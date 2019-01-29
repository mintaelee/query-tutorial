# query-tutorial

Today, we're going to make a responsive website that uses media queries. For the content, let's make it plain: a grid of 20 boxes of ALTERNATING colors. It could be red and then green and then red and then green, or whatever colors you choose. But let's not go crazier with the content than that!

Here are the different column layouts we want:

When the screen is less than 400px, make one column of 20.

When the screen is between 400px and 500px, make two columns of 10.

When the screen is between 500px and 700px, make 4 columns of 4.

When the screen is between 700px and 900px, make 10 columns of 2.

When the screen is greater than 900px, make 20 columns of 1.

### Hints:

1. Look for different flexbox attributes. One useful one rhymes with Tex Mesas!
2. You can think in terms of rows rather than columns, if that helps. Or both?


### Stretch Goals:

1. Use both a minimum and a maximum width for each rule.
2. Adust the behavior in some way for portrait vs landscape mode.
3. Use an entirely different thing to query for besides width and orientation! Do something fun with it!