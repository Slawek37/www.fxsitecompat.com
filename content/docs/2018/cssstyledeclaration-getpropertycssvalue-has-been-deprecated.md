---
title: "`CSSStyleDeclaration.getPropertyCSSValue()` has been deprecated"
date: "2018-03-16T18:09:00-04:00"
categories: ["css", "dom"]
tags: []
versions: ["61"]
references:
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=474655"
      title: "Bug 474655 - warn when nsIDOMCSSStyleDeclaration::GetPropertyCSSValue is called"
---
The support for the [`getPropertyCSSValue`](https://developer.mozilla.org/en-US/docs/Web/API/CSSStyleDeclaration/getPropertyCSSValue) method on the `CSSStyleDeclaration` interface is now considered deprecated and will be removed in the near future. Firefox 61 and later will show a console warning for the method that has been [classified as obsolete](https://lists.w3.org/Archives/Public/www-style/2003Oct/0347.html) since 2003. Google Chrome has already [removed the support](https://groups.google.com/a/chromium.org/d/topic/blink-dev/3VmxWFzcyJc/discussion) back in 2014. Use the [`getPropertyValue`](https://developer.mozilla.org/en-US/docs/Web/API/CSSStyleDeclaration/getPropertyValue) method instead.