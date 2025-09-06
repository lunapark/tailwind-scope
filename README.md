## @luna-park/tailwind-scope

Allow you to scope tailwind classes to a specific part of your DOM.

### Usage

```html
<script type="module">
import scope from 'https://esm.sh/@luna-park/tailwind-scope';
scope({ from: '#app', to: '.no-tailwind'});
</script>