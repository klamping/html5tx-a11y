# Does HTML5 improve website accessibility or make it worse?
There's really no solid answer to this. In general, by providing native replacements for customized code, there is a more consistent and accessible interface used for common controls like <audio> and <video>. However, web developers have the responsibility to ensure their interface is accessible. HTML5 doesn't change this.

There's also the introduction of new elements like <canvas> which complicates accessibility greatly. It's extremly easy to create something in a <canvas> element that is inaccessible. That's not to say web developers shouldn't use these elements, just that they need to be careful with their use. Don't put mission critical information in a <canvas> element simply becaue it looks good.

In my honest opinion, I think HTML5 is good for accessibility. Any sort of maturation of the language helps standardize common practices so that assistive technology can take advantage of them. While HTML5 does introduce new ways to be inaccessible, being inaccessible has always been an option. Some new HTML5 elements probably won't make developers any more inclined to be inaccessible.

# How have screen readers adapted to the new technologies?
Support for technology like ARIA and HTML5 is growing. It's now mostly okay to expect support for ARIA role attributes. There's still lots of support for HTML5 to be added (for both assistive technology and browsers), but there is progress being made. For more information on browser support, check out the "Support Information" section in [Resources.md](./Resources.md).

# Does HTML5 remove the need for WAI-ARIA or the need for accessibility testing all together?
Not at all. Always test your app. Always provide a fallback. In theory, at some point in the future, HTML5 elements can be used alone without need for ARIA redundancy. That being said, HTML5 is not a 1:1 match for ARIA, so there are ARIA roles/attributes that don't have an HTML5 equivelant. I believe ARIA will be sticking around for a good while, as it provides not only a good fallback, but a fertile testing ground for trying out new behaviors to then merge into the official HTML spec.