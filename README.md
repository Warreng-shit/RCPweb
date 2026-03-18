
<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <title>Log In Form</title>
    <style>
        body {
            background-color: grey;
        }

        @media only screen and (orientation: landscape) {
            body {
                background: linear-gradient(to right, #bdc3c7, #2c3e50)
            }
        }


        .container {
            background-color: rgb(180, 154, 154);
            border-radius: 15px;
            color: beige;
            padding: 25px;
            width: 600px;
            border: 1px solid black;
            margin: auto;
        }

        fieldset {
            padding: 4;
            margin-bottom: 4;

        }

        body h6 {
            margin-top: 10px;
        }

        .A {
            padding-top: 50px;
        }

        .hp {
            font-family: 'Inter', 'Open Sans', Arial, sans-serif;
        }
    </style>
</head>

<body class="example">
    <div class="A">
        <div class="container">
            <form action="RCP.html">
                <fieldset>
                    <div class="hp">
                        <label for="Email"> Email Address</label>
                        <input type="email" class="form-control" id="Email" placeholder="Email Address"><br>
                        <label for="password"> Password</label>
                        <input type="password" class="form-control" id="password" placeholder="Password"><br>
                        <input type="checkbox" id="checkbox">
                        <label for="checkbox">Remember Me</label><br><br>
                    </div>
                    <div class="row">
                        <div class="col">
                            <button onclick="window.location.href='ind'"
                                class="btn btn-success">Submit</button>
                        </div>
                        <div class="col">
                            <h6><a href="2 Sign up.html">Create Account</a></h6>
                        </div>
                    </div>
                </fieldset>
            </form>
        </div>
    </div>
</body>

</html>
