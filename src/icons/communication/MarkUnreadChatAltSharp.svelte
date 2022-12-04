<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><circle cx="15.5" cy="2.75" r="2.5"/><path d="M14.15,6.5H5V5h7.2c-0.33-0.49-0.9-1.55-0.62-3H2v16l3-3h13V5.85c-0.69,0.56-1.55,0.9-2.5,0.9 C15.03,6.75,14.58,6.65,14.15,6.5z M12,12H5v-1.5h7V12z M15,9.25H5v-1.5h10V9.25z"/></g></g></svg>