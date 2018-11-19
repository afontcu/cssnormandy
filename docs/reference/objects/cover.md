# Cover

| Class         | Property                                                            |
| --------------| ------------------------------------------------------------------- |
| o-cover       | display: flex, background-position: center; background-size: cover; |
| o-cover__body | margin:auto padding: $global-spacing-unit                           |                         

::: tip Where can I see more about Cover Object?
 It is located in `5-Objects/_objects.cover.scss`
:::


## Cover Object

#### Use `o-cover` to create a cover-object

```html
<div class="o-cover o-cover--demo">
     <div class="o-cover__body">
        Lorem ipsum dolor sit amet
    </div>
</div>
```
---

<code>
    <div class="o-cover o-cover--demo">
        <div class="o-cover__body">
            Lorem ipsum dolor sit amet
        </div>
    </div>
</code>

## Size modifiers

#### Use `o-cover--{size}`

```html
<div class="o-cover o-cover--demo">
     <div class="o-cover__body">
        Lorem ipsum dolor sit amet
    </div>
</div>
```
---

<code>
    <p class="u-m u-text-h4">flush</p>
    <div class="o-cover o-cover--flush o-cover--demo">
        <div class="o-cover__body">
            Lorem ipsum dolor sit amet
        </div>
    </div>  
    <p class="u-m u-text-h4">tiny</p>
    <div class="o-cover o-cover--tiny o-cover--demo">
        <div class="o-cover__body">
            Lorem ipsum dolor sit amet
        </div>
    </div>
    <p class="u-m u-text-h4">small</p>
    <div class="o-cover o-cover--small o-cover--demo">
        <div class="o-cover__body">
            Lorem ipsum dolor sit amet
        </div>
    </div>
    <p class="u-m u-text-h4">large</p>
    <div class="o-cover o-cover--large o-cover--demo">
        <div class="o-cover__body">
            Lorem ipsum dolor sit amet
        </div>
    </div>
    <p class="u-m u-text-h4">huge</p>
    <div class="o-cover o-cover--huge o-cover--demo">
        <div class="o-cover__body">
            Lorem ipsum dolor sit amet
        </div>
    </div>
</code>

## Alignment modifiers

<br>Use `o-cover--{alignment}`

<code>
<p class="u-m u-text-h4">left</p>
    <div class="o-cover o-cover--left o-cover--demo">
        <div class="o-cover__body">
            Lorem ipsum dolor sit amet
        </div>
      </div>
<p class="u-m u-text-h4">right</p>
      <div class="o-cover o-cover--right o-cover--demo">
          <div class="o-cover__body">
              Lorem ipsum dolor sit amet
          </div>
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