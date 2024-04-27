## This file consists of the HTML content that I've learned:

- Doctype: The doctype’s purpose is to tell the browser what version of HTML it should use to render the document.
  - Current version is: `HTML 5` and it is written as: `<!DOCTYPE html>`.
  - For `HTML 4`: `<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
`

- Elements:
  - html `<html>`: This is what’s known as the root element of the document, meaning that every other element in the document will be a descendant of it.
  - head `<head>`: This is where we keep important metadata of the document.
    - This is only used for containing data that renders our page correctly.
    - This should not be used to display content to the user, (Except the `title` of the webpage).
    - Elements:
      - `<meta>`: includes metadata, more importantly, the <b>charset encoding</b>.
        - This tells the browser engine to process the type of encoding specified here. Most used is: `utf-8`.
      - `<title>`: this element gives a human-readable title to the webpage.
        - Also useful for `SEO`.
  - 


- Attributes:
  - `lang`: specifies the language of the text content in that element. This attribute is primarily used for improving accessibility of the webpage.
    - It allows assistive technologies, for example screen readers, to adapt according to the language and invoke correct pronunciation.