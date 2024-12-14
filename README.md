<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Refer & Earn</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css"
    />
    <link
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css"
      rel="stylesheet"
    />
    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        text-align: center;
        background: linear-gradient(lightblue, white);
    }

      .container {
        padding: 20px;
      }

      h1 {
        font-size: 2.5rem;
        color: white;
        margin-bottom: 20px;
      }

      .refer-section {
        display: flex;
        /* align-items: center; */
        justify-content: space-evenly;
        /* margin: auto; */
        /* margin-bottom: 20px; */
      }
      .img1 {
        position: absolute;
        left: 400px;
      }
      .img2 {
        position: relative;
      }

      .refer-section img {
        width: 80px;
        height: 80px;
        border-radius: 50%;
        margin: 0 10px;
      }

      .refer-section span {
        font-size: 1.2rem;
        font-weight: bold;
        color: black;
      }

      .code-container {
        width: 100%;
        height: 100%;
        background-color: #f9f9f9;
        border: 1px solid #ddd;
        border-radius: 8px;
        padding: 10px;
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      }

      .code-container p {
        font-size: 1rem;
        color: red;
      }

      .code-container .referral-code {
        font-size: 1.2rem;
        font-weight: bold;
        color: black;
        margin-bottom: 10px;
        /* border: 1px solid gray ; */
        background-color: lightgrey;
      }

      .btn {
        display: inline-block;
        padding: 10px 20px;
        color: white;
        font-size: 15px;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        text-decoration: none;
        margin-top: 10px;
      }

      .btn:hover {
        background-color: #0056b3;
      }

      .btn-whatsapp {
        background-color: #25d366;
      }

      .btn-whatsapp:hover {
        background-color: #1da955;
      }
      .more-button {
        padding: 1px 20px;
        text-align: center;
        border-radius: 50px;
        margin-left: 410px;
      }
      footer{
        margin-top: 150px;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <h1>Refer & Earn</h1>
      <div class="refer-section">
        <img
          src="/DesawarBazar-main/public/images/man-phone.png"
          alt="Refer a Friend"
          class="img1"
        />

        <span>
          <i class="fa-solid fa-arrow-right fa-2x my-4"></i>
        </span>

        <img
          src="/DesawarBazar-main/public/images/commission-icon.png"
          alt="Commission"
          class="img2"
        />
      </div>
      <div class="img-content d-flex justify-content-evenly">
        <span class="text-dark"><strong>Refer a Friend</strong></span>
        <span> <strong>3% commission lifetime for each Game Play</strong></span>
      </div>
      <button class="btn btn-danger more-button">More?</button>

      <div class="code-container mt-2">
        <span class="text-dark d-flex align-items-start">Referal Code</span>

        <div class="d-flex justify-content-center align-items-center">
          <div
            class="referral-code text-center form-control me-2"
            style="width: 75%; overflow: hidden"
          >
            25806RIG
          </div>
          <button class="btn btn-primary mb-4" onclick="copyCode()">
            COPY
          </button>
        </div>
        <p class="commission text-uppercase">
          Copy or share your referral code with friends
        </p>
        <a
          href="https://wa.me/?text=Join%20and%20earn%20with%20my%20referral%20code:%2025806RIG"
          class="btn btn-whatsapp"
        >
          <i class="fa-brands fa-whatsapp me-1"></i>SHARE VIA WHATSAPP</a
        >
        <div class="question">
          <h5 class="text-danger d-flex align-items-start ms-5">
            How to refer a friend?
          </h5>
         
          <div class="text-dark">
            <div class="d-flex align-items-start ms-4">
              1.Copy the referal code and share it with your friend.
            </div>
            <div class="d-flex align-items-start ms-4">
              2.Ask your friend to register on Desawar Bazar App using the
              referal code.
            </div>
          </div>
        </div>
      </div>
    </div>
    <footer>
      <h4 class="text-dark d-flex align-items-start ms-4">All Links</h4>
      <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid">
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="#">HOME</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">STATEMENT</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">RESULT & RULES</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">HELP</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">PROFILE</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">REFER & EARN</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">PRIVACY POLICY</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">TERMS & CONDITION</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </footer>
    <script>
      function copyCode() {
        const code = "25806RIG";
        navigator.clipboard
          .writeText(code)
          .then(() => {
            alert("Referral code copied to clipboard!");
          })
          .catch((err) => {
            alert("Failed to copy referral code.");
          });
      }
    </script>
  </body>
</html>
# Refer-Earn-Page
