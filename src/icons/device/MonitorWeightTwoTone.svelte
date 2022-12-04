<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height={size} {viewBox} width={size}><g><path d="M0,0h24v24H0V0z" fill={color}/></g><g><g><rect height={size} opacity=".3" width={size} x="13" y="8.5"/><rect height={size} opacity=".3" width={size} x="10" y="8.5"/><rect height={size} opacity=".3" width={size} x="11.5" y="8.5"/><path d="M5,19h14V5H5V19z M12,6c1.66,0,3,1.34,3,3s-1.34,3-3,3s-3-1.34-3-3S10.34,6,12,6z" opacity=".3"/><path d="M12,12c1.66,0,3-1.34,3-3s-1.34-3-3-3S9,7.34,9,9S10.34,12,12,12z M13,8.5h1v1h-1V8.5z M11.5,8.5h1v1h-1V8.5z M10,8.5h1v1 h-1V8.5z"/><path d="M19,3H5C3.9,3,3,3.9,3,5v14c0,1.1,0.9,2,2,2h14c1.1,0,2-0.9,2-2V5C21,3.9,20.1,3,19,3z M19,19H5V5h14V19z"/></g></g></svg>