# Helpful notes
## Meta
- The HTML <meta> element represents metadata that cannot be represented by other HTML meta-related elements, like <base>, <link>, <script>, <style> or <title>.
- If the name attribute is set, the meta element provides document-level metadata, applying to the whole page.
- If the http-equiv attribute is set, the meta element is a pragma directive, providing information equivalent to what can be given by a similarly-named HTTP header.
- If the charset attribute is set, the meta element is a charset declaration, giving the character encoding in which the document is encoded.
- If the itemprop attribute is set, the meta element provides user-defined metadata.
## meta name
- this meta data will be applied to the entire page. 
- viewport is used to control mobile browsers. Especially phones with narrow screens. This also lets you scroll and zoom in with fingertips. It will also shrink the pixels from original assigned based on the space the device. 
- The width property controls the size of the viewport. It can be set to a specific number of pixels like width=600 or to the special value device-width, which is the width of the screen in CSS pixels at a scale of 100%. There are corresponding height and device-height values, which may be useful for pages with elements that change size or position based on the viewport height.

The initial-scale property controls the zoom level when the page is first loaded. The maximum-scale, minimum-scale, and user-scalable properties control how users are allowed to zoom the page in or out.
```js
<meta name="viewport" content="width=device-width,initial-scale=1.0">
``` 
## meta charset
- This attribute is put in the head of a html document and declares the document's character encoding. For charset you will put in "utf-8" because this is the only valid coding in HTML5. Meta elements which declare a character encoding must be located within the first 1024 bytes of document. 