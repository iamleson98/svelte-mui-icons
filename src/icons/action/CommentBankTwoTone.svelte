<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M4,14.59L5.59,13H16V4H4V14.59z M11,5h4v6l-2-1.31L11,11V5z" opacity=".3"/><polygon points="15,11 15,5 11,5 11,11 13,9.69"/><path d="M16,3H4C3.45,3,3,3.45,3,4v13l3-3h10c0.55,0,1-0.45,1-1V4C17,3.45,16.55,3,16,3z M16,13H5.59L4,14.59V4h12V13z"/></g></g></svg>