<script lang="ts">
  export let size: number = 20;
  export let color: string = 'currentColor';
  export let viewBox: string = '0 0 24 24';
</script>
<svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 20 20" height={size} {viewBox} width={size}><g><rect fill={color} height={size} width={size}/></g><g><g><path d="M6,8.75V15h2v-4h4v4h2V8.75l-4-3.43L6,8.75z M11,9H9c0-0.55,0.45-1,1-1C10.55,8,11,8.45,11,9z" opacity=".3"/><path d="M15,8.29V5h-2v1.57L10,4l-7,6h2v6h4v-4h2v4h4v-6h2L15,8.29z M14,15h-2v-4H8v4H6V8.75l4-3.43l4,3.43V15z"/><path d="M9,9h2c0-0.55-0.45-1-1-1C9.45,8,9,8.45,9,9z"/></g></g></svg>