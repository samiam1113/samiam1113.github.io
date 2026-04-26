<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Application 6</title>
  <style>

    body {
      /* Center all content */
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;

      /* Background image */
      background-image: url('https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.old-games.com%2Fscreenshot%2F6886-2-rollercoaster-tycoon-2.jpg&f=1&nofb=1&ipt=c4509a3c0f3dcfa39a2d0f4153fcde92d80f0255412649fd973fa438d0e000c2');
      background-size: cover;       /* fills the whole screen */
      background-position: center;  /* keeps it centered */
      background-attachment: fixed; /* parallax-like effect */

      /* Fallback color if image doesn't load */
      background-color: #1a1a2e;

      min-height: 100vh;
      margin: 0;
      padding: 40px 20px;

      /* Text styling */
      font-family: Arial, sans-serif;
      color: white;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.1rem;
      max-width: 600px;
      margin-bottom: 30px;
    }

    /* Responsive video */
    .video-container {
      position: relative;
      padding-bottom: 56.25%;
      height: 0;
      width: 100%;
      max-width: 800px;
    }

    .video-container iframe {
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      border-radius: 10px;
    }

  </style>
</head>
<body>

  <h1>Rollercoaster Control System</h1>
  <p>My dream job is to create ride control software for a theme park in Orlando. This design is a simple ride control system 
that monitors critical ride information. Built for a rollercoaster, this design monitors if a train is in the critical zone, 
and if the e-stop button has been pressed. The e-stop button can be reset, and the system monitors for overall health of the ride. 
Systems like these are incredibly important. Ride conditions need to be closely monitored in the case that anything goes wrong, 
failure of this hard real-time system could result in serious injury, and it is important that functions like the e-stop are deterministic.</p>

  <iframe
    width="560"
    height="315"
    src="https://youtu.be/KaH8Oey2f7I"
    title="Rollercoaster Control System Demo Video"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>

</body>
</html>
