<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M13.5,17H18V6l-8-3L2,6v11h4.5v-6.5h7V17z M16.5,7.04v8.46H15V9H5v6.5H3.5V7.04L10,4.6L16.5,7.04z M9.25,17h-1.5v-1.5h1.5 V17z M10.75,14.5h-1.5V13h1.5V14.5z M12.25,17h-1.5v-1.5h1.5V17z"/></g></svg>