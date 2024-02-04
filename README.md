HTML-Content-Identification
HTML Language Support
The lang attribute specifies the language of a webpage, typically set on the HTML element that wraps everything else. It's essential to set it once, like in a template file.

The lang attribute should be specific, indicating the language, such as "en-US" for U.S. English or "en-GB" for Great Britain, for better spell checkers and preference, rather than simply "lang=en".

he lang attribute specifies language, regional versions, and writing system used on webpages. It can be used on any element, like Mexican Spanish with Nahuatl block quotes, to indicate language and writing system.

The dir attribute indicates the content's direction, which can be applied to any element, and should be defined once on the outer HTML element for all content on the page.

Unicode, specifically UTF-8, is a widely used specification that encodes various characters, scripts, and emojis, covering languages, scripts, and communication forms like Braille and musical notation.
To specify the character set in HTML, include a meta charset tag equal to UTF-8 within the head element on every website page.

HTML Generic Elements, Div and Span
HTML elements like div and span are useful when an element doesn't exist, such as grouping or highlighting phrases or targeting specific parts of the DOM with CSS or Javascript, even if there's no real meaning behind it.

Using divs and spans for everything is not good practice and negatively affects users. Instead, use appropriate HTML elements for specific purposes. Generic elements like divs and spans are needed when block-level elements are needed, as they do not function until CSS or Javascript is applied.

Eg-A simple article with a headline and four paragraphs can be grouped using CSS to add a background color to the paragraphs. To target a specific phrase, use the inline element span. Both div and span can use global attributes like class, id, lang, and aria roles. They are useful last resort options when other options are unavailable.

