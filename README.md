Booyah!
=======

The easy mode template parser in JavaScript.

Decide what you want your template tags to look like and replace them with the content you want. Super small no predefined syntax rules.

A quick example:

```js
yourCopy = booyah;

yourTemplate = yourCopy
  .addTemplate('<a href="{{ avatar }}">{{ name }}</a>')
  .addTag('{{ avatar }}', 'http://example.com/kevin.jpg')
  .addTag('{{ name }}', 'Kevin Dees')
  .ready();
    
console.log( yourTemplate );

```
