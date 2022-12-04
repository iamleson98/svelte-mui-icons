<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g/><g><polygon opacity=".3" points="10.59,8 7,8 7,12 10.41,12 11.41,13 14,13 14,9 11.59,9"/><path d="M12,8l-1-1H7V5.85C7.29,5.67,7.5,5.37,7.5,5c0-0.55-0.45-1-1-1s-1,0.45-1,1c0,0.37,0.21,0.67,0.5,0.85V16h1v-3h3l1,1h4V8 H12z M14,13h-2.59l-1-1H7V8h3.59l1,1H14V13z"/></g></g></svg>