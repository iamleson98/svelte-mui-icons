<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M3,4v12h14V4H3z M9,13H5v-1h4V13z M9,10.5H5v-1h4V10.5z M9,8H5V7h4V8z M11.97,11.77l-1.41-1.41l0.71-0.71l0.71,0.71l2.12-2.12l0.71,0.71L11.97,11.77z" fill-rule="evenodd"/></g></svg>