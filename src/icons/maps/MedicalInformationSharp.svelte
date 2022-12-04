<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M18,6h-5.75V2h-4.5v4H2v12h16V6z M9.25,13.25H7.5V15H6v-1.75H4.25v-1.5H6V10h1.5v1.75h1.75V13.25z M9.25,3.5h1.5v4h-1.5 V3.5z M14,14.5h-3.25v-1H14V14.5z M15.75,12h-5v-1h5V12z"/></g></svg>