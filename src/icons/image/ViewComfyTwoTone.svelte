<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height="3.75" opacity=".3" width="3.5" x="3.5" y="10.75"/><rect height="3.75" opacity=".3" width={size} x="8.5" y="10.75"/><rect height="3.75" opacity=".3" width={size} x="3.5" y="5.5"/><path d="M2,4v12h16V4H2z M7,14.5H3.5v-3.75H7V14.5z M16.5,14.5h-8v-3.75h8V14.5z M16.5,9.25h-13V5.5h13V9.25z"/></g></g></svg>