# AMP [Accelerated Mobile Pages]

> AMP is an open source initiative that enables the creation of consistently fast, beautiful, and high-performing web experiences across devices and distribution platforms. The AMPHTML library is a set of components, backed by carefully curated JavaScript, that enables functionality beyond HTML, with a focus on performance and security.

> AMP for email is another way for marketers to leverage the speed of the accelerated mobile pages framework.
it a powerful way for developers to create more engaging, interactive, and actionable email experiences.

> AMP in their email messages to support a whole host of new features. Emails written with AMP can contain interactive elements, like image carousels or accordions, content stays up-to-date in the message, and the ability for recipients to take action like responding to a form all without leaving their inbox.

> AMP for Email is compatible with existing emails. The AMP version of the message is embedded into the email as a new MIME part, in addition to the HTML and plaintext, ensuring compatibility across all mail clients.


# What We can Use In AMP Emails-

  - Dynamic content
    - amp-form: This is AMP’s form element. It allows designers to create forms directly in email that can be completed by users.
    - amp-selector: This is multi-select widget for use within a form.
    - amp-bind and amp-state: Simple scripting language in AMP that allows the manipulation of a state machine for interactions between elements. Can also be used to add behavior on certain events. amp-state is used to remotely fetch the initial state machine values.
    - amp-list: Remotely fetches JSON data that will be rendered by an .
    - template type=”amp-mustache”: A Mustache template markup to render the results of an amp-list call.


- Layout
    - amp-accordion: A UI element that facilitates showing/hiding different sections.
    - amp-carousel: A carousel UI component.
    - amp-sidebar: A sidebar for navigational purposes.
    - amp-image-lightbox: A lightbox for containing images.
    - amp-lightbox: A lightbox for containing content.
    - amp-fit-text: A helper component for fitting text within a certain area.
    - amp-timeago: Provides a convenient way of rendering timestamps.

- Media
    - amp-img: An AMP component that replaces “image”.
    - amp-anim: Embeds GIF files.
  
### AMP email boilerplate
The AMP for Email team has created a playground where you can develop, test, and send yourself AMP Emails. 
It contains all the required markup and the minimum code to be a valid AMP email.

* AMP emails must identify themselves as such by including ⚡4email, or amp4email, in the html tag.
* The <head> tag must also contain a <script> tag that loads the AMP runtime. <script async src="https://cdn.ampproject.org/v0.js"></script>
* A CSS boilerplate to initially hide the content until AMP is loaded. <style amp4email-boilerplate>body{visibility:hidden}</style>

### Image

- <img> ------>  <amp-img>
    ```
    <body>
      <amp-img src="https://placekitten.com/800/400"
               alt="Welcome"
               width="800"
               height="400">
      </amp-img>
    </body>
    ```
- For GIF Images ----> <amp-anim> URLs must use absolute paths in AMP emails and must be HTTPS.





### Plugins

Dillinger is currently extended with the following plugins. Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| Github | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |



**Free Software, Hell Yeah!**
 [![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

