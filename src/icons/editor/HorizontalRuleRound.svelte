<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M16,11H4c-0.55,0-1-0.45-1-1v0c0-0.55,0.45-1,1-1h12c0.55,0,1,0.45,1,1v0C17,10.55,16.55,11,16,11z"/></g></svg>