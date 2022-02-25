# Svelte Library Template

## Testing

1. Create a package

```
npm run package
```

2. Link the package to NPM locally

```
cd package
npm link
```

3. Install this library in your consuming app.

```
npm link svelte-library-template
```

4. Import and use a component

```html
<script>
	import MyComponent from 'svelte-library-template/components/MyComponent.svelte';
</script>

<div>
	<MyComponent name="Garrett" />
</div>
```
