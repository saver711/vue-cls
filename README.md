# Vue-cls

A simple utility to merge class names, handle dynamic class bindings, and conditionally apply classes in Vue components based on component state or props.

## Installation

```bash
npm install vue-cls
```

## Usage

```bash
<script setup lang="ts">
import { cls } from 'vue-cls';

const isActive = true
</script>

<template>
 <a href="/" :class="cls('text-white', { 'bg-green-900': isActive }) ">Home</a>
</template>
```

## Author

[@AhmedHassan](https://www.linkedin.com/in/ahmedhassan711/)
