<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><g><path d="M3,5v10h14V5H3z M7.17,13.5H4.5v-7h2.67V13.5z M11.33,13.5H8.67v-2.75h2.67V13.5z M15.5,13.5h-2.67v-2.75h2.67V13.5z M15.5,9.25H8.67V6.5h6.83V9.25z"/></g></svg>