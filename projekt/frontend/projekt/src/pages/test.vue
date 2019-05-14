<template>
<q-page padding>
 <div class="row q-gutter-xs">
      <div class="col">
        jedan
        <div>
        <q-btn color="primary" label="Primary" @click="handleClick" />
        <q-input outlined v-model="myInput" label="Outlined" />
        </div>
      </div>
      <div class="col">
        dva
      </div>
    </div>
  </q-page>
</template>

<script>
export default {
  data () {
    return {
      myInput: ''
    }
  },
  methods: {
    handleClick () {
      this.myInput = 'clicked'
    }
  }
}
</script>
