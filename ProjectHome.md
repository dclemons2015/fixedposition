# Introduction #
Position: Fixed, is a powerful CSS attribute, that allows you to fix a HTML element to a position on the page, irrespective of user interaction. Put simply, if the user scrolls, it stays put.

# What’s the Problem #

As web developers (now let's be honest), we face an interesting challenge when it comes to CSS and Internet Explorer. As an advocate for the users right to choose a platform, device and browser, we as web developers need to deliver a consistent user experience (no matter the browser)

Did you know that IE7 & 8 only support fixed positioning when using a strict doctype? Quirks Mode still remains IE8’s default, meaning we still need a graceful way of using this CSS gem.

# So what is FixedPosition? #

Through a blend of CSS and JavaScript, we can gracefully achieve this fixed functionality. FixedPosition is built off the jQuery JavaScript framework, which is already a trusted library.

  * It supports Internet Explorer 6, 7 & 8.
  * It integrates the IE "Speed Fix", to help ensure a fluent user experience
  * It check for browser capability, not user-agent
  * It supports Standard and Quirks mode
  * It Progressively Enhances your webpage

# Articles and Examples #
http://chrisiona.com/fixedposition/