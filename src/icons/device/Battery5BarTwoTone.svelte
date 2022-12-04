<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><rect height="3.5" opacity=".3" width={size} x="7.5" y="5"/><path d="M13,3.5c0.55,0,1,0.45,1,1V17c0,0.55-0.45,1-1,1H7c-0.55,0-1-0.45-1-1V4.5c0-0.55,0.45-1,1-1h1.5V2h3v1.5H13z M12.5,5h-5 v3.5h5V5z"/></g></svg>