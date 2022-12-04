<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M10,3C8.34,3,7,4.34,7,6c0,1.66,1.34,3,3,3s3-1.34,3-3C13,4.34,11.66,3,10,3z M14,11c-1.66,0-3,1.34-3,3c0,1.66,1.34,3,3,3 s3-1.34,3-3C17,12.34,15.66,11,14,11z M6,11c-1.66,0-3,1.34-3,3c0,1.66,1.34,3,3,3s3-1.34,3-3C9,12.34,7.66,11,6,11z"/></svg>