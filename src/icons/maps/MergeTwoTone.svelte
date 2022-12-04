<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M9.25,10.45c0,0.8-0.32,1.56-0.88,2.12L5,15.94L6.06,17L10,13.06L13.94,17L15,15.94l-3.37-3.37 c-0.56-0.56-0.88-1.33-0.88-2.12l0-4.58l1.19,1.19L13,6l-3-3L7,6l1.06,1.06l1.19-1.19L9.25,10.45z"/></g></svg>