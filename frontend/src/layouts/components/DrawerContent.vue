<script setup>
import {
  VerticalNavLink,
  VerticalNavSectionTitle,
} from '@layouts'
</script>

<template>
    <ul>
        <VerticalNavSectionTitle :item="{ heading: '작가관리' }" />
        <VerticalNavLink
            :item="{
                title: '작가',
                to: '/authors',
            }"
        />
        <VerticalNavSectionTitle :item="{ heading: '집필관리' }" />
        <VerticalNavLink
            :item="{
                title: '원고',
                to: '/manuscripts',
            }"
        />
        <VerticalNavSectionTitle :item="{ heading: '포인트관리' }" />
        <VerticalNavLink
            :item="{
                title: '포인트',
                to: '/points',
            }"
        />
        <VerticalNavLink
            :item="{
                title: '포인트조회',
                to: '/getPoints',
            }"
        />
        <VerticalNavSectionTitle :item="{ heading: '구독자관리' }" />
        <VerticalNavLink
            :item="{
                title: '구독자',
                to: '/users',
            }"
        />
        <VerticalNavLink
            :item="{
                title: '구독',
                to: '/subscriptions',
            }"
        />
        <VerticalNavLink
            :item="{
                title: '구독 열람',
                to: '/getSubscriptions',
            }"
        />
        <VerticalNavSectionTitle :item="{ heading: '플랫폼' }" />
        <VerticalNavLink
            :item="{
                title: '도서',
                to: '/books',
            }"
        />
        <VerticalNavLink
            :item="{
                title: '도서 조회',
                to: '/getBookByIds',
            }"
        />
        <VerticalNavSectionTitle :item="{ heading: 'AI도서처리' }" />
        <VerticalNavLink
            :item="{
                title: 'AI자동화',
                to: '/aiBookGenerations',
            }"
        />
        <VerticalNavLink
            :item="{
                title: 'AI도서처리결과',
                to: '/processedResults',
            }"
        />
    </ul>
</template>
