<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M12.75,4.25v1.5h4.5v-1.5H12.75z M11,5c0,2.21,1.79,4,4,4v8l-5-2l-5,2V3l6.54,0C11.19,3.59,11,4.27,11,5z"/></svg>