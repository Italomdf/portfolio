<script>
	import EmailIcon from "./EmailIcon.svelte";

    const myFunction = async () => {
  await navigator.clipboard.writeText('imartinsdefaveri@gmail.com');
  // Alert the copied text
  alert("Email Copied");
}
</script>
<button on:click={myFunction} ><EmailIcon/></button>