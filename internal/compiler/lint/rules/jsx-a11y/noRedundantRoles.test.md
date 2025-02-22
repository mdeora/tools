# `harness.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/compiler/lint/rules/harness.test.ts --update-snapshots` to update.

## `jsx-a11y/noRedundantRoles`

### `0`

```

 lint/jsx-a11y/noRedundantRoles/reject/1/file.tsx:1:9 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━━

  ✖ Using the role attribute article on the article element is redundant.

    <article role='article'></article>
             ^^^^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <article·role="article">
      1 │ + <article>
    2 2 │   </article>

  ℹ


```

### `0: formatted`

```tsx
<article role="article" />;

```

### `1`

```

 lint/jsx-a11y/noRedundantRoles/reject/2/file.tsx:1:8 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━━

  ✖ Using the role attribute button on the button element is redundant.

    <button role='button'></button>
            ^^^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <button·role="button">
      1 │ + <button>
    2 2 │   </button>

  ℹ


```

### `1: formatted`

```tsx
<button role="button" />;

```

### `2`

```

 lint/jsx-a11y/noRedundantRoles/reject/3/file.tsx:1:4 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━━

  ✖ Using the role attribute heading on the h1 element is redundant.

    <h1 role='heading' aria-level='1'>title</h1>
        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  Suggested fix: Remove the role attribute and ARIA attributes.

    1   │ - <h1·role="heading"·aria-level="1">
      1 │ + <h1>
    2 2 │   → title
    3 3 │   </h1>

  ℹ


```

### `2: formatted`

```tsx
<h1 role="heading" aria-level="1">
	title
</h1>;

```

### `3`

```

 lint/jsx-a11y/noRedundantRoles/reject/4/file.tsx:1:4 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━━

  ✖ Using the role attribute heading on the h1 element is redundant.

  Suggested fix: Remove the role attribute.

    1   │ - <h1·role="heading">
      1 │ + <h1>
    2 2 │   → title
    3 3 │   </h1>

  ℹ


```

### `3: formatted`

```tsx
<h1 role="heading">
	title
</h1>;

```

### `4`

```

 lint/jsx-a11y/noRedundantRoles/reject/5/file.tsx:1:8 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━━

  ✖ Using the role attribute dialog on the dialog element is redundant.

    <dialog role='dialog'></dialog>
            ^^^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <dialog·role="dialog">
      1 │ + <dialog>
    2 2 │   </dialog>

  ℹ


```

### `4: formatted`

```tsx
<dialog role="dialog" />;

```

### `5`

```

 lint/jsx-a11y/noRedundantRoles/reject/6/file.tsx:1:24 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━

  ✖ Using the role attribute checkbox on the input element is redundant.

  Suggested fix: Remove the role attribute.

  - <input·type="checkbox"·role="checkbox"·/>
  + <input·type="checkbox"·/>

  ℹ


```

### `5: formatted`

```tsx
<input type="checkbox" role="checkbox" />;

```

### `6`

```

 lint/jsx-a11y/noRedundantRoles/reject/7/file.tsx:1:9 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━━

  ✖ Using the role attribute figure on the figure element is redundant.

    <figure  role='figure'></figure>
             ^^^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <figure·role="figure">
      1 │ + <figure>
    2 2 │   </figure>

  ℹ


```

### `6: formatted`

```tsx
<figure role="figure" />;

```

### `7`

```

 lint/jsx-a11y/noRedundantRoles/reject/8/file.tsx:1:7 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━━

  ✖ Using the role attribute form on the form element is redundant.

    <form  role='form'></form>
           ^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <form·role="form">
      1 │ + <form>
    2 2 │   </form>

  ℹ


```

### `7: formatted`

```tsx
<form role="form" />;

```

### `8`

```

 lint/jsx-a11y/noRedundantRoles/reject/9/file.tsx:1:8 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━━

  ✖ Using the role attribute grid on the table element is redundant.

    <table  role='grid'></table>
            ^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <table·role="grid">
      1 │ + <table>
    2 2 │   </table>

  ℹ


```

### `8: formatted`

```tsx
<table role="grid" />;

```

### `9`

```

 lint/jsx-a11y/noRedundantRoles/reject/10/file.tsx:1:5 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━

  ✖ Using the role attribute gridcell on the td element is redundant.

  Suggested fix: Remove the role attribute.

    1   │ - <td·role="gridcell">
      1 │ + <td>
    2 2 │   </td>

  ℹ


```

