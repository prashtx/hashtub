hashtub
=======

Organize github repos by hashtag #github #javascript

Include hashtub.js in your page. Then use `hashtub.getTagTable`. For example:

```javascript
hashtub.getTagTable({user: prashtx}, function(result) {
  console.log(result);
});
```

```javascript
hashtub.getTagTable({org: codeforamerica}, function(result) {
  console.log(result);
});
```
