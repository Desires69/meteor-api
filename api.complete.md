
---------------------------------------
#### Spacebar Snippets

**template**

```html
<template name="name">
  ...
</template>
```

**#each**

```handlebars
{{#each collection}}
  ...
{{/each}}
```

**#if**

```handlebars
{{#if statement}}
  ...
{{/if}}
```

**#ife**

```handlebars
{{#if statement}}
  ...
{{else}}
  ...
{{/if}}
```


---------------------------------------
#### Javascript Controller Snippets


**log**

```javascript
console.log("foo");
```



---------------------------------------
#### Core



**publish**

```javascript
Meteor.publish("name", function(argument){
  ...
});
```

**subscribe**

```javascript
Meteor.subscribe("name", argument);
```

**rendered**

```javascript
Template.name.rendered = function(){
  ...
}
```

**created**

```javascript
Template.name.created = function(){
  ...
}
```

**helpers**

```javascript
Template.name.helpers({
  rendered: function(){
    ...
  }
});
```

**events**

```javascript
Template.name.events({
  'click #foo': function(e, t){
    ...
  }
});
```

**Template**

```javascript
Router.map(function(){
  this.route("nameRoute", {
    path: "/route",
    template: "name",
    onBeforeAction: function () {
      setPageTitle("Some Page");
    }
  });
});
Template.name.helpers({
  rendered: function(){
    ...
  }
});
Template.name.events({
  'click #foo': function(e, t){
    ...
  }
});
```
