<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M15,4v12H5V4H15 M15,3H5C4.45,3,4,3.45,4,4v13h12V4C16,3.45,15.55,3,15,3L15,3z M13,9c-0.55,0-1,0.45-1,1s0.45,1,1,1 s1-0.45,1-1S13.55,9,13,9z"/></g></svg>