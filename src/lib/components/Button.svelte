<script>
    /**
	 * @type {string}
	 */
     export let text;
</script>

<button on:click={() => console.log('Button clicked!')}>
    {text}
</button>
