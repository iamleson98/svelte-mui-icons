<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M15,10c-1.1,0-2-0.9-2-2V4h1V3H6v1h1v4c0,1.1-0.9,2-2,2v1h4.5v5.5L10,17l0.5-0.5V11H15V10z"/></g></g></svg>