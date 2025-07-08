<!--
SPDX-FileCopyrightText: syuilo and misskey-project
SPDX-License-Identifier: AGPL-3.0-only
-->

<template>
<PageWithHeader>
	<div class="_spacer" style="--MI_SPACER-w: 800px;">
		<YamiSearch />
	</div>
</PageWithHeader>
</template>

<script setup lang="ts">
import { definePage } from '@/page.js';
import { i18n } from '@/i18n.js';
import YamiSearch from '@/components/YamiSearch.vue';

definePage(() => ({
	title: i18n.ts._yami.searchYamiNotes,
	icon: 'ti ti-search',
}));
</script> 