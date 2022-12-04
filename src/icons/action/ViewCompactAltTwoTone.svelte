<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M3.5,14.5h13v-9h-13V14.5z M10.5,6.5h3v3h-3V6.5z M10.5,10.5h3v3h-3V10.5z M6.5,6.5h3v3h-3V6.5z M6.5,10.5 h3v3h-3V10.5z" opacity=".3"/><rect height={size} width={size} x="6.5" y="6.5"/><rect height={size} width={size} x="10.5" y="6.5"/><rect height={size} width={size} x="6.5" y="10.5"/><rect height={size} width={size} x="10.5" y="10.5"/><path d="M16.5,4h-13C2.67,4,2,4.67,2,5.5v9C2,15.33,2.67,16,3.5,16h13c0.83,0,1.5-0.67,1.5-1.5v-9C18,4.67,17.33,4,16.5,4z M16.5,14.5h-13v-9h13V14.5z"/></g></g></svg>