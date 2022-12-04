<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/><path d="M15,8c0.34,0,0.68,0.04,1,0.1V4H4v9h6C10,10.24,12.24,8,15,8z" opacity=".3"/><path d="M13.76,15l-2.12-2.12l0.71-0.71l1.41,1.41l3.54-3.54L18,10.76L13.76,15z M10,13H4V4h12v4.1c0.35,0.07,0.68,0.18,1,0.32V4 c0-0.55-0.45-1-1-1H4C3.45,3,3,3.45,3,4v13l3-3h4.1C10.04,13.68,10,13.34,10,13C10,13,10,13,10,13z"/></g></svg>