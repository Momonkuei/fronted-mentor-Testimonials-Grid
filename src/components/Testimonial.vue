<template>
	<div
		class="pt-[26px] p-8 rounded-lg relative"
		:style="{ backgroundColor: bgColor }"
	>
		<!-- 作者 -->
		<div
			class="flex gap-[17px] items-center mb-[18px] leading-none relative z-[2]"
		>
			<div
				class="rounded-full border-2 overflow-hidden inline-block"
				:style="{ borderColor: borderColor }"
			>
				<img class="w-6 h-6" :src="imgUrl" alt="" />
			</div>
			<div
				class="flex flex-col gap-1 leading-none"
				:style="{ color: titleColor }"
			>
				<span class="text-[13px] inline-block">{{ name }}</span>
				<span class="text-[11px] opacity-50 inline-block">{{
					identity
				}}</span>
			</div>
		</div>

		<!-- 主評論 -->
		<div class="mb-4 relative z-[2]">
			<div
				class="text-xl font-semibold leading-[1.2] z-[2]"
				:style="{ color: mainCommentColor }"
			>
				{{ mainComment }}
			</div>
		</div>

		<!-- 副評論 -->
		<div>
			<div
				class="text-[13px] opacity-70 font-medium leading-[18px] z-[2]"
				:style="{ color: subCommentColor }"
			>
				{{ subComment }}
			</div>
		</div>
		<slot></slot>
	</div>
</template>

<script setup>
defineProps({
	bgColor: String,
	borderColor: String,
	titleColor: String,
	name: String,
	identity: String,
	mainComment: String,
	mainCommentColor: String,
	subComment: String,
	subCommentColor: String,
	imgUrl: String,
});
</script>
