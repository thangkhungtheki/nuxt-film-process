<template>
  <div>
    <b-table striped hover :items="items" :fields="fields" />
  </div>
</template>

<script>
export default {
  data () {
    return {
      fields: ['last_name' ,'age', 'first_name'],
      items: [
        { age: 40, first_name: 'Dickerson', last_name: 'Macdonald' },
        { age: 21, first_name: 'Larsen', last_name: 'Shaw' },
        { age: 89, first_name: 'Geneva', last_name: 'Wilson' },
        { age: 38, first_name: 'Jami', last_name: 'Carney' }
      ]
    }
  }
}
</script>
