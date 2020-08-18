<template>
  <v-treeview
    selectable
    selected-color="teal darken-4"
    :items="items"
  ></v-treeview>
</template>

<script>
  export default {
    data: () => ({
      items: [
        {
          id: 1,
          name: 'Ils savent faire des tours :',
          children: [
            { id: 2, name: 'Assis' },
            { id: 3, name: 'Couché' },
            { id: 4, name: 'Donne la patte' },
          ],
        },
        {
          id: 5,
          name: 'Ils comprennent notre langage :',
          children: [
                { id: 6, name: 'Quand on leur dit de boire un coup'},
                { id: 7, name: 'Quand on leur dit "Bon chien"' },
                { id: 8, name: 'Quand ils font des bêtises' },

              ],
            },
]
})
}

</script>
