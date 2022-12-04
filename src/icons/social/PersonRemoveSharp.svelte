<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M8,11c2,0,6,0.96,6,2.86V16H2v-2.14C2,11.96,6,11,8,11z"/><circle cx="8" cy="7" r="3"/><rect height={size} width={size} x="13" y="9"/></g></g></svg>