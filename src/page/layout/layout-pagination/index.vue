<template>
<div class="pagination-cell cf">
    <slot></slot>
</div>
</template>

<script>
export default {
    name: 'LayoutPagination'
}
</script>
<style lang="scss" scoped>
.pagination-cell {
	.el-pagination {
		float: right;
		padding: 0;
	}
}
</style>
