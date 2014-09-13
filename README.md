Meteor snippets for Atom editor
=======================================

Basic snippets to make meteor development faster in Atom.  Isomorphic javascript for the win!  Now supporting Server, Client, Database, Mobile Devices, Testing, and Editor!  

---------------------------------------
#### Examples

**mtp**

```html
<template name="name">
  ...
</template>
```

**mea**

```handlebars
{{#each collection}}
  ...
{{/each}}
```

**mif**

```handlebars
{{#if statement}}
  ...
{{/if}}
```

**mife**

```handlebars
{{#if statement}}
  ...
{{else}}
  ...
{{/if}}
```

**mpub**

```javascript
Meteor.publish("name", function(argument){
  ...
});
```

**msub**

```javascript
Meteor.subscribe("name", argument);
```

**mren**

```javascript
Template.name.rendered = function(){
  ...
}
```

**mcre**

```javascript
Template.name.created = function(){
  ...
}
```

**mhel**

```javascript
Template.name.helpers({
  helper: function(){
    ...
  }
});
```

**mevn**

```javascript
Template.name.events({
  'event': function(e, t){
    ...
  }
});
```
