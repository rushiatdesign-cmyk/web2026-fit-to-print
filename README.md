# Newspaper track

1. Pick a real page from the [South Asia Open Archives](https://www.jstor.org/site/south-asia-open-archives/saoa/newspapers-34677887/?so=item_title_str_asc).
2. Replace the placeholder headlines, decks, and body text with the real thing.
3. Swap each `.photo` box for a processed image, cropped and resized for web.
4. Then bring your design to life. **Typography first, then layout, then the fancy stuff.** Get one section looking great before moving to the next.

## Column widths

Every column is a `.col`. Add one of these to change how much space it takes (a bigger number means more room). Each one essentially applies a different `flex: NUMBER` value to the targetted element.

- `.wide` (flex 5), `.mid` (flex 4), `.narrow` (flex 2)

## Structure

- `index.html`: example front-page markup (replace with your page)
- `style.css`: minimal flexbox styling, commented (make it yours)
- [`../css-properties.md`](../css-properties.md): CSS reference
