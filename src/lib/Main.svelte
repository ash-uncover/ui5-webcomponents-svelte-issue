<script>
  import '@ui5/webcomponents/dist/Label.js'
  import '@ui5/webcomponents/dist/Tab.js'
  import '@ui5/webcomponents/dist/TabContainer'
</script>

<ui5-tabcontainer fixed>
  <ui5-tab text='Tab1' selected>
    <ui5-label>Tab1</ui5-label>
  </ui5-tab>
  <ui5-tab text='Tab2'>
    <ui5-label>Tab2</ui5-label>
  </ui5-tab>
</ui5-tabcontainer>

<style>
  ui5-tabcontainer {
    height: 100%;
  }
</style>
