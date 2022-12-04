<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><g opacity=".3"><path d="M4.5,15.5h11v-11h-11V15.5z M11,6h3v3h-3V6z M11,11h3v3h-3V11z M6,6h3v3H6V6z M6,11h3v3H6V11z"/></g><g><rect height={size} width={size} x="6" y="11"/></g><g><rect height={size} width={size} x="11" y="11"/></g><g><path d="M15.5,3h-11C3.67,3,3,3.67,3,4.5v11C3,16.33,3.67,17,4.5,17h11c0.83,0,1.5-0.67,1.5-1.5v-11C17,3.67,16.33,3,15.5,3z M15.5,15.5h-11v-11h11V15.5z"/></g><g><rect height={size} width={size} x="6" y="6"/></g><g><rect height={size} width={size} x="11" y="6"/></g></g></g></svg>