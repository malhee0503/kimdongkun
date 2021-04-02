<template>
  <div id="app">
    <TooHeader />
    <TooTitle />
    <TooInput />
    <TooController />
    <TooList />
    <TooFooter />
  </div>
</template>
 
<script>
import TooHeader from "./components/TooHeader";
import TooTitle from "./components/TooTitle";
import TooInput from "./components/TooInput";
import TooController from "./components/TooController";
import TooList from "./components/TooList";
import TooFooter from "./components/TooFooter";
 
export default {
  name: "App",
  components: {
    TooHeader,
    TooTitle,
    TooInput,
    TooController,
    TooList,
    TooFooter
  }
};
</script>
