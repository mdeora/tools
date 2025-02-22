# `harness.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/compiler/lint/rules/harness.test.ts --update-snapshots` to update.

## `js/preferOptionalChaining`

### `0`

```

 lint/js/preferOptionalChaining/reject/1/filename.ts:2 lint/js/preferOptionalChaining  FIXABLE  ━━━━

  ✖ Prefer optional chaining to manual checks.

    1 │ let foo = {};
  > 2 │ foo && foo.bar;
      │ ^^^^^^^^^^^^^^

  ℹ Safe fix

  - foo·&&·foo.bar
  + foo?.bar


```

### `0: formatted`

```ts
let foo = {};
foo?.bar;

```

### `1`

```

 lint/js/preferOptionalChaining/reject/2/filename.ts:2 lint/js/preferOptionalChaining  FIXABLE  ━━━━

  ✖ Prefer optional chaining to manual checks.

    1 │ let foo = {};
  > 2 │ foo !== undefined && foo.bar;
      │ ^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Safe fix

  - foo·!==·undefined·&&·foo.bar
  + foo?.bar


```

### `1: formatted`

```ts
let foo = {};
foo?.bar;

```

### `2`

```

 lint/js/preferOptionalChaining/reject/3/filename.ts:2 lint/js/preferOptionalChaining  FIXABLE  ━━━━

  ✖ Prefer optional chaining to manual checks.

    1 │ let foo = {};
  > 2 │ foo !== null && foo.bar;
      │ ^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Safe fix

  - foo·!==·null·&&·foo.bar
  + foo?.bar


```

### `2: formatted`

```ts
let foo = {};
foo?.bar;

```

### `3`

```

 lint/js/preferOptionalChaining/reject/4/filename.ts:2 lint/js/preferOptionalChaining  FIXABLE  ━━━━

  ✖ Prefer optional chaining to manual checks.

    1 │ let foo = {};
  > 2 │ foo != undefined && foo.bar;
      │ ^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Safe fix

  - foo·!=·undefined·&&·foo.bar
  + foo?.bar


```

### `3: formatted`

```ts
let foo = {};
foo?.bar;

```

### `4`

```

 lint/js/preferOptionalChaining/reject/5/filename.ts:3 lint/js/preferOptionalChaining  FIXABLE  ━━━━

  ✖ Prefer optional chaining to manual checks.

    1 │ let foo = {};
    2 │ // leading binary comment
  > 3 │ foo != null && foo.bar;
      │ ^^^^^^^^^^^^^^^^^^^^^^

  ℹ Safe fix

  - foo·!=·null·&&·foo.bar
  + foo?.bar


```

### `4: formatted`

```ts
let foo = {};
// leading binary comment
foo?.bar;

```

### `5`

```

 lint/js/preferOptionalChaining/reject/6/filename.ts:2 lint/js/preferOptionalChaining  FIXABLE  ━━━━

  ✖ Prefer optional chaining to manual checks.

    1 │ let foo = {};
  > 2 │ foo != null && foo.bar === "baz";
      │ ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Safe fix

  - foo·!=·null·&&·foo.bar·===·"baz"
  + foo?.bar·===·"baz"


```

### `5: formatted`

```ts
let foo = {};
foo?.bar === "baz";

```

### `6`

```

 lint/js/preferOptionalChaining/reject/7/filename.ts:2 lint/js/preferOptionalChaining  FIXABLE  ━━━━

  ✖ Prefer optional chaining to manual checks.

    1 │ let foo = {};
  > 2 │ undefined !== foo && foo.bar;
      │ ^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Safe fix

  - undefined·!==·foo·&&·foo.bar
  + foo?.bar


```

### `6: formatted`

```ts
let foo = {};
foo?.bar;

```

### `7`

```

 lint/js/preferOptionalChaining/reject/8/filename.ts:2 lint/js/preferOptionalChaining  FIXABLE  ━━━━

  ✖ Prefer optional chaining to manual checks.

    1 │ let foo = {};
  > 2 │ null !== foo && foo.bar;
      │ ^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Safe fix

  - null·!==·foo·&&·foo.bar
  + foo?.bar


```

### `7: formatted`

```ts
let foo = {};
foo?.bar;

```

### `8`

