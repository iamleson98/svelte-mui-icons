<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height="1.5" width={size} x="7.5" y="1.5"/><path d="M15.45,6.61l1.08-1.08l-1.06-1.06l-1.08,1.08C13.19,4.58,11.66,4,10,4c-3.87,0-7,3.13-7,7s3.13,7,7,7c3.87,0,7-3.13,7-7 C17,9.34,16.42,7.81,15.45,6.61z M10.75,12h-1.5V7h1.5V12z"/></g></g></svg>