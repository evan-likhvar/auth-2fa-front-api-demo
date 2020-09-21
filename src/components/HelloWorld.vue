<template>
  <div class="uk-section">
    <div class="uk-container uk-container-expand">
      <div uk-grid>
        <div class="uk-width-1-6">
          <form>
            <fieldset class="uk-fieldset">

              <legend class="uk-legend">Login</legend>

              <div class="uk-margin">
                <input class="uk-input" type="text" placeholder="Email">
              </div>

              <div class="uk-margin">
                <input class="uk-input" type="password" placeholder="Password">
              </div>

            </fieldset>
            <button class="uk-button uk-button-primary">Login</button>

          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>

</style>
