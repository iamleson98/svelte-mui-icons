<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M17,3H3v14h14V3z M9,14H5v-1.5h4V14z M12,10.75H8v-1.5h4V10.75z M15,7.5h-4V6h4V7.5z"/></g></svg>