# Website Integration

### Website Integration

Integrating HelpYouSponsor with your Website.

> You will see notice that each individual program has a unique frontend URL that looks something like this:\
> https://app.helpyousponsor.com/frontend/view\_all/1/2\
> \
> You clearly don't want your donors to have to type in this URL to be able to donate, so you have two options:\
> \
> a. Use an Iframe in your existing web-page \
> An Iframe is essentially a website within another website. This is by far the simpler of the two options.\
> From your Admin login, If you go into your "Program Options" and click on your desired program, you will see a box that says, "Embed Code." From here, you can copy the Iframe embed code in the gray box and paste it into the code of your website wherever you like. This will put the frontend into an Iframe window within your existing web-page.\
> \
> b. [Edit the Front End Template](../product-tour/program-options/email-set-templates.md) and use this URL as a page within your website. To do this, you must customize the HTML, CSS and Javascript/JQuery in order for the HelpYouSponsor page to look like a normal part of your website. With the right programmer (you can't do this without a code guru) this option will allow you the most flexibility and make your sponsorship website look exactly as you want it to.

Iframe Scrolling Issue

> **The Problem:** When the donor clicks a button, they have to scroll back to the top of the page.
>
> **Why does this happen?** Because the HYS Iframe is a window within your website, the web browser doesn't realize that the page needs to be scrolled back to the top. Because of browser security constraints, we can't (from inside the iframe) tell your page to scroll to the top.
>
> **The Fix:** However, you can fix this very easily in the code on your website.&#x20;
>
> There are three ways you can remedy this:

*   **Scroll to Top of Page Easy**

    Scrolls to the top of the page every time the iframe changes.\
    Add this code to your iframe tag

```
onload="scroll(0,0);"
```

_This option is best if your iframe code is placed near the top of your page._

*   **Scroll to Specified Location Precise**

    Scrolls to the specified location every time the iframe changes. \
    First Determine the location you want the page to scroll to (we recommend just above the iframe.)\
    Then insert this code in that location&#x20;

```
onload="location.href='#Iframe'"
```

_This option is best if your iframe code is not near the top of your page._

*   **Don't use Iframe Coders Only**

    If you know what you are doing, you can directly link the frontend to your website and customize it so that the frontend sponsorship page looks just like another page on your website.

