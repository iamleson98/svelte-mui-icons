<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M17,3H3v14h14V3z M15.5,11H12c0,1.1-0.9,2-2,2s-2-0.9-2-2H4.5V4.5h11V11z"/><polygon points="9.25,11 10.75,11 10.75,9 13,9 10,6 7,9 9.25,9"/></g></g></svg>