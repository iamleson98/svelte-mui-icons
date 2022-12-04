<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} y="0"/></g><g><g><path d="M16.5,8.5h-2v1.26c0,0.73,0.37,1.4,1,1.79c0.63-0.39,1-1.06,1-1.79V8.5z" opacity=".3"/><rect height="1.5" width={size} x="2" y="16.5"/><path d="M12.5,13.5H9V12H6v1.5H2.5C2.22,13.5,2,13.72,2,14v1h11v-1C13,13.72,12.78,13.5,12.5,13.5z"/><path d="M18,9.76V2h-5v7.76c0,1.27,0.67,2.44,1.75,3.09V18H18v-1.5h-1.75v-3.65C17.33,12.2,18,11.04,18,9.76z M14.5,3.5h2V7h-2 V3.5z M15.5,11.55c-0.63-0.39-1-1.06-1-1.79V8.5h2v1.26C16.5,10.49,16.13,11.16,15.5,11.55z"/></g></g></svg>