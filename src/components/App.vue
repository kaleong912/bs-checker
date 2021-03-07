<template>
    <Page>
        <ActionBar title="Welcome!"/>
        <GridLayout columns="*" rows="*">
            <Label class="message" :text="msg" col="0" row="0"/>
        </GridLayout>
    </Page>
</template>

<script >
  export default {
    data() {
      return {
        msg: 'Hello World!'
      }
    }
  }
</script>

<style scoped>
    ActionBar {
        background-color: #53ba82;
        color: black;
    }

    .message {
        vertical-align: center;
        text-align: center;
        font-size: 20;
        color: red;
    }
</style>
