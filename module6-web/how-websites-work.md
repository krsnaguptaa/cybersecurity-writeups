# How Websites Work
Browser → Internet → Server → Internet → Browser

HTML = structure (tags, elements, attributes)
CSS = styling (colors, fonts, layout)
JS = interactive functionality
     loaded via <script> tags
     security risk = JS injection

SENSITIVE DATA EXPOSURE:
Source code viewable by anyone
Developers accidentally leave credentials in comments
First step pentesting = view page source
Look for: comments, hidden fields, credentials

HTML INJECTION:
Website doesn't sanitize user input
Attacker injects HTML/JS into input field
Browser renders it as real code
Fix = always sanitize user input
Golden rule = never trust user input
