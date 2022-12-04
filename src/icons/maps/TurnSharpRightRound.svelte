<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M7,16.25C7,16.66,6.66,17,6.25,17S5.5,16.66,5.5,16.25V12c0-0.83,0.67-1.5,1.5-1.5l6,0l0-4.63l-0.66,0.66 c-0.29,0.29-0.77,0.29-1.06,0c-0.29-0.29-0.29-0.77,0-1.06l1.76-1.76c0.39-0.39,1.02-0.39,1.41,0l1.76,1.76 c0.29,0.29,0.29,0.77,0,1.06c-0.29,0.29-0.77,0.29-1.06,0L14.5,5.87l0,4.63c0,0.83-0.67,1.5-1.5,1.5l-6,0V16.25z"/></g></svg>