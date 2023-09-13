# Is-Prime
Javascript function to check whether a number is a prime.

A number is considered a prime when it is not divisible by any number besides 1 and itself.

# Usage
Add `is_prime.js` into your project folder.

In your `index.html`:

```html
<script src="is_prime.js"/>
```

In your javascript files, you can use the function like this:

```js
if (is_prime(42)) {
    ...
}
```

# Limitations

`is_prime` only works with non-negative integers up to 507461. We are looking into this issue.
