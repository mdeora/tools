# `harness.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/compiler/lint/rules/harness.test.ts --update-snapshots` to update.

## `a11y/useHeadingContent`

### `0`

```

 lint/a11y/useHeadingContent/reject/1/file.tsx:1 lint/a11y/useHeadingContent ━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Provide screen reader accessible content when using heading elements.

    <h1 />
    ^^^^^^

  ℹ All headings on a page should have content that is accessible to screen readers.


```

### `0: formatted`

```tsx
<h1 />;

```

### `1`

```

 lint/a11y/useHeadingContent/reject/2/file.tsx:1 lint/a11y/useHeadingContent ━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Provide screen reader accessible content when using heading elements.

    <h1><TextWrapper aria-hidden /></h1>
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ All headings on a page should have content that is accessible to screen readers.


```

### `1: formatted`

```tsx
<h1>
	<TextWrapper aria-hidden={true} />
</h1>;

```

### `2`

```

 lint/a11y/useHeadingContent/reject/3/file.tsx:1 lint/a11y/useHeadingContent ━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Provide screen reader accessible content when using heading elements.

    <h1><div aria-hidden /></h1>
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ All headings on a page should have content that is accessible to screen readers.


```

### `2: formatted`

```tsx
<h1>
	<div aria-hidden={true} />
</h1>;

```

### `3`

```

```

### `3: formatted`

```tsx
<h1>
	heading
</h1>;

```

### `4`

```

```

### `4: formatted`

```tsx
<h1>
	<TextWrapper />
</h1>;

```

### `5`

```

```

### `5: formatted`

```tsx
<h1 dangerouslySetInnerHTML={{__html: "heading"}} />;

```

### `6`

```

```

### `6: formatted`

```tsx
<h1>
	<div aria-hidden={true} />
	visible content
</h1>;

```

### `7`

```

 lint/a11y/useHeadingContent/reject/1/file.html:1 lint/a11y/useHeadingContent ━━━━━━━━━━━━━━━━━━━━━━

  ✖ Provide screen reader accessible content when using heading elements.

    <h1></h1>
    ^^^^^^^^

  ℹ All headings on a page should have content that is accessible to screen readers.


```

### `7: formatted`

```html
<h1>
</h1>

```

### `8`

```

```

### `8: formatted`

```html
<h1>
	heading
</h1>

```

### `9`

```

```

### `9: formatted`

```html
<h1>
	<div aria-hidden="true">
	</div>
	visible content
</h1>

```