### `9: formatted`

```tsx
<td role="gridcell" />;

```

### `10`

```

 lint/jsx-a11y/noRedundantRoles/reject/11/file.tsx:1:11 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━

  ✖ Using the role attribute group on the fieldset element is redundant.

    <fieldset  role='group'></fieldset>
               ^^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <fieldset·role="group">
      1 │ + <fieldset>
    2 2 │   </fieldset>

  ℹ


```

### `10: formatted`

```tsx
<fieldset role="group" />;

```

### `11`

```

 lint/jsx-a11y/noRedundantRoles/reject/12/file.tsx:1:26 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━

  ✖ Using the role attribute img on the img element is redundant.

    <img src='foo' alt='bar'  role='img' />
                              ^^^^^^^^^^

  Suggested fix: Remove the role attribute.

  - <img·src="foo"·alt="bar"·role="img"·/>
  + <img·src="foo"·alt="bar"·/>

  ℹ


```

### `11: formatted`

```tsx
<img src="foo" alt="bar" role="img" />;

```

### `12`

```

 lint/jsx-a11y/noRedundantRoles/reject/13/file.tsx:1:3 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━

  ✖ Using the role attribute link on the a element is redundant.

  Suggested fix: Remove the role attribute.

    1   │ - <a·role="link">
      1 │ + <a>
    2 2 │   → something
    3 3 │   </a>

  ℹ


```

### `12: formatted`

```tsx
<a role="link">
	something
</a>;

```

### `13`

```

 lint/jsx-a11y/noRedundantRoles/reject/14/file.tsx:1:6 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━

  ✖ Using the role attribute link on the link element is redundant.

    <link role='link' />
          ^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

  - <link·role="link"·/>
  + <link·/>

  ℹ


```

### `13: formatted`

```tsx
<link role="link" />;

```

### `14`

```

 lint/jsx-a11y/noRedundantRoles/reject/15/file.tsx:1:4 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━

  ✖ Using the role attribute list on the ol element is redundant.

    <ol role='list' ></ol>
        ^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <ol·role="list">
      1 │ + <ol>
    2 2 │   </ol>

  ℹ


```

### `14: formatted`

```tsx
<ol role="list" />;

```

### `15`

```

 lint/jsx-a11y/noRedundantRoles/reject/16/file.tsx:1:4 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━

  ✖ Using the role attribute list on the ul element is redundant.

    <ul role='list' ></ul>
        ^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <ul·role="list">
      1 │ + <ul>
    2 2 │   </ul>

  ℹ


```

### `15: formatted`

```tsx
<ul role="list" />;

```

### `16`

```

 lint/jsx-a11y/noRedundantRoles/reject/17/file.tsx:1:8 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━

  ✖ Using the role attribute listbox on the select element is redundant.

    <select role='listbox' ></select>
            ^^^^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <select·role="listbox">
      1 │ + <select>
    2 2 │   </select>

  ℹ


```

### `16: formatted`

```tsx
<select role="listbox" />;

```

### `17`

```

 lint/jsx-a11y/noRedundantRoles/reject/18/file.tsx:1:4 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━

  ✖ Using the role attribute listitem on the li element is redundant.

    <li role='listitem' ></li>
        ^^^^^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <li·role="listitem">
      1 │ + <li>
    2 2 │   </li>

  ℹ


```

### `17: formatted`

```tsx
<li role="listitem" />;

```

### `18`

```

 lint/jsx-a11y/noRedundantRoles/reject/19/file.tsx:1:5 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━

  ✖ Using the role attribute navigation on the nav element is redundant.

    <nav role='navigation' ></nav>
         ^^^^^^^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <nav·role="navigation">
      1 │ + <nav>
    2 2 │   </nav>

  ℹ


```

### `18: formatted`

```tsx
<nav role="navigation" />;

```

### `19`

```

 lint/jsx-a11y/noRedundantRoles/reject/20/file.tsx:1:8 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━

  ✖ Using the role attribute option on the option element is redundant.

  Suggested fix: Remove the role attribute.

    1   │ - <option·role="option">
      1 │ + <option>
    2 2 │   </option>

  ℹ


```

### `19: formatted`

```tsx
<option role="option" />;

```

### `20`

```

 lint/jsx-a11y/noRedundantRoles/reject/21/file.tsx:1:4 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━

  ✖ Using the role attribute row on the tr element is redundant.

    <tr role='row' ></tr>
        ^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <tr·role="row">
      1 │ + <tr>
    2 2 │   </tr>

  ℹ


```

