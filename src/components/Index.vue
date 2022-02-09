<template>
  <div>
    <menu-bar />
    <div class="container">
      <div class="row">
        <div class="col-12">
          <nav aria-label="breadcrumb">
            <ol class="breadcrumb bg-transparent">
                <li class="breadcrumb-item"><a href="#">Breadcrumb</a></li>
                <li class="breadcrumb-item"><a href="#">Breadcrumb</a></li>
                <li class="breadcrumb-item active" aria-current="page">Breadcrumb</li>
            </ol>
          </nav>
        </div>
      </div>
      <div class="row p-5">
        <div class="col-12 pb-4">
          <h1 class="text-uppercase">Contact US</h1>
          <h5 class="text-uppercase text-secondary">Our Contact Details</h5>
        </div>
        <div class="col-md-6 p-5 bg-light">
          <table class="col-12">
            <tr>
              <td>
                <i class="fas fa-phone fa-2x"></i>
              </td>
              <td>
                <h5>1300 061 811</h5>
              </td>
            </tr>
          </table>
        </div>
        <div class="col-md-6 p-5 bg-light">
          <table class="col-12">
            <tr>
              <td class="align-top">
                <i class="far fa-building fa-2x"></i>
              </td>
              <td>
                  <h5>
                    Level 7, 60 Light Square
                    <br />
                    Adelaide, South Australia 5000
                    <br />
                    Austrailia
                  </h5>
              </td>
            </tr>
          </table>
        </div>
      </div>
      <contact-form />
    </div>
  </div>
</template>
<script>
import MenuBar from "./MenuBar.vue";
import ContactForm from "./ContactForm.vue";
export default {
  name: "index",
  components: {
    MenuBar, ContactForm,
  },
  data: function() {
    return {
    }
  },
};
</script>