
<script>
    const obj = {
    foo: {
        bar: {
        baz: 42,
        },
    },
    };

    const baz = obj?.foo?.bar?.baz; // 42

    const safe = obj?.qux?.baz; // undefined

    // Optional chaining and normal chaining can be intermixed
    console.log(baz, safe);
</script>