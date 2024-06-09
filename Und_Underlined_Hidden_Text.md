# Hidden Text Underline

**A)** Class: **.hide**

Text is <u class="hide">hidden</u>.

You can <u class="hide">hide</u> the text.


**B)** Class: **.hide-c**

Text is <u class="hide-c">hidden</u>.

You can <u class="hide-c">hide</u> the text.

### Show text on hover -> reading mode

**C)** Class: **.hide-r**

You can <u class="hide-r">hide</u> the text.


**D)** Class: **.hide-rc**

You can <u class="hide-rc">hide</u> the text.

## Overview of the hidden text underline

A) **Show text on hover** (hide text on live preview and reading modes)

Add the `hide` class to the `<u>` HTML tags.

```html
You can <u class="hide">hide</u> the text.
```

B) **Show text on click and hold** (hide text on live preview and reading modes)

Add the `hide-c` class to the `<u>` HTML tags (it will **reveal on click**).

```html
You can <u class="hide-c">hide</u> the text.
```

C) **Hide text on reading mode only - show on hover**

Add the `hide-r` class to the `<u>` HTML tags. It will **reveal on hover** (reading mode).

```html
You can <u class="hide-r">hide</u> the text.
```

D) **Hide text on reading mode only - show on click**

Add the `hide-rc` class to the `<u>` HTML tags. It will **reveal on click** (reading mode).

```html
You can <u class="hide-rc">hide</u> the text.
```

- The hidden text will appear on **hover** or on **click** (bolder and highlighted). You can change the **background (highlight)** and **foreground** color using the Style Settings options (different colors for light and dark modes).

E) **Hide on reading mode only - show on hover - full width**

- Add the `hide-w` class. It will hide the text on reading mode and occupy the full width of the parent element (table column) or page.

```html
Question: What is the name of this theme? <u class="hide-w">MagicUser</u>
```


| Column 1  | Column 2 |  Column 3 |
| :---:     | :---:    |  :---:    |
| <u class="hide-w">Text1</u>    | Text 2   | Text 3    |
| <u class="hide-w">Text 4</u>  | Text 5   | Text 6    |
| <u class="hide-w">Text 7</u>   | Text 8   | Text 9    |
| <u class="hide-w"> Text 10</u>   | Text 11  | Text 12   |

Question: What is the name of this theme? <u class="hide-w">MagicUser</u>
