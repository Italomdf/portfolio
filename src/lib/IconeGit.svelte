<script lang='ts'>
    import GithubIcon from "./GithubIcon.svelte";
    GithubIcon

  export let cor = "#fafafa";
   export let gitref = '';


</script>

  <a href= {gitref} target="_blank">
    <button style="width: 50px; height: 50px;" class=" transition ease-in-out delay-150 transform hover:-translate-y-1 hover:scale-150 duration-300 ">
      <GithubIcon cor = {cor}/>
    </button> 
  </a>