### `20: formatted`

```tsx
<tr role="row" />;

```

### `21`

```

 lint/jsx-a11y/noRedundantRoles/reject/22/file.tsx:1:7 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━

  ✖ Using the role attribute rowgroup on the tbody element is redundant.

    <tbody role='rowgroup' ></tbody>
           ^^^^^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <tbody·role="rowgroup">
      1 │ + <tbody>
    2 2 │   </tbody>

  ℹ


```

### `21: formatted`

```tsx
<tbody role="rowgroup" />;

```

### `22`

```

 lint/jsx-a11y/noRedundantRoles/reject/23/file.tsx:1:7 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━

  ✖ Using the role attribute rowgroup on the tfoot element is redundant.

    <tfoot role='rowgroup' ></tfoot>
           ^^^^^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <tfoot·role="rowgroup">
      1 │ + <tfoot>
    2 2 │   </tfoot>

  ℹ


```

### `22: formatted`

```tsx
<tfoot role="rowgroup" />;

```

### `23`

```

 lint/jsx-a11y/noRedundantRoles/reject/24/file.tsx:1:7 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━

  ✖ Using the role attribute rowgroup on the thead element is redundant.

    <thead role='rowgroup' ></thead>
           ^^^^^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <thead·role="rowgroup">
      1 │ + <thead>
    2 2 │   </thead>

  ℹ


```

### `23: formatted`

```tsx
<thead role="rowgroup" />;

```

### `24`

```

 lint/jsx-a11y/noRedundantRoles/reject/25/file.tsx:1:16 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━

  ✖ Using the role attribute rowheader on the th element is redundant.

    <th scope='row' role='rowheader' ></th>
                    ^^^^^^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <th·scope="row"·role="rowheader">
      1 │ + <th·scope="row">
    2 2 │   </th>

  ℹ


```

### `24: formatted`

```tsx
<th scope="row" role="rowheader" />;

```

### `25`

```

 lint/jsx-a11y/noRedundantRoles/reject/26/file.tsx:1:21 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━

  ✖ Using the role attribute searchbox on the input element is redundant.

    <input type='search' role='searchbox' />
                         ^^^^^^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

  - <input·type="search"·role="searchbox"·/>
  + <input·type="search"·/>

  ℹ


```

### `25: formatted`

```tsx
<input type="search" role="searchbox" />;

```

### `26`

```

 lint/jsx-a11y/noRedundantRoles/reject/27/file.tsx:1:7 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━

  ✖ Using the role attribute table on the table element is redundant.

    <table role='table' ></table>
           ^^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <table·role="table">
      1 │ + <table>
    2 2 │   </table>

  ℹ


```

### `26: formatted`

```tsx
<table role="table" />;

```

### `27`

```

 lint/jsx-a11y/noRedundantRoles/reject/28/file.tsx:1:4 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━━

  ✖ Using the role attribute term on the dt element is redundant.

    <dt role='term' ></dt>
        ^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <dt·role="term">
      1 │ + <dt>
    2 2 │   </dt>

  ℹ


```

### `27: formatted`

```tsx
<dt role="term" />;

```

### `28`

```

 lint/jsx-a11y/noRedundantRoles/reject/29/file.tsx:1:10 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━

  ✖ Using the role attribute textbox on the textarea element is redundant.

    <textarea role='textbox' ></textarea>
              ^^^^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

    1   │ - <textarea·role="textbox">
      1 │ + <textarea>
    2 2 │   </textarea>

  ℹ


```

### `28: formatted`

```tsx
<textarea role="textbox" />;

```

### `29`

```

 lint/jsx-a11y/noRedundantRoles/reject/30/file.tsx:1:19 lint/jsx-a11y/noRedundantRoles  FIXABLE  ━━━

  ✖ Using the role attribute textbox on the input element is redundant.

    <input type='text' role='textbox' />
                       ^^^^^^^^^^^^^^

  Suggested fix: Remove the role attribute.

  - <input·type="text"·role="textbox"·/>
  + <input·type="text"·/>

  ℹ


```

### `29: formatted`

```tsx
<input type="text" role="textbox" />;

```

### `30`

```

```

### `30: formatted`

```tsx
<article role="presentation" />;

```

### `31`

```

```

### `31: formatted`

```tsx
<Button role="button" />;

```

### `32`

```

```

### `32: formatted`

```tsx
<span />;

```
