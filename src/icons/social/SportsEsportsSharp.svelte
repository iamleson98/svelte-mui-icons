<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M15,6H5l-1,9h2l2-2h4l2,2h2L15,6z M9.25,9.75H8V11H7.5V9.75H6.25v-0.5H7.5V8H8v1.25h1.25V9.75z M11.5,9 C11.22,9,11,8.78,11,8.5C11,8.22,11.22,8,11.5,8S12,8.22,12,8.5C12,8.78,11.78,9,11.5,9z M12.5,11c-0.28,0-0.5-0.22-0.5-0.5 c0-0.28,0.22-0.5,0.5-0.5s0.5,0.22,0.5,0.5C13,10.78,12.78,11,12.5,11z"/></g></g></svg>