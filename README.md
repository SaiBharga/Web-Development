<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport" content="width=device-width,initial-scale=1">
        <title>
            Welcome | Aqgromalin Farmtech Services Private Limited
        </title>
        <link rel="stylesheet" href="css/bootstrap.min.css">
        <link rel="stylesheet" href="https://use.fontawesome.com/release/v5.11.2/css/all.css">
        <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap"/>
        <link rel="stylesheet" href="css/common.css">
    </head>
    <body>
        <div class="header sticky-top">
            <nav class="navbar navbar-expand-md navbar-light">
                <a class="navbar-brand" href="index.html">
                </a>
                <button class="navbar-toggler" type="button" data-toggle=" collapse" data-target="#my-navbar">
                    <span class="navbar-toggler-icon" ></span>
                </button>

                <div class="collapse navbar-collapse justify-content-end " id="my-navbar">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link" href="#" data-toggle="modal" data-target="#signup-modal">
                                <i class="fas fa-user"></i>signup
                            </a>
                        </li>
                        <div class="nav-vl"></div>
                        <li class="nav-item">
                            <a class="nav-link" href="#" data-toggle="modal" data-target="#login-modal">
                                <i class="fas fa-sign-in-alt"></i>Login
                            </a>
                        </li>
                    </ul>
                </div>
            </nav>
        </div>

        <div id="loading"></div>

        <div class="modal fade" id="signup-modal" tabindex="-1" role="dialog" aria-labelledby="signup-heading" aria-hidden="true">
            <div class="modal-dialog" role="document">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title" id="signup-heading">Signup with Aqgromalin Farmtech Services Private Limited</h5>
                        <button type="button" class="close" data-dismiss="modal" aria-label="close">
                            <span aria-hidden="true">&times;</span>
                        </button>
                    </div>

                <div class="modal-body">
                    <form id="signup-form" class="form" role="form">
                        <div class="input-group form-group">
                            <div class="input-group-prepend">
                                <span class="input-group-text">
                                    <i class="fas fa-user"></i>
                                </span>
                            </div>
                            <input type="text" class="form-control" name="full-name" placeholder="Full name" maxlength="30" required>
                        </div>

                         <div class="input-group form-group">
                             <div class="input-group-prepend">
                                 <span class="input-group-text">
                                     <i class="fas fa-phone-alt"></i>
                                 </span>
                            </div>
                            <input type="text" class="form-control" name="phone" placeholder="Phone" maxlength="10" minlength="10" required>
                        </div>

                        <div class="input-group form-group">
                            <div class="input-group-prepend">
                                <span class="input-group-text">
                                   <i class="fas fa-envelop"></i>
                                </span>
                             </div>
                            <input type="text" class="form-control" name="email" placeholder="Email" required>
                        </div>

                        <div class="input-group form-group">
                            <div class="input-group-prepend">
                                <span class="input-group-text">
                                    <i class="fas fa-lock"></i>
                                </span>
                            </div>
                            <input type="text" class="form-control" name="password" placeholder="Password" minlength="6" required>
                        </div>

                        <div class="form-group">
                            <span >I'm a</span>
                            <input type="radio" class="m1-3" id="gender-male" name="gender" value="male"/>
                            <label for="gender-male">Male</label>
                            <input type="radio" class="m1-3" id="gender-female" name="gender" value="female"/>
                            <label for="gender-female">Female</label>
                        </div>

                       <div class="form-group">
                           <button type="submit" class="btn btn-block btn-primary">
                               Create Account
                           </button>
                       </div>
                    </form>
                </div>

                <div class="modal-footer">
                    <span>Already have an account?</span>
                    <a href="#" data-dismiss="modal" data-toggle="modal" data-target="#login-modal">Login</a>
                </div>
            </div>
        </div>
    </div>

    <div class="modal-fade" id="login-modal" tabindex="-1" role="dialog" aria-labelledby="login-heading" aria-hidden="true">
        <div class="modal-dialog modal-dialog-centered" role="document">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="login-heading">Login</h5>
                    <button  type="button" class="close" data-dismiss="modal" aria-label="close">
                        <span aria-hidden="true">&times;</span>
                    </button>
                </div>

                <div class="modal-body">
                    <form id="login-form" class="form" role="form">
                        <div class="input-group form-group">
                            <div class="input-group-prepend">
                                <span class="input-group-text">
                                    <i class="fas fa-user"></i>
                                </span>
                            </div>
                            <input type="email" class="form-control" name="email" placeholder="Email" required>
                        </div>

                        <div class="input-group form-group">
                            <div class="input-group-prepend">
                                <span class="input-group-text">
                                    <i class="fas fa-lock"></i>
                                </span>
                            </div>
                            <input type="password" class="form-control" name="password" placeholder="Password" required>
                        </div>

                        <div class="form-group">
                            <button type="submit" class="btn btn-block btn-primary">Login</button>
                        </div>
                    </form>
                </div>

                <div class="modal-footer">
                    <span>
                        <a href="#" data-dismiss="modal" data-toggle="modal" data-target="#signup-modal">Click here</a>to register a new account
                    </span>
                </div>
            </div>
        </div>

        <script type="text/javascript" src="js/jquery.js"></script>
        <script type="text/javascript" src="js/bootstrap.min.js"></script>
        <script crossorigin src="https://unpkg.com/react@16/umd/react.development.js"></script>
        <script crossorigin src="https://unpkg.com/react-dom@16/umd/react.development.js"></script>
        
    </body>
</html>
