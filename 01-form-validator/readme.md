### Key Takeaways

#### CSS

- How to define and use variables in CSS.

- relative and absolute positioning on form-control and 'small' elements, respectively.

- Very important - [Why use position: absolute on `<small>` element?](https://chatgpt.com/c/6851502c-31dc-8002-8f9c-60f9e5f754d4)

```
.form-control small {
  color: var(--error-color);
  position: absolute;
  bottom: 0;
  left: 0;
  /* visibility: hidden; */
}
```