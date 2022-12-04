<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M5,5.75L5,5.75C5,6.16,5.34,6.5,5.75,6.5h6.69l-7.91,7.91c-0.29,0.29-0.29,0.77,0,1.06l0,0c0.29,0.29,0.77,0.29,1.06,0 l7.91-7.91v6.69c0,0.41,0.34,0.75,0.75,0.75h0c0.41,0,0.75-0.34,0.75-0.75V6c0-0.55-0.45-1-1-1H5.75C5.34,5,5,5.34,5,5.75z"/></g></svg>