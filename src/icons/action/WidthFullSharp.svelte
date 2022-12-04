<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M18,4H2v12h16V4z M3.5,5.5h1v9h-1V5.5z M16.5,14.5h-1v-9h1V14.5z"/></g></svg>