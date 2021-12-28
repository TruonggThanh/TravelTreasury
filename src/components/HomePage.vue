<template>
 <div class="container-fluid m-0 p-0">

    <div id="home-page" class="full-height p-4">
        <div class="container pt-3">
            <div class="row pb-5">
                <div class="col-lg-6 my-auto">
                    <div class="text-center mb-3 d-block d-lg-none">
                        <h1 class="display-3">{{title}}</h1>
                        <h3>Find the world</h3>
                    </div>
                   <img id="iphone-img" src="../assets/travelTreasuryiPhone.png" class="img-fluid" />
                </div>
                <div class="col-lg-6">
                    <div class="text-center mb-3 d-none d-lg-block">
                       <h1 class="display-3">{{title}}</h1>
                       <h3>Find the world</h3>
                    </div>
                    <div class="border p-3 p-md-5 bg-white rounded shadow">
                        <h2>Comeming Soon</h2>
                        <form>
                            <div class="form-group">
                                <label for="emailSignup">Reserve your account now, we'll cotact you when it's live</label>
                                <input id="emailSignup" 
                                       placeholder="Enter Email" 
                                       class="form-control"
                                />
                                <div id="emailHelp" class="form-text text-muted">We'll never share your email address</div>
                                <button type="submit" class="btn btn-success mt-3">Join Waiting List</button>
                            </div>
                        </form>
                    </div>
                    <div id="available" class="p-2">
                        <div class="text-center mb-2 mt-3 text-light">
                            Available On
                        </div>
                        <div class="row">
                            <div class="col my-auto">
                                <img src="../assets/download_apple.png" class="float-right img-fluid app_store_img"/>
                            </div>
                            <div class="col my-auto">
                                <img src="../assets/download_google.png" class="float-left img-fluid app_store_img" />
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div id="about" class="bg-light p-3 p-md-5">
        <div class="row">
            <div class="col-lg">
                <img src="../assets/icons/app.svg" height="120" class="m-4">
                <h5 class="ml-md-4 mr-md-4">
                   Plan your next adventure by setting a daily spending budget. We make it easy to break your expenses down by category, giving you more time to plan the important tings!
                </h5>
            </div>
            <div class="col-lg">
                <img src="../assets/icons/piggy-bank.svg" height="120" class="m-4">
                <h5 class="ml-md-4 mr-md-4">
                    Use the app to track how much money you've saved towards your trips total budgeted goal. Know exactly how much more you need to save, and how much tive you have left to save.
                </h5>
            </div>
            <div class="col-lg">
                <img src="../assets/icons/passport.svg" height="120" class="m-4">
                <h5 class="ml-md-4 mr-md-4">
                    When the day of your trip comes, have the peace of mind that you planned out your expenses. Nerver worry about money on a trip again.
                </h5>
            </div>
        </div>
    </div>

    <div id="contact" class="bg-info p-4">
        <div class="row justify-content-center mt-3 mb-3">
            <div class="col-lg-4">
                <h2>Have Any Questions?</h2>
                <p>Contact us by filling out the information below</p>
                <form>
                    <div class="form-group text-left">
                        <input type="email"
                               class="form-control"
                               placeholder="Enter Your Email"
                        >
                        <textarea class="form-control mt-3"
                                  placeholder="Enter Your Message"
                                  rows="5"
                        >
                        </textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Send Message</button>
                </form>
            </div>
        </div>
    </div>
   
    <div id="footer" class="bg-primary p-4">
        <footer class="text-light p-4">
            <a href="" target="_blank" class="text-warning">Build This App</a>
            <a href="#" class="text-warning">Privacy Policy</a>
            <br>
            <small>&copy; 2020, TravelTreasury.app</small>
        </footer>
    </div>
 </div>
</template>

<script>
export default {
  name: 'HomePage',
  data() {
      return {
          title: 'Travel Treasury'
      }
  }
}
</script>

<style scoped>
#home-page {
    background: url('../assets/bg_mt.jpg') no-repeat center center;
    background-size: cover;
}

#about {
    min-height: 40vh;
}

#contact {
    background-color: #57AEAF;
}

#iphone-img {
    max-height: 80vh;
}

.app_store_img {
    max-height: 80px;
}
</style>
