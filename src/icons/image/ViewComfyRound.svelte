<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M18,8.25V5c0-0.55-0.45-1-1-1H3C2.45,4,2,4.45,2,5v3.25c0,0.55,0.45,1,1,1h14C17.55,9.25,18,8.8,18,8.25z"/><path d="M8.5,11.75V15c0,0.55,0.45,1,1,1H17c0.55,0,1-0.45,1-1v-3.25c0-0.55-0.45-1-1-1H9.5C8.95,10.75,8.5,11.2,8.5,11.75z"/><path d="M6,10.75H3c-0.55,0-1,0.45-1,1V15c0,0.55,0.45,1,1,1h3c0.55,0,1-0.45,1-1v-3.25C7,11.2,6.55,10.75,6,10.75z"/></g></g></svg>