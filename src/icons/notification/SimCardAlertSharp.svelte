<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><g><path d="M20,2H10L4,8v14h16V2z M13,17h-2v-2h2V17z M13,13h-2V8h2V13z"/></g></g></g></svg>