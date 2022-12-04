<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} opacity=".2" width="1.12" x="10.75" y="4.5"/><rect height={size} opacity=".2" width="1.12" x="8.12" y="4.5"/><rect height={size} opacity=".2" width="1.12" x="5.5" y="4.5"/><rect height={size} opacity=".2" width="1.12" x="13.38" y="4.5"/><path d="M16,15.5V3H4v12.5H2V17h16v-1.5H16z M6.62,15.5H5.5v-11h1.12V15.5z M9.25,15.5H8.12v-11h1.12V15.5z M11.88,15.5h-1.12v-11 h1.12V15.5z M14.5,15.5h-1.12v-11h1.12V15.5z"/></g></g></svg>