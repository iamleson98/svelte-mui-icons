<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><rect fill={color} height={size} width={size}/><path d="M7.06 8H2.43c-.47 0-.68.6-.31.89l3.82 3.04-1.42 4.58c-.14.46.39.84.78.55L9 14.25l3.7 2.81c.39.29.92-.08.78-.55l-1.42-4.58 3.82-3.04c.37-.29.16-.89-.31-.89h-4.63L9.48 3.47c-.15-.46-.8-.46-.95 0L7.06 8zm4.3-3.56.67 2.06h1.58l-.98-3.03c-.15-.46-.8-.46-.95 0l-.32.97zM16.9 10l-3.1 2.47 1.23 3.97.81.62c.39.29.92-.08.78-.55L15.53 13l2.65-2.11c.37-.29.17-.89-.31-.89h-.97z"/></svg>