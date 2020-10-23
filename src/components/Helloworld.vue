<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <h1 style = "color:blue; text-align:center">WORLD OF WORK SERVICES COOP</h1>
    <h2>sales</h2>
    <h2>construction management and all engineering</h2>
    <h2>entry level</h2>
    <h2>merit advancement</h2>
    <h2>professional positions based upon experience and education</h2>
    <h2>self-employment can immediately become part of the coop and can make money</h2>
    <h2>employment-work options</h2>
<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Your Role: <select name="role[]" multiple>
      <option value="leader">Leader</option>
      <option value="follower">Follower</option>
    </select></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
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

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
