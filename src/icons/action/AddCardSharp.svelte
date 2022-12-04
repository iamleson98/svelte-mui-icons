<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M18,4H2v12h10v-1.5H3.5V10H18V4z M16.5,7h-13V5.5h13V7z M20,15.5h-2.5V18H16v-2.5h-2.5V14H16v-2.5h1.5V14H20V15.5z"/></g></svg>