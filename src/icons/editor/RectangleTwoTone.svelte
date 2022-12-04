<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><rect height={size} opacity=".3" width={size} x="3.5" y="5.5"/><path d="M2,4v12h16V4H2z M16.5,14.5h-13v-9h13V14.5z"/></g></svg>