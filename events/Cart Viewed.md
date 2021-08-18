# Cart Viewed

### This event is part of the page load sequence, including virtual page loads in the case of single page apps, and must be pushed between the `Page Load Started` and `Page Load Completed` events.

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Cart Viewed",
    "cart": {
        "item": [
            {
                "productInfo": {
                    "productID": "<productID>"
                }
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|productID|string|Unique Identifier of a product or offering.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level above SKU for products with SKU variants. |155, 65588, 987764448|||||||

## Attached Notes

<ol>
<li>svgfdfgfdg</li>
<li>dfgdfgfdg</li>
<li>dfgdfgfdg</li>
</ol>
<p>&nbsp;</p>
<ol style="list-style-type: lower-alpha;">
<li>fvghjfgh</li>
<li>fghgfh</li>
<li>fghfghfg</li>
</ol>
<p>&nbsp;</p>
<ol style="list-style-type: lower-greek;">
<li>gfhjfgh</li>
<li>gjkghjghj</li>
<li>ghjkjghkhg</li>
</ol>
<p>&nbsp;</p>
<ol style="list-style-type: lower-roman;">
<li>sdfdsfsdf</li>
<li>sdfsdfsdf</li>
<li>sdfsdfsdf</li>
</ol>
<p>&nbsp;</p>
<ol style="list-style-type: upper-alpha;">
<li>sdfsdfsdf</li>
<li>sdfsdfsdf</li>
<li>sdfsdfsdf</li>
</ol>
<p>&nbsp;</p>
<ol style="list-style-type: upper-roman;">
<li>sdfsdfsdf</li>
<li>sdfsdfsdf</li>
<li>sdfsdfsdf</li>
</ol>
<p>&nbsp;</p>
<ul>
<li>sdfdsfdsf</li>
<li>sdfsdfsdf</li>
<li>sdfsdfsdf</li>
</ul>
<p>&nbsp;</p>
<ul style="list-style-type: circle;">
<li>asdfsadsa</li>
<li>asdsadasd</li>
<li>asdasdasd</li>
</ul>
<p>&nbsp;</p>
<ul style="list-style-type: square;">
<li>sadfdsf</li>
<li>sdfsdfsdf</li>
<li>sdfsdfsdf</li>
</ul>