# vue-lerp-element

> A VueJs component that makes the default slot follow the mouse from its default position

## Installation

#### NPM

```bash
 npm i --save vue-lerp-element
 ```

## Example

This is the most basic usage of the component :

```vue
<template>
    <vue-lerp-element>
        <div class="circle"></div>
    </vue-lerp-element>
</template>

<script>
    import VueLerpElement from "vue-lerp-element";

    export default {
        components: {
            VueLerpElement,
        },
    };
</script>   
```

## Props

| name         |  type  | description                                                      | required | default value |
|--------------|:------:|------------------------------------------------------------------|----------|---------------|
|transitionDuration        |Number   |The duration of the transition in seconds      |false      |0.3   |
|easing        |String   |The easing of the transition (any css easing is valid)     |false      |ease-out   |
|followOffset        |Number   |The offset of the element from the mouse position (in percentage between 0 and 1)    |false      |1   |

## Contributing 

Contributions are welcome !
Follow the instructions in the [contributing file](./CONTRIBUTING.md)

## License

[MIT](./LICENCE)