```

 lint/js/preferOptionalChaining/reject/9/filename.ts:2 lint/js/preferOptionalChaining  FIXABLE  ━━━━

  ✖ Prefer optional chaining to manual checks.

    1 │ let foo = {};
  > 2 │ undefined != foo && foo.bar;
      │ ^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Safe fix

  - undefined·!=·foo·&&·foo.bar
  + foo?.bar


```

### `8: formatted`

```ts
let foo = {};
foo?.bar;

```

### `9`

```

 lint/js/preferOptionalChaining/reject/10/filename.ts:2 lint/js/preferOptionalChaining  FIXABLE  ━━━

  ✖ Prefer optional chaining to manual checks.

    1 │ let foo = {};
  > 2 │ null != foo && foo.bar;
      │ ^^^^^^^^^^^^^^^^^^^^^^

  ℹ Safe fix

  - null·!=·foo·&&·foo.bar
  + foo?.bar


```

### `9: formatted`

```ts
let foo = {};
foo?.bar;

```

### `10`

```

 lint/js/preferOptionalChaining/reject/11/filename.ts:3 lint/js/preferOptionalChaining  FIXABLE  ━━━

  ✖ Prefer optional chaining to manual checks.

    1 │ let foo = {};
    2 │ // leading ternary comment
  > 3 │ foo ? foo.bar.baz : undefined
      │ ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Safe fix

  - foo·?·foo.bar.baz·:·undefined
  + foo?.bar.baz


```

### `10: formatted`

```ts
let foo = {};
// leading ternary comment
foo?.bar.baz;

```

### `11`

```

 lint/js/preferOptionalChaining/reject/12/filename.ts:3 lint/js/preferOptionalChaining  FIXABLE  ━━━

  ✖ Prefer optional chaining to manual checks.

    1 │ let foo = {}
    2 │ // leading binary comment
  > 3 │ foo && foo()
      │ ^^^^^^^^^^^^

  ℹ Safe fix

  - foo·&&·foo()
  + foo?.()


```

### `11: formatted`

```ts
let foo = {};
// leading binary comment
foo?.();

```

### `12`

```

 lint/js/preferOptionalChaining/reject/13/filename.ts:3 lint/js/preferOptionalChaining  FIXABLE  ━━━

  ✖ Prefer optional chaining to manual checks.

    1 │ let foo = {}
    2 │ // leading binary comment
  > 3 │ foo && foo.bar()
      │ ^^^^^^^^^^^^^^^^

  ℹ Safe fix

  - foo·&&·foo.bar()
  + foo?.bar()


```

### `12: formatted`

```ts
let foo = {};
// leading binary comment
foo?.bar();

```

### `13`

```

 lint/js/preferOptionalChaining/reject/14/filename.ts:3 lint/js/preferOptionalChaining  FIXABLE  ━━━

  ✖ Prefer optional chaining to manual checks.

    1 │ let foo = {}
    2 │ // leading ternary comment
  > 3 │ foo ? foo.bar() : undefined
      │ ^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Safe fix

  - foo·?·foo.bar()·:·undefined
  + foo?.bar()


```

### `13: formatted`

```ts
let foo = {};
// leading ternary comment
foo?.bar();

```

### `14`

```

 lint/js/preferOptionalChaining/reject/15/filename.ts:5:1 lint/js/preferOptionalChaining  FIXABLE  ━

  ✖ Prefer optional chaining to manual checks.

    3 │ if (
    4 │   // leading if condtion comment
  > 5 │   foo != undefined && foo.bar != null
      │   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
    6 │ ) {
    7 │   // leading call expression comment comment

  ℹ Safe fix

  - foo·!=·undefined·&&·foo.bar·!=·null
  + foo?.bar·!=·null


```

### `14: formatted`

```ts
let foo = {};
// leading if statement comment

// leading if condtion comment
// leading call expression comment comment
foo?.bar?.("baz")

```

### `15`

```

```

### `15: formatted`

```ts
let foo = {};
foo?.bar;

```

### `16`

```

```

### `16: formatted`

```ts
let foo = {};
let bar = "";
foo && bar.foo;

```

### `17`

```

```

### `17: formatted`

```ts
let foo = {};
let bar = "";
bar in foo && foo.bar;

```

### `18`

```

```

### `18: formatted`

```ts
let foo = {};
foo?.[bar];

```

### `19`

```

```

### `19: formatted`

```ts
let foo = {};
foo ? foo.bar.baz : null;

```

### `20`

```

```

### `20: formatted`

```ts
let foo = {};
foo ? foo.bar.baz : "anything else";

```
