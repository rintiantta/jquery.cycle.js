# jquery.cycle.js

jQuery 1.8's toggle method.

```html
<script src="jquery.cycle.js"></script>
<script>
    $(document).ready(function () {
        $('h1').cycle(function () {
            alert('FIRST');
        }, function () {
            alert('SECONDS');
        });
    });
</script>
```
