<template>
  <p>
    <ADButton :txt="'Test Button'">
      <template v-slot:header>
        {{ 'Slot Header' }}
      </template>
      <template v-slot:content>
        {{ 'Slot Content' }}
      </template>
      <template v-slot:footer>
        {{ 'Slot Footer' }}
      </template>
    </ADButton>
  </p>
</template>
