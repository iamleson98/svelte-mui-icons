<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M6,17H3V6.89L13,3v5.5H6V17z M15.5,8.5C14.67,8.5,14,9.17,14,10H7.5v7h4v-4H13v4h4v-7C17,9.17,16.33,8.5,15.5,8.5z"/></svg>