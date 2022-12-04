<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M13.5,14.78l-3.5-1.4l-3.5,1.4V4.5l4.53,0C11.01,4.66,11,4.83,11,5c0,1.68,1.03,3.12,2.5,3.71L13.5,14.78z" opacity=".3"/><path d="M12.75,4.25v1.5h4.5v-1.5H12.75z M15,17l-5-2l-5,2V4.5C5,3.67,5.67,3,6.5,3l5.04,0c-0.26,0.45-0.44,0.96-0.5,1.5l-4.53,0 v10.28l3.5-1.4l3.5,1.4V8.71h0C13.96,8.9,14.47,9,15,9V17z"/></svg>