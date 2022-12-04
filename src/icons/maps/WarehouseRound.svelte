<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><path d="M14,17h2.5c0.83,0,1.5-0.67,1.5-1.5V7.04c0-0.63-0.39-1.18-0.97-1.4l-6.5-2.44c-0.34-0.13-0.71-0.13-1.05,0l-6.5,2.44 C2.39,5.85,2,6.41,2,7.04v8.46C2,16.33,2.67,17,3.5,17H6v-7h8V17z M9.25,17h-1.5v-1.5h1.5V17z M10.75,14.5h-1.5V13h1.5V14.5z M12.25,17h-1.5v-1.5h1.5V17z"/></g></svg>