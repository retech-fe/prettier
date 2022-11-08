# prettier

[prettier](https://prettier.io/) config


## tailwind

使用`tailwindcss`可以配合[`prettier-plugin-tailwindcss`](https://github.com/tailwindlabs/prettier-plugin-tailwindcss)来对原子类进行[排序](https://tailwindcss.com/blog/automatic-class-sorting-with-prettier#how-classes-are-sorted)

```
  plugins: [require('prettier-plugin-tailwindcss')],
  tailwindConfig: './tailwind.config.js',
```

