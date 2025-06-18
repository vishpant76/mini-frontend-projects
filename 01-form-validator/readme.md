### Key Takeaways

#### CSS

- How to define and use variables in CSS.

- relative and absolute positioning on form-control and 'small' elements, respectively.

- Very important - [Why use position: absolute on `<small>` element?](https://chatgpt.com/c/6851502c-31dc-8002-8f9c-60f9e5f754d4). This discussion should clear the doubts regarding what exactly is absolute positioning and how it behaves within its relatively positioned parent, and how it may affect the spacing betweeen other nearby elements on the page.

```
.form-control small {
  color: var(--error-color);
  position: absolute;
  bottom: 0;
  left: 0;
  /* visibility: hidden; */
}
```

- `border: #00ff00 solid 1px;` is helpful to visualize almost everything on the page in terms of boxes.