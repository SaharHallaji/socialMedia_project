<script setup lang="ts">
import Tweets from "../components/Tweets.vue"

let tweets = [{
  name: "Steve Schogere",
  username: "Steve_Schoger",
  date: "Jun 27",
  tweet: "🔥 If you're tired of using outline styles for secondary buttons, a soft solid background based on the text color can be a great alternative.",
  comments:33,
  retweets : 96,
  likes: 2600
}]

</script>

<template>
  <main>
    <Tweets :tweet="tweets[0]"/>
  </main>
</template>
