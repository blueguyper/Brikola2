<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">


  <style>
    /* Body background setup */
    body {
      margin: 0;
      height: 100vh;
      background: url('file_00000000358861f9aa0782508db6f677_2.png') center/cover no-repeat;
      font-family: 'Poppins', sans-serif;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
      overflow: hidden;
    }

    /* Dark overlay for readability */
    body::before {
      content: "";
      position: absolute;
      inset: 0;
      background: rgba(0, 0, 0, 0.55);
      backdrop-filter: blur(4px);
      z-index: 0;
    }

    /* Animated heading */
    h1 {
      position: relative;
      z-index: 1;
      font-size: 3em;
      letter-spacing: 2px;
      text-transform: uppercase;
      animation: fadeIn 2s ease-out, float 4s ease-in-out infinite alternate;
      text-shadow: 0 4px 15px rgba(0, 0, 0, 0.8);
    }

    /* Fade-in effect */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* Floating subtle animation */
    @keyframes float {
      from { transform: translateY(0px); }
      to { transform: translateY(-10px); }
    }
  </style>
</head>

<body>
  <h1>Test</h1>
</body>
</html>
