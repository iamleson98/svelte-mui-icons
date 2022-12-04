<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><polygon points="16,9 16,7 15,7 15,9 13,9 13,10 15,10 15,12 16,12 16,10 18,10 18,9"/><path d="M8,11c-2,0-6,0.96-6,2.86v1.64C2,15.78,2.22,16,2.5,16h11c0.28,0,0.5-0.22,0.5-0.5v-1.64C14,11.96,10,11,8,11z"/><circle cx="8" cy="7" r="3"/></g></g></svg>