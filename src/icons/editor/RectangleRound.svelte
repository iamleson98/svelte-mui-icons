<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M16.5,16h-13C2.67,16,2,15.33,2,14.5v-9C2,4.67,2.67,4,3.5,4h13C17.33,4,18,4.67,18,5.5v9C18,15.33,17.33,16,16.5,16z"/></g></svg>