<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size} x="0"/></g><g><g><rect height={size} width={size} x="6" y="6"/><rect height={size} width={size} x="11" y="6"/><rect height={size} width={size} x="6" y="11"/><rect height={size} width={size} x="11" y="11"/><path d="M16.5,4h-13C2.67,4,2,4.67,2,5.5v9C2,15.33,2.67,16,3.5,16h13c0.83,0,1.5-0.67,1.5-1.5v-9C18,4.67,17.33,4,16.5,4z M16.5,14.5h-13v-9h13V14.5z"/></g></g></svg>