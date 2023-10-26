# Snippets

**Snippets are found below.**

→ Denotes the `TAB` key.

| Snippet→     | Output            |
| ----------  | -------------------|
| [`nfor→`](#nfor) | Nue For Loop |
| [`nif→`](#nif) | Nue If Statement  |
| [`nscript→`](#nscript) | Nue Script with all lifecycle methods |
| [`nattr→`](#nattr) | Rendering attributes with :attr |
| [`ncomp→`](#ncomp) | Nue Component |

## `nfor`

```js
:for="(item, index) in array"
```

## `nif`

```html
<div :if="condition"></div>
<div :else-if="condition"></div>
<div :else></div>
```

## `nscript`

```html
<script>
  constructor(data) {

  }
  mounted() {

  }
  updated() {

  }
  unmounted() {

  }
</script>
```

## `nattr`

```html
<div :attr="data">
  <script>
    data = {

    }
  </script>
</div>
```

## `ncomp`

```html
<div @name="comp">

</div>
```
