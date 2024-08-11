<script setup lang="ts">
import { Slider } from "@ark-ui/vue";
</script>

<template>
  <main>
    <!-- @see https://ark-ui.com/vue/docs/components/slider#range-slider -->
    <Slider.Root name="time">
      <Slider.Label>Label</Slider.Label>
      <Slider.ValueText />
      <Slider.Control>
        <Slider.Track>
          <Slider.Range />
        </Slider.Track>
        <Slider.Thumb :index="0">
          <Slider.HiddenInput />
        </Slider.Thumb>
        <Slider.Thumb :index="1">
          <Slider.HiddenInput />
        </Slider.Thumb>
      </Slider.Control>
    </Slider.Root>
  </main>
</template>
