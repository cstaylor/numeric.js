# numeric.js
Fork of texotela's numeric jquery plugin with a few tweaks

I've added three new features to the plugin:
- config option for allowing empty values
- config option for calling the blur function on each successful keyup event
- automatically converting the value into either an Integer or Double when sending it to the optional callback function

Simple example of using these three new features:
```$('#some_input').numeric ( { allowEmpty:true, live:true }, function ( val ) {
  console.log ( val );
});```
