<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} opacity=".3" width="1.5" x="5.5" y="4.5"/><rect height={size} opacity=".3" width="1.5" x="13" y="4.5"/><path d="M16,15.5V3H4v12.5H2V17h16v-1.5H16z M7,15.5H5.5v-11H7V15.5z M11.5,15.5h-3v-11h3V15.5z M14.5,15.5H13v-11h1.5V15.5z"/></g></g></svg>