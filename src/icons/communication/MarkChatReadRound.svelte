<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M14.11,14.65c-0.2,0.2-0.51,0.2-0.71,0l-1.41-1.41c-0.2-0.2-0.2-0.51,0-0.71v0c0.2-0.2,0.51-0.2,0.71,0l1.06,1.06 l3.18-3.18c0.2-0.2,0.51-0.2,0.71,0l0,0c0.2,0.2,0.2,0.51,0,0.71L14.11,14.65z M10,13c0-2.76,2.24-5,5-5c0.71,0,1.39,0.15,2,0.42V4 c0-0.55-0.45-1-1-1H4C3.45,3,3,3.45,3,4v13l3-3h4.1C10.04,13.68,10,13.34,10,13z"/></g></svg>