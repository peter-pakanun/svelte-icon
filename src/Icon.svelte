<script>
  export let d;
  export let fill = "currentColor";
  export let stroke = "";
  export let title = '';

	let classProp = '';
	export { classProp as class };
</script>

<svg viewBox="0 0 24 24" class={classProp} {...$$restProps}>
  {#if title}<title>{title}</title>{/if}
  <path {fill} {stroke} {d} />
</svg>