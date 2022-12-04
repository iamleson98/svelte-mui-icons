<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M8.25,16C8.66,16,9,15.66,9,15.25v-4.69l4-4l0,0.94c0,0.41,0.34,0.75,0.75,0.75c0.41,0,0.75-0.34,0.75-0.75l0-2.5 c0-0.55-0.45-1-1-1L11,4c-0.41,0-0.75,0.34-0.75,0.75c0,0.41,0.34,0.75,0.75,0.75l0.94,0l-4,4C7.66,9.78,7.5,10.16,7.5,10.56v4.69 C7.5,15.66,7.84,16,8.25,16z"/></g></svg>