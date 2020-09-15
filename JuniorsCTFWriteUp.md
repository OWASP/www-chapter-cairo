---

layout: col-sidebar
title: OWASP Cairo
site_side: true
tags: egypt
order: 1
region: Africa
---

## Example 1 : Web Challenge

**Preferred reading**: https://en.wikipedia.org/wiki/HTML

**Link**: https://prejuniorsctf.azurewebsites.net/Web1/

**Description**: It's possible to see the source of a web page (the code the browser uses to render a page), developers shouldn't expose any private information in the HTML source code.

**Walkthrough**:
1. Visit the challenge page at `https://prejuniorsctf.azurewebsites.net/Web1/`.
2. Right click on the page and choose `View Page Source`.
3. You will see the flag as HTML comment.

## Example 2 : Crypto Challenge

**Link**: https://prejuniorsctf.azurewebsites.net/Crypto1/Reverser.txt

**Description**: Crypto usually changes a readable text into a form that can not be read by humans, in order to read the text you need to figure out how to transfer it back to the readable form.

**Walkthrough**:
1. Visit the challenge page at `https://prejuniorsctf.azurewebsites.net/Crypto1/Reverser.txt`.
2. Notice the last word is flag in reverse.
3. In order to find the flag you need to read the string backwards.

**Other Examples of Encoding**: rot13 and base64.
