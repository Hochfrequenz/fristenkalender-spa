<script lang="ts">
  import IconDownload from "../shared/icon-download.svelte";

  export let background = "bg-secondary";
  export let textColor = "text-white";
</script>

<div class="flex items-center gap-4">
  <button
    class="
        flex
        items-center
        gap-2
        rounded-full
        {background} 
        {textColor} 
        text-[16px]
        py-3
        px-5
        shadow-md
        ring-1
        ring-black/5
        transition-all
        duration-300
        ease-in-out
        hover:scale-105"
  >
    <IconDownload /> Download ICS
  </button>
</div>
