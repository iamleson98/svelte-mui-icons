<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M6.22,7.28L4.5,6.5l1.72-0.78L7,4l0.78,1.72L9.5,6.5L7.78,7.28L7,9L6.22,7.28z M7,17l0.78-1.72L9.5,14.5l-1.72-0.78L7,12 l-0.78,1.72L4.5,14.5l1.72,0.78L7,17z M4.5,12l0.47-1.03L6,10.5l-1.03-0.47L4.5,9l-0.47,1.03L3,10.5l1.03,0.47L4.5,12z M15.5,18 c-3.21-1.23-5.5-4.36-5.5-8c0-2.2,0.83-4.24,2.2-5.8L10,2h5.5v5.5l-2.23-2.23C12.17,6.55,11.5,8.21,11.5,10c0,2.81,1.64,5.23,4,6.37 L15.5,18z M20,11.5h-1.5V10H17v1.5h-1.5V13H17v1.5h1.5V13H20V11.5z"/></svg>