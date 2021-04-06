original behavior

```js
const foo = (
  <Foo>
    { cond && (
        <Bar />
    ) }
  </Foo>
);
```

this branch

``` js
const foo = (
  <Foo>
    { cond && (
      <Bar />
    ) }
  </Foo>
);
```

this behavior is compatible with eslint rule `jsx-indent`
