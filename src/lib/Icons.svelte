<script>
	import CvIcon from "$lib/CvIcon.svelte";
  import GithubIcon from "./GithubIcon.svelte";
	import LinkedinIcon from "./LinkedinIcon.svelte";
    GithubIcon
    CvIcon
    LinkedinIcon

  export let cor = "#fafafa";
  cor

</script>



  <a href="https://github.com/italomdf" target="_blank">
    <button class=" transition ease-in-out delay-150 transform hover:-translate-y-1 hover:scale-150 duration-300 ">
      <GithubIcon cor = {cor}/>
    </button> 
  </a>
  <a href="https://www.linkedin.com/in/italo-de-faveri-421901207/"  target="_blank">
    <button class=" transition ease-in-out delay-150 transform hover:-translate-y-1 hover:scale-150 duration-300">
      <LinkedinIcon cor = {cor}/>
    </button> 
  </a>

  <a href="Cv_Italo_En.pdf" target="_blank">
    <button class=" transition ease-in-out delay-150 transform hover:-translate-y-1 hover:scale-150 duration-300">
      <CvIcon cor = {cor} />
    </button> 
  </a>