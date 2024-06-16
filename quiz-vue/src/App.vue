<template>
  <main>
    <header>
      <h1 id="title">QuizVue</h1>
      <input type="text" id="search-input" />
    </header>
    <section id="quiz-container">
      <div class="card">
        <img
          src="https://plus.unsplash.com/premium_photo-1678565999588-08fdd0b1410b?w=1000&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8cHJvZ3JhbW1pbmd8ZW58MHx8MHx8fDA%3D"
          alt=""
        />
        <div class="card-body">
          <h2>Programming</h2>
          <p>2 Questions</p>
        </div>
      </div>
    </section>
  </main>
</template>

<style scoped>
main {
  max-width: 900px;
  margin: 0 auto;
}

header {
  margin-top: 30px;
  margin-bottom: 10px;
  display: flex;
  align-items: center;
}

#title {
  font-weight: bold;
  margin-right: 30px;
}

#search-input {
  border: none;
  background-color: #c9c9c9a9;
  padding: 10px;
  border-radius: 5px;
}

#quiz-container {
  display: flex;
  flex-wrap: wrap;
  margin-top: 20px;
}

.card {
  width: 270px;
  margin-right: 30px;
  margin-bottom: 30px;
  border-radius: 5px;
  overflow: hidden;
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
}

.card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  margin: 0;
}

.card-body {
  padding: 0 15px;
}

.card-body h2 {
  font-weight: bold;
}
</style>
