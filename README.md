<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>OBMC Contact Us</title>
    <link rel="stylesheet" href="styles.css">
    <style>
      body {
        background-image: url(https://obmontessori.orangeapps.ph/landing/obmontessori/images/Las%20Pinas%20Facade.jpg);
      }
    </style>
    <!-- BOOTSTRAP-CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
    
    <!-- BOOTSTRAP-JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js" integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI" crossorigin="anonymous"></script>  

  </head>

<body>
  <nav class="navbar navbar-expand-sm bg-dark navbar-dark">
    <div class="container-fluid">
            <a class="navbar-brand" href="#">
                <img src="OBMC%20LOGO%202024-Circle.png" alt="logo" height="50px" width="50px" class="rounded-pill"> OB MONTESSORI CENTER
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#mynavbar">
                <span class="navbar-toggler-icon"></span>
            </button>   

            <div class="collapse navbar-collapse" id="collapsibleNavbar">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    
                    
                    <li class="nav-item"><a class="nav-link" href="#contact-section">Contact Us</a></li>

                </ul>
                <form class="d-flex">
                    <input class="form-control me-2" type="text" placeholder="Search">
                    <button class="btn btn-primary" type="button">Search</button>
                    </form>
            </div>
    </div>
  </nav>


  <div class="container p-3 mt-5">
    <div class="row">
      <!-- TABLE -->
        <div class="col-12 col-md-6 col-lg-6">
          <h3> School Office Hours </h3><hr>            
          <table class="table table-striped table-bordered">
          <thead>
            <tr class="bg secondary text-light">
            
            <tr>
              <th>Day</th>
              <th>Office Hours</th>
              <th>Department</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>Monday</td>
              <td>8:00AM-4:00PM</td>
              <td>Registrar's Office</td>
            </tr>
            <tr>
              <td>Tuesday</td>
              <td>8:00AM-4:00PM</td>
              <td>Accounting Office</td>
            </tr>
            <tr>
              <td>Wednesday</td>
              <td>8:00AM-4:00PM</td>
              <td>Guidance Office</td>
            </tr>
            <tr>
              <td>Thursday</td>
              <td>8:00AM-4:00PM</td>
              <td>Principal's Office</td>
            </tr>
            <tr>
              <td>Friday</td>
              <td>8:00AM-3:00PM</td>
              <td>Admin Office</td>
            </tr>
          </tbody>
          </table>
        </div>

        <!-- FORM -->
        <div class="col-12 col-md-5 col-lg-5">
          <h3>Contact Us</h3><hr>
          <div class="container-fluid mt-3 p-3">
          <form class="bg-light ">
          <!--Full Name-->
          <div class="mb-3">
            <label for="Full Name" class="form-label">Full Name</label>
            <input type="fn" class="form-control" id="Flname" aria-describedby="name">
            <div id="name" class="form-text"></div>
          </div>

          <!--Email-->
          <div class="mb-3">
            <label for="Email" class="form-label">Email</label>
            <input type="email" class="form-control" id="email">
          </div>

          <!-- Subject-->
          <div class="mb-3">
            <label for="Subject" class="form-label">Subject</label>
            <input type="sub" class="form-control" id="subject">
          </div>

          <!-- Message-->
          <div class="mb-3">
            <label for="Message" class="form-label">Message</label>
            <textarea class="form-control" id="msg" rows="3"></textarea>
          </div>
          <!-- Submit-->
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
        </div>

    </div>
  </div>


<footer class="text-center py-3 bg-dark text-light mt-auto fixed-bottom">
    &copy; 2025 Copyright | Jacob Kyan M. Mendoza| 9-Sapphire
</footer>

</body>
</html>
