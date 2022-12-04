<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M17.5,3h-15C1.67,3,1,3.67,1,4.5V12h1.5V4.5h15V17c0.83,0,1.5-0.67,1.5-1.5v-11C19,3.67,18.33,3,17.5,3z"/><circle cx="7" cy="9" r="3"/><path d="M12.03,14.37C10.56,13.5,8.84,13,7,13s-3.56,0.5-5.03,1.37C1.36,14.72,1,15.39,1,16.09V18h12v-1.91 C13,15.39,12.64,14.72,12.03,14.37z"/></g></g></svg>