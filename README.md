Fire the `wholesaleVariantChanged` function from the `custom-events.js` file
```document.addEventListener('product:variant-change', function (evt) {
  console.log('Product variant changed');
  console.log(evt.detail.variant);
  
  wholesaleVariantChanged(evt.detail.variant);
  
});
```

Add the `Wholesale Club.liquid` code in between the injected Wholesale Club code in the product template liquid file.
