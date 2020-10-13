# what is SMACSS ??
SMACSS ( Scalable and Modular Architecture for CSS ) is a css methodology that designed by Jonathan Snook in 2011.

According to style guide of SMACSS, the Css Architecture should not build on 1 stylesheet . It ought to has builded on 5 different categories. The goal of this process is creating flexible, consistent, reusable codes blocks, it prevents iteration of codes.

The categories are base, layout, module, state and theme .

base: It is used for html tags like html, body, a, a:hover. It also can included reset.css elements. Id and classes should not be used in this section.

```body, form {```
```margin: 0; padding: 0; }a { color: #039; }a:hover { color: #03F; ```
```}```

layout: It is used for divide css in sections like header, footer, sidebar. Id recommended for single usage, classes are recommended for multiple usage. “l-” or “layout-” prefix should be added for naming.

```#article { ```
```width: 80%; float: left; }#sidebar { width: 20%; float: right; ```
```} ```
```l-fixed #article { ```
```width: 600px; ```
```} ```
```l-fixed #sidebar {```
```width: 200px;```
```}```

module: It consist of reusable blocks which are smaller than layouts. Some of modules are form, menu, list, panel. It is not recommended to use Id, instead of it class should be used. In large projects element selectors not recommended too.

```.module {```
```padding: 10px ```
```}.module .title { ```
```color: red; ```
```}.module .description {```
```width: 200px;```
```}```

state : It includes styles of elements status. With state rules adjustments are made on how the pages will appear in different situations.The changes are mostly done by javascript. !important is allowed if needed. Some status are active, inactive, disable, hidden, expanded . It is reccomended to use “is-” prefix.

```.is-error{ ```
```border: 1px solid red;```
```}```
```.is-active{ ```
```border: 2px solid green;```
```}```

theme: It includes styles of the theme. The theme rules more applicable for larger websites . As small projects mostly has only one theme, it is not essential to use for them.

```/* in modules.css */.mod {  border: 1px solid;}/* in theme.css */ .mod {border-color: blue;}```

![](https://miro.medium.com/max/700/1*EqNOOn4VG-c6dvMIEZGTRA.png)


# what is Responsive web design

Responsive web design (RWD) is a website design approach that recommends building a single website that adapts to all devices and platforms. This avoids the duplication of effort involved in building separate desktop and mobile websites. A website built to RWD principles uses floating content elements, an adjustable page layout, and dynamically resized images to accommodate various viewport sizes and device capabilities. In other words, the site responds to the user's requirements.

The Magnolia Standard Templating Kit (STK) implements the RWD principles. A website built with the STK can deliver a browsing experience that works well on desktop browsers, smartphones, tablets and other types of clients. In this article we look at how the RWD technology is built into the system.

![](https://help.hcltechsw.com/commerce/7.0.0/com.ibm.commerce.aurora-starterstore.doc/images/locale/screensnap/smaurorarwdconceptscreen.png)
