<template>
   
     <div class="home">
      <main id="main-content">
        <p class="text-center intro">Ten Ton Coffee offers locally roasted coffee and house-made baked goods, located on Main Street in the historic city of Waitsburg, Washington.</p>
          <div class="row">
            <!-- IMAGE ZOOM -->
            <article class="col-md-6 col-lg-6 mb-5">
              <div class="image-wrapper img-fluid">
                <img class="img-fluid w-100" src="/images/ten-ton-owners.jpeg" width="500" height="500">
              </div>
              <div class="text-center bg-white p-4">
                <h4>Grab a warm drink and a tasty treat</h4>
                <p>With exceptional espresso, pastries baked from scratch, gluten-free options, house-made granola, and delicious panini, Ten Ton Coffee has what you crave</p>
              </div>
            </article>
            <article class="col-md-6 col-lg-6 mb-5">
              <div class="image-wrapper">
                <img class="img-fluid w-100" src="/images/ten-ton-mask.jpg" width="500" height="500">
              </div>
              <div class="text-center bg-white p-4">
                <h4>We're open!</h4>
                <p>Our fabulous take-out window is open daily, 7:30am - 2pm. Come grab a coffee and say hello!</p>
              </div>
            </article>
          </div>
      </main>
    </div>

    <!--<HomePage />-->
 
</template>

<script>

export default {
  name: 'Home',
  data () {
    return {
      title: 'Ten Ton Coffee - Home',
    }
  },
  head () {
      return {
        title: this.title,
        meta: [
          // hid is used as unique identifier. Do not use `vmid` for it as it will not work
          {
            hid: 'description',
            name: 'description',
            content: 'Ten Ton Coffee - Home'
          }
        ]
      }
    }
}
</script>
