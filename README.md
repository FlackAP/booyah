Booyah!
=======

The easy mode template parser in JavaScript.

Decide what you want your tamplate tags to look like and replace them with the content you want. Super small no predefined syntax rules.

A quick example:

```js
yourTemplate = booyah
  .addTemplate('<a href="{{ avatar }}">{{ name }}</a>')
  .addTag('{{ avatar }}', 'http://example.com/kevin.jpg')
  .addTag('{{ name }}', 'Kevin Dees')
  .ready();
    
console.log( yourTemplate );

```
