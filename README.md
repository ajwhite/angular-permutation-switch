# angular-permutation-switch

An enhancement of the principles behind `ng-switch` and `ng-messages` to allow for more complex view dynamics based on changing permutations


## Example

```html
<div permutation-switch="{foo: true, bar: false}">
  <div permutation-switch-when="{foo: true, bar: false}">Foo is true, bar is false</div>
  <div permutation-switch-when="{foo: false, bar: true}">Foo is false, bar is true</div>
  <div permutation-switch-when="{foo: true, bar: true}">Foo is true, bar is true</div>
  <div permutation-switch-when="{foo: false, bar: false}">Foo is false, bar is false</div>
  <div permutation-switch-when="{foo: true}">Foo is true, doesn't matter what bar is</div>
  <div permutation-switch-when="{bar: false}">Bar is false, doesn't matter what foo is</div>
  ...
</div>
```
