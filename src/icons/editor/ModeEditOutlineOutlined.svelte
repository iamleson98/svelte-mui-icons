<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M3,14v3h3l8.62-8.62l-3-3L3,14z M5.38,15.5H4.5v-0.88l7.12-7.12l0.88,0.88L5.38,15.5z"/><path d="M16.71,4.88l-1.59-1.59c-0.39-0.39-1.02-0.39-1.41,0l-1.03,1.02l3,3l1.03-1.02C17.1,5.9,17.1,5.27,16.71,4.88z"/></g></g></svg>