<template>

  <body class="creamBackground">

    <header>
      <nav class="navbar navbar-dark nav-fill text-white" style="background-color: #000000;">
        <a class="nav-item nav-link text-white" href="#">HOME</a>
        <a class="nav-item nav-link text-white" href="#">ABOUT</a>
        <a class="nav-item nav-link text-white" href="#">MENU</a>
        <a class="nav-item nav-link text-white" href="#">WHERE</a>
      </nav>
    </header>

    <main>

      <section title="about the cafe">
        <div class="bg-image p-5 text-center shadow-1-strong mb-5 text-white"
          style="background-image: url('https://mdbcdn.b-cdn.net/img/new/slides/003.webp');">
          <h1>
            the
          </h1>
          <h1> Cafe</h1>
        </div>

        <div class="row">
          <div class="col text-center">
            <h5 class="sectionTitle px-2 my-5 text-white">ABOUT THE CAFE</h5>
          </div>
        </div>
        <div class="row justify-content-center">
          <p class="col-5 mx-5">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam cupiditate, architecto totam quidem minus
            repellat natus cumque sit pariatur at, reiciendis asperiores perferendis accusantium voluptatum ex officia
            quibusdam ullam eius!
          </p>
        </div>

        <div class="row justify-content-center">
          <p class="col-5 mx-5">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam cupiditate, architecto totam quidem minus
            repellat natus cumque sit par.
          </p>
        </div>

        <div class="row justify-content-center">
          <div class="col-5">
            <div class="p-3 rounded" style="border-left: .25rem solid #adb5bd; background-color: #e9ecef;">
              <p class="font-italic">
                "Use products from nature for what it's worth - but never too early, nor too late." Fresh is the new
                sweet.
              </p>
              <p>
                Chef, Coffeeist and Owner: Liam Brown
              </p>
            </div>
          </div>
        </div>
        <div class="flex-column">
          <div class="row justify-content-center my-4">
            <img class="col-5" src="https://mdbcdn.b-cdn.net/img/new/slides/003.webp" alt="">
          </div>
        </div>

        <div class="row justify-content-center">
          <div class="col-5">
            <p class="mx-5"><strong>Opening hours:</strong> everyday from 6am to 5pm.</p>
          </div>
        </div>

        <div class="row justify-content-center">
          <div class="col-5">
            <p class="mx-5"><strong>Adress:</strong> 15 Adr street, 5015, NY</p>
          </div>
        </div>
      </section>

      <section title="the menu">
        <div class="row">
          <div class="col text-center">
            <h5 class="sectionTitle px-2 my-5 text-white">THE MENU</h5>
          </div>
        </div>

        <div class="row justify-content-center">
          <div class="card col-5 creamBackground">
            <div class="card-header row justify-content-between align-items-center text-center">
              <a href="#" class="col-6 text-decoration-none text-black text-dark">Eat</a>
              <a href="#" class="col-6 text-decoration-none text-white bg-dark">Drink</a>

            </div>

            <div class="card-body">
              <p class="">Coffe</p>
              <small>Regular coffe 2.50</small>
            </div>

            <div class="card-body">
              <p class="">Coffe</p>
              <small>Regular coffe 2.50</small>
            </div>

            <div class="card-body">
              <p class="">Coffe</p>
              <small>Regular coffe 2.50</small>
            </div>

            <div class="card-body">
              <p class="">Coffe</p>
              <small>Regular coffe 2.50</small>
            </div>

            <div class="card-body">
              <p class="">Coffe</p>
              <small>Regular coffe 2.50</small>
            </div>

          </div>
        </div>

        <div class="flex-column">
          <div class="row justify-content-center my-4">
            <img class="col-5" src="https://mdbcdn.b-cdn.net/img/new/slides/003.webp" alt="">
          </div>
        </div>

      </section>

      <section title="Where to find us">
        <div class="row">
          <div class="col">
            <h5 class="sectionTitle px-2 my-5 text-white">WHERE TO FIND US</h5>
          </div>
        </div>
        <div class="row justify-content-center">
          <p class="col-5 mx-5">
            Find us at some address at some place.
          </p>
        </div>

        <div class="flex-column">
          <div class="row justify-content-center my-1">
            <img class="col-5" src="https://mdbcdn.b-cdn.net/img/new/slides/003.webp" alt="">
          </div>
        </div>

        <div class="row justify-content-center">
          <p class="col-5 mx-5">
            <span class="bg-dark text-white px-2">FYI!</span>
            We offer full-service catering for any event, large or small. We understand your needs and we will cater the
            food to satisfy the biggerst criteria of them all, both look and taste.
          </p>
        </div>

        <div class="row justify-content-center">
          <p class="col-5 mx-5">
            <strong>Reserve</strong> a table, ask for today's special or just send us a message:
          </p>
        </div>

        <div class="row justify-content-center">
          <div class="col-5">
  <div class="input-group-prepend">
  </div>

    <form @submit.prevent="forms">

       <input type="text"
class="form-control my-3"
placeholder="Username"
v-model="name"
name="name"
id="name">

  <input type="text"
class="form-control my-3"
placeholder="How many people"
v-model="people"
name="people"
id="people">

  <input type="datetime-local"
class="form-control my-3"
placeholder="Username"
v-model="time"
name="time"
id="time">

  <input type="text"
class="form-control my-3"
placeholder="Message \ Special requirements"
v-model="message"
name="message"
id="message">

    <button type="submit" value="submit">Send</button>
      </form>

</div>

        </div>
      </section>

    </main>

<footer class="footerBackground mt-5">
  <div class="d-flex align-items-center justify-content-center pt-4">
    <p> Powered by <u>w3.css</u></p>
  </div>
</footer>

  </body>
</template>

<script>
export default {
  name: 'IndexPage',
  data () {
    return {
      name: '',
      people: '',
      time: '',
      message: ''
    }
  },
  methods: {
    forms () {
      this.$axios({
        method: 'post',
        url: 'https://www.cantacom.com.br/email/store.php',
        data: {
          name: this.name,
          people: this.people,
          time: this.time,
          message: this.message
        }
      })
    // add a .then() and a .catch() here to deal with response.
    }
  }
}
</script>

<style>
html, body {
    overflow-x: hidden;
}

.footerBackground {
  background-color: #F1F1F1;
}

.creamBackground {
  background-color: #F7F5F2;
}
a {
  text-decoration: none;
}

</style>

<style scoped>
.sectionTitle {
  background-color: #000000;
  max-width: max-content;
  margin: 0 auto;
}
</style>
