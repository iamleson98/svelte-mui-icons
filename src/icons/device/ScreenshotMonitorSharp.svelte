<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M18,3H2v12h5v2h6v-2h5V3z M16.5,13.5h-13v-9h13V13.5z"/><polygon points="5.5,6.5 7.5,6.5 7.5,5.5 4.5,5.5 4.5,8.5 5.5,8.5"/><polygon points="15.5,9.5 14.5,9.5 14.5,11.5 12.5,11.5 12.5,12.5 15.5,12.5"/></g></g></svg>