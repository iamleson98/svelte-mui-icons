<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M9.25,16.25C9.25,16.66,9.59,17,10,17s0.75-0.34,0.75-0.75l0-10.38l0.66,0.66c0.29,0.29,0.77,0.29,1.06,0 c0.29-0.29,0.29-0.77,0-1.06l-1.76-1.76c-0.39-0.39-1.02-0.39-1.41,0L7.53,5.47c-0.29,0.29-0.29,0.77,0,1.06 c0.29,0.29,0.77,0.29,1.06,0l0.66-0.66L9.25,16.25z"/></g></svg>