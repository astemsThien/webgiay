<script>
    
</script>

<div class="container">

    <div class="row">

      <div class="col-lg">

        <!-- <h1>Thông tin người nhận <a href="https://bootstrapious.com">Võ Đức Tính</a></h1>

        <p class="lead">This is a demo for our tutorial dedicated to crafting working <a href="https://bootstrapious.com/p/how-to-build-a-working-bootstrap-contact-form">Bootstrap contact form with PHP and AJAX</a>. </p>
        <p>This pen shows how to make a basic Bootstrap and HTML contact form, activate a validator and send it via AJAX. It also displays a custom Bootstrap alert after submitting the form.</p>
        <p>PHP files are not included in this Pen, just visit the tutorial page to download them.</p> -->

        <form id="contact-form" method="post" action="contact.php" role="form">

        <div class="messages"></div>

        <div class="controls">

          <div class="row">
            <div class="col-md-6">
              <div class="form-group">
                <label for="form_name">Firstname *</label>
                <input id="form_name" type="text" name="name" class="form-control" placeholder="Please enter your firstname *"  data-error="Firstname is required.">
                <div class="help-block with-errors"></div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="form-group">
                <label for="form_lastname">Lastname *</label>
                <input id="form_lastname" type="text" name="surname" class="form-control" placeholder="Please enter your lastname *" data-error="Lastname is required.">
                <div class="help-block with-errors"></div>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-md-6">
              <div class="form-group">
                <label for="form_email">Email *</label>
                <input id="form_email" type="email" name="email" class="form-control" placeholder="Please enter your email *"  data-error="Valid email is required.">
                <div class="help-block with-errors"></div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="form-group">
                <label for="form_phone">Phone</label>
                <input id="form_phone" type="tel" name="phone" class="form-control" placeholder="Please enter your phone">
                <div class="help-block with-errors"></div>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-md-12">
              <div class="form-group">
                <label for="form_message">Message *</label>
                <textarea id="form_message" name="message" class="form-control" placeholder="Message for me *" rows="4"  data-error="Please,leave us a message."></textarea>
                <div class="help-block with-errors"></div>
              </div>
            </div>
            <div class="col-md-12">
              <input type="submit" class="btn btn-success btn-send" value="Send message">
            </div>
          </div>
          <div class="row">
            <div class="col-md-12">
              <p class="text-muted"><strong>*</strong> These fields are required. Contact form template by <a href="https://bootstrapious.com" target="_blank">Bootstrapious</a>.</p>
            </div>
          </div>
        </div>

        </form>

      </div>

    </div>

  </div>

<style>
    .container{
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
    }
</style>