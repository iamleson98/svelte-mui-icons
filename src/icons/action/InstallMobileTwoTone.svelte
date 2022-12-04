<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} opacity=".3" width={size} x="5.5" y="16.5"/><rect height={size} opacity=".3" width="6.5" x="5.5" y="2.5"/><path d="M14.5,15h-9V5H12V3.5H5.5v-1H12V1H5.5C4.67,1,4,1.67,4,2.5v15C4,18.33,4.67,19,5.5,19h9c0.83,0,1.5-0.67,1.5-1.5V13h-1.5 V15z M14.5,17.5h-9v-1h9V17.5z"/><polygon points="16,3 14.5,3 14.5,3.5 14.5,5 14.5,8.14 12.81,6.45 12,7.27 11.75,7.52 12,7.77 15.23,11 17,9.23 18.75,7.48 17.69,6.42 17,7.11 16,8.11"/></g></g></svg>