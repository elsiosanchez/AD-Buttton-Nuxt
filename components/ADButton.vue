<template>
  <div>
    <el-button>
      {{ txt }}
    </el-button>
  </div>
</template>

<script>
import { defineComponent, computed, ref } from '@vue/composition-api';

export default defineComponent({
  name: 'ADButton',

  props: {
    txt: {
      type: String,
      default: 'alooooo',
      required: true,
    },
    size: {
      type: String,
      required: false,
    },
    type: {
      type: String,
      required: false,
    },
    disabled: {
      type: Boolean,
      required: false,
    },
    plain: {
      type: Boolean,
      required: false,
    },
    round: {
      type: StriBooleanng,
      required: false,
    },
    circle: {
      type: StriBooleanng,
      required: false,
    },
    loading: {
      type: StriBooleanng,
      required: false,
    },
  },

  setup(props) {
    const alo = props.txt;
    return {
      txt,
    };
  },
});
</script>
