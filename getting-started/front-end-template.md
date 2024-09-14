# Front End Template

### Edit Front End Template

There are two options for integrating HelpYouSponsor with your existing website. One is using an iframe that embeds the application right in a page on your website. For most organizations this method is sufficient but there are some drawbacks. For those that find the iframe does not meet their need we have provided a way to edit the templates used in the front end or public facing portion of the application.

To access the Front End Template editor you will need to click on the Account link in the left hand Administration menu. On the following page scroll to the bottom and click the Edit Template button.&#x20;

_NOTE:_ This should only be done by an experienced web developer who is proficient in CSS, Javascript or Jquery, and HTML.

In the Front End Template Editor you will find three boxes: one for adding custom CSS, one for adding custom Javascript/Jquery, and one for adding custom HTML. At the bottom of the page is a file uploader for uploading images you would like to use in the template. We recommend using the uploaded images and not linking to externally hosted images. Because the app is contained in a secure (https) environment if you link to images that are not hosted on a secure server there will be a notice to visitors that some of the content is not secure.

### CSS

The CSS entered here is placed after the default CSS files so you are able to override any of the default styles.

### Javascript / Jquery

Jquery 2.0.3 is included in the template. Please be careful with what you do here as you could impact the performance of the software.

### HTML

The HTML is added to the top of the page so you are able to create a header region. This is perfect for adding navigation and a logo or anything else you want. Specifically the HTML will be place after the opening body tag and before the div with the container class.

> _HelpYouSponsor does not provide support for anything entered in the Front End Template. If you require support it will be provided at our hourly rate of $75/hour. If you would like us to do the customization we can provide a quote. Please send your request to support@helpyousponsor.com_
