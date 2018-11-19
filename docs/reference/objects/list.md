# List

| Class         | Property                           |
| --------------| ---------------------------------- |
| o-list        | margin:0 padding:0 list-style:none |
| o-list__item  | display:inline-block               |
| o-list--block | display:block                      |

::: tip Where can I see more about List Object?
 It is located in `5-Objects/_objects.list.scss`
:::

---

## List Object

#### Use `o-list` to create a list-object

```html
    <div class="o-list">
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
    </div>
```
---

<code>
    <div class="o-list">
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
    </div>
</code>

## Display Modifiers

#### Use `o-list--block`

```html
    <div class="o-list o-list--block">
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
    </div>
```
---

<code>
    <div class="o-list o-list--block">
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
        <div class="o-list__item">Item</div>
    </div>
</code>

<style lang="scss">
@import '../../.vuepress/scss/main.scss';
@import './outline.css';

code {
    div {
        color:black;
    }
    p {
        color:black;
    }
}

.o-cover--demo {
    background-image:url('http://unsplash.it/960/600');
    height: 250px;
}

</style>