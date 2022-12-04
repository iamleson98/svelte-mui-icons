<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M11.5,8.75v0.5h-2v-0.5c0-0.55-0.45-1-1-1h-1V6.5h1c0.55,0,1-0.45,1-1V3c0-0.55-0.45-1-1-1H5C4.45,2,4,2.45,4,3v2.5 c0,0.55,0.45,1,1,1h1v1.25H5c-0.55,0-1,0.45-1,1v2.5c0,0.55,0.45,1,1,1h1V14H5c-0.55,0-1,0.45-1,1v2.5c0,0.55,0.45,1,1,1h3.5 c0.55,0,1-0.45,1-1V15c0-0.55-0.45-1-1-1h-1v-1.75h1c0.55,0,1-0.45,1-1v-0.5h2v0.5c0,0.55,0.45,1,1,1H16c0.55,0,1-0.45,1-1v-2.5 c0-0.55-0.45-1-1-1h-3.5C11.95,7.75,11.5,8.2,11.5,8.75z"/></svg>