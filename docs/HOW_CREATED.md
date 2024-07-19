# How Was This Created?

1. It only took a few minutes!
2. You could easily duplicate this yourself, from scratch.

This was the prompt that I gave chatGPT4 to generate this code.

```
I would like help with the creation of a web page.

It would have all of it's content showing on the screen

CSS would all be in a separate `style.css` page

It is made of html elements, each with a different background color

The body is a flex container with 3 rows, top for header, middle for content and bottom for footer.

The top row contains a flex container inside it which has 5 menu elements, each a different color

The middle row contains a flex container with two equal columns of full width, each a different color, and no gap between the columns. The column on the right is itself a flex container, and has 7 rows, each of a different background color.

The bottom footer row contains a flex container which has 3 columns, each being a div of a different color with gap between each column.
```

You could use chatGPT or bard or ... and try this yourself!

The above prompt generated 2 files, placed here as

`/index.html`
`/css/style.css`
## Interesting Observations

If you ask generative AI to create this multiple times each may be different.

## Manual Steps 

I didn't use the exact code given to me by generative AI. But these are the only 2 changes that I made.

- moved `style.css` into `/css/style.css`
- formatted code
