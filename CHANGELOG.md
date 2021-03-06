# Changelog

#### 0.2.0
- Fix slash bug of autoclose.

#### 0.3.0
- Enable selfclose tags configuration.
- Fix typing > cause auto add right part tag to selfclose tags.

### 0.3.2
- Fix tag attributes take up multi lines cause auto close not work.

### 0.3.3
- Fix bugs produced by 0.3.2

### 0.3.4
- Stop continue close tag logic when typing slash or > in template brackets like`{#if a / b > c}`.

### 0.3.5
- Auto backspace indent for tags that across multiple lines like this:

before 0.3.5
```
<div
    aaa="bbb"
    ></div>
```
after 0.3.5
```
<div
    aaa="bbb"
></div>
```

### 0.3.6
- Add changelog of 0.3.5


### 0.3.7
- Auto close comment tag

![A screenshot of 0.3.7](https://raw.githubusercontent.com/yubaoquan/yubaoquan.github.io/master/images/auto-close-html2-demo/commentDemo.gif)

### 0.4.1
- Add freemarker support

### 0.5.0
- Add 3 more options for self-close tag

### 0.6.0
- Change `Disabled File Extensions` to `Enabled File Types` because I think file type having html-like content is less than file type not having html-like content.

- Auto detect and use the editor setting of `Tab Type` and `Tab Length`. If tab type is set to `hard`, the indent in `auto-close-html2` will be tab, otherwise whitespace.

### 0.6.1
- Update description of settings.

### 0.7.0
- Add `@` to tagName regexp
