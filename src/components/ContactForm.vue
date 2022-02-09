<template>
  <div class="container">
      <form>
        <div class="row pb-4">
            <div class="col-6">
                <label class="form-label text-uppercase">First Name</label>
                <input type="text" class="form-control p-4 rounded-pill" value="" />
            </div>
            <div class="col-6">
                <label class="form-label text-uppercase">Last Name</label>
                <input type="text" class="form-control p-4 rounded-pill" value="" />
            </div>
        </div>
        <div class="row pb-4">
            <div class="col-6">
                <label class="form-label text-uppercase">Email</label>
                <input type="text" class="form-control p-4 rounded-pill" value="" />
            </div>
            <div class="col-6">
                <label class="form-label text-uppercase">Phone</label>
                <input type="text" class="form-control p-4 rounded-pill" value="" />
            </div>
        </div>
        <div class="row pb-4">
            <div class="col-12">
                <label class="form-label text-uppercase">Message</label>
                <textarea class="form-control p-4 rounded-3" rows="3"></textarea>
            </div>
        </div>
        <div class="row pb-5">
            <div class="col-12">
                <button type="button" class="btn-submit">Submit</button>
            </div>
        </div>
      </form>
  </div>
</template>

<script>

export default {
  name: 'contact-form',
  data() {
    return {
      
    }
  }
}
</script>
<style>
.btn-submit {
    border: 0;
    background-color: #f26725;
    border-radius: 10px;
    color: #fff;
    font-weight: bold;
    padding: 10px;
    width: 25%;
    opacity: 0.6;
    transition: 0.3s;
}
.btn-submit:hover {
    opacity: 1;
}
</style>