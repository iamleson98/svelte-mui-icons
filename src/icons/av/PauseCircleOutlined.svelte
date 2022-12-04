<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M10,2c-4.42,0-8,3.58-8,8s3.58,8,8,8s8-3.58,8-8S14.42,2,10,2z M10,16.5c-3.58,0-6.5-2.92-6.5-6.5S6.42,3.5,10,3.5 s6.5,2.92,6.5,6.5S13.58,16.5,10,16.5z"/><rect height={size} width="1.5" x="7.5" y="7"/><rect height={size} width="1.5" x="11" y="7"/></g></g></svg>