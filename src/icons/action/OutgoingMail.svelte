<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M15,10.5c0.73,0,1.41,0.21,2,0.55V5c0-0.55-0.45-1-1-1H4C3.45,4,3,4.45,3,5v10c0,0.55,0.45,1,1,1h7.3 c-0.19-0.46-0.3-0.97-0.3-1.5C11,12.29,12.79,10.5,15,10.5z M4,6.18V5l6,3.75L16,5v1.18l-6,3.75L4,6.18z"/><polygon points="15.17,11.67 14.46,12.38 16.09,14 12,14 12,15 16.09,15 14.46,16.62 15.17,17.33 18,14.5"/></g></g></svg>