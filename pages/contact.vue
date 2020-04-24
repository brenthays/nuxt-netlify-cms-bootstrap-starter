<template>
  <div class="container py-5">
    <h1 class="mb-3">Contact</h1>
    <p>Contact form using <a href="https://formsubmit.io" target="_blank">
      FormSubmit.io</a></p>
    <!-- Contact Form Using FormSubmit -->
    <b-form class="contact-form" action="https://formsubmit.co/your@email.com" method="post">
      <input
        type="hidden"
        name="_template"
        value="box"
        />
      <b-form-group
        id="input-group-1"
        label="Email *"
        label-for="input-1"
        description="We'll never share your email with anyone else."
      >
        <b-form-input
          id="input-1"
          name="email"
          type="email"
          required
          placeholder="Your email"
        ></b-form-input>
      </b-form-group>

      <b-form-group id="input-group-2" label="Name *" label-for="input-2">
        <b-form-input
          id="input-2"
          name="name"
          required
          placeholder="Your name"
        ></b-form-input>
      </b-form-group>

      <b-form-group id="input-group-3" label="Comments / Questions" label-for="input-3">
        <b-form-textarea
          id="input-3"
          name="comments"
        ></b-form-textarea>
      </b-form-group>

      <b-button type="submit" variant="primary" size="lg">Submit</b-button>
    </b-form>
  </div>
</template>

<style lang="scss" scoped>
.contact-form {
  max-width: 600px;
}
</style>
