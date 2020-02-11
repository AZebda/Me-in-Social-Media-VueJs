<template>
  <div >
    <div id="name">{{ name }}</div>
    <div id="role">{{ role }}</div>
    <ul>
			<li>
				<a class="sociallink linkedin" title="LinkedIn" href="https://www.linkedin.com/in/zebda-ahlem-281567153/" target="_blank">
          <img width="20" height="20" alt="Vue logo" src="../assets/linkedin.png">
				</a>
			</li>
			<li>
				<a class="sociallink github" title="Github" href="https://github.com/AZebda" target="_blank">
					<img width="20" height="20" alt="Vue logo" src="../assets/github.png">
				</a>
			</li>
			<li>
				<a class="sociallink facebook" title="Facebook" href="https://www.facebook.com/ah.leem.12" target="_blank">
					<img width="20" height="20" alt="Vue logo" src="../assets/facebook.png">
				</a>
			</li>
			<li>
				<a class="sociallink twitter" title="twitter" href="https://twitter.com/ZebdaAhlem" target="_blank">
					<img width="20" height="20" alt="Vue logo" src="../assets/twitter.png">
				</a>
			</li>
			<li>
				<a class="sociallink instagram" title="Instagram" href="https://www.instagram.com/ahlem_zebda/" target="_blank">
					<img width="20" height="20" alt="Vue logo" src="../assets/instagram.png">
				</a>
			</li>
      <li>
				<a class="sociallink instagram" title="Instagram" href="https://medium.com/@ahlem.zebda1" target="_blank">
					<img width="20" height="20" alt="Vue logo" src="../assets/medium.png">
				</a>
			</li>
		</ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    name: String,
    role: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
#name {
  font: 100 30px/3em 'Lato', Georgia;
  line-height: 26pt;
}
#role {
  font: 50 15px/1.4em 'Lato', Georgia;
  margin-left: 90px;
}
</style>
