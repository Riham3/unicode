# Riham Blogs' LaTeX to Unicode
**Try it out at:** [https://cigarettesprettysmokes.pages.dev/unicode/](https://cigarettesprettysmokes.pages.dev/unicode/)
 
## Overview
It's a lightweight, client-side web page that transforms LaTeX syntax and script notation into shareable Unicode characters. Designed primarily for writing mathematical or chemical notation in plain-text environments, where LaTeX or Markdown is not supported.
 
 
## LaTeX
It features 240+ LaTeX commands that can be inserted if you type a backslash (\\), which includes Greek, operators, relations, arrows, sets, calculus, and delimiters.
 
A backslash (\\), braces { }, caret (^), and underscore can be escaped with a leading backslash. Layout commands such as "\\frac" are not supported. Unknown LaTeX is preserved as-is.
 
 
## Script
Underscore is used for subscripts (e.g. "H_2O" becomes H₂O) whilst caret (^) is used for superscripts (e.g. "y^2" becomes y²). Braces group multi-character scripts. For example, "b^{20}" becomes b²⁰, whilst "b^20" only converts the first character, becoming b²0.
 
Superscript supports 0-9, A-Z, and a-z (although it doesn't support "q" in lowercase and 7 characters in uppercase).  Subscript supports 0-9 and a limited subset of lowercase letters. Uppercase subscripts do not exist in Unicode. Both forms also support plus (+), minus (-), equals (=), and parentheses "( )".
 
If a character can't be mapped to a script Unicode character, it is preserved as-is while the rest of the script converts normally (e.g. "y^{2%}" becomes y²%). 
 
 
## Usage
Click "Copy Result" to copy without selecting anything. Some emoji-prone Unicode characters are forced to render as text presentation. Report bugs or request features on Riham Blogs' [Submit Feedback](https://cigarettesprettysmokes.pages.dev/feedback/) page.

## Desktop Preview
<img width="2208" height="1192" alt="IMG_4673" src="https://github.com/user-attachments/assets/88d42245-ca79-476f-b515-9aa81bc959fe" />

## Mobile Preview
<img width="1242" height="2018" alt="IMG_4677" src="https://github.com/user-attachments/assets/79fb1e89-998c-45be-88c4-c59b41b4dd67" />
