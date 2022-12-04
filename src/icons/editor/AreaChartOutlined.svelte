<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M14,6l-4-3L6,8L3,6v10h14V6H14z M15.5,13.8L10,9.39L7,13.5l-2.5-1.88V8.8l1.81,1.21l3.95-4.94L13.5,7.5h2V13.8z"/></svg>