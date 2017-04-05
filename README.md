# Accessibility - Make Websites for Everyone

Safari has good developer tools to check for accessibility.  

<img src="img/safari-accessibility.png" alt="Safari accessibility developer tools" height="400px" width="650px" />  

Additionally, VoiceOver (screen reader on a Mac) works really well with Safari to identify accessibility issues. The shortcut on a Mac to turn on VoiceOver is `command` + `F5`. To open the VoiceOver help menu press `control` + `option` + `H`. To open the VoiceOver rotor press `control` + `option` + `U`. The rotor provides a quick overview of the structure of the webpage and allows easy access to many elements on the page. You can adjust VoiceOver settings and rotor options within the VoiceOver Utility.  

VoiceOver Shortcut Resources:  
[Apple VoiceOver Commands & Gestures](https://www.apple.com/voiceover/info/guide/_1131.html)  
[WebAIM](http://webaim.org/articles/voiceover/)

<img src="img/voiceover-utility.png" alt="Safari accessibility developer tools" height="400px" width="550px" />

If using Windows you will use the NVDA screen reader. Click [here](https://dequeuniversity.com/screenreaders/nvda-keyboard-shortcuts) for NVDA shortcuts.

Important to use [WAI-ARIA](https://www.w3.org/TR/wai-aria-1.1/)   (Web Accessibility Initiative - Accessible Rich Internet Applications), a standard set of attributes that you can put in your HTML or SVGs to provide accessibility information in your applications.  

*Don't make up ARIA attributes since there's a standard set that screen readers are able to decipher*  

## How to ensure accessibility

* Use native semantic tags whenever possible
* Use ARIA roles - specifies what an element does
* Use ARIA labels - specifies a name for the element
* Make elements focusable with `tabindex="0"`
* Make elements not focusable with `tabindex="-1"` (pulls element out of tab order, but can add focus with JS)
* Make skip links for navigation  
* Test websites and applications with the keyboard

Always test accessibility with the keyboard. In Safari, turn on the ability to tab over every element.

<img src="img/tab-option.png" alt="Safari accessibility developer tools" height="400px" width="500px" />



## Add Accessibility Chrome Extenstions

[Accessibility Developer Tools](https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb?hl=en)  

<img src="img/accessibility-developer-tools.png" alt="Safari accessibility developer tools" height="400px" width="650px" />

[Accessibility Inspection](https://gist.github.com/marcysutton/0a42f815878c159517a55e6652e3b23a)

<img src="img/chrome-accessibility.png" alt="Chrome accessibility developer tools" height="600px" width="450px" />

[aXe](https://chrome.google.com/webstore/detail/axe/lhdoppojpmngadmnindnejefpokejbdd?hl=en-US)

<img src="img/axe.png" alt="Chrome accessibility developer tools" height="600px" width="450px" />

## Run Accessibility Audits

<img src="img/accessibility-audit.png" alt="Chrome accessibility developer tools" height="600px" width="450px" />
