<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><rect height={size} opacity=".3" width="7.5" x="3.5" y="3.5"/><path d="M11,2H3.5C2.67,2,2,2.67,2,3.5v13C2,17.33,2.67,18,3.5,18H11c0.83,0,1.5-0.67,1.5-1.5v-13C12.5,2.67,11.83,2,11,2z M11,16.5H3.5v-13H11V16.5z"/><path d="M14,4v12c0.83,0,1.5-0.67,1.5-1.5v-9C15.5,4.67,14.83,4,14,4z"/><path d="M17,5v10c0.58-0.21,1-0.76,1-1.41V6.41C18,5.76,17.58,5.21,17,5z"/></g></g></svg>