# bmw
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="main_1.css"> <!-- Add your custom CSS file if needed -->
    <link rel="icon" href="./img/BMW_logo_(gray).png">

    <title>Loading Page...</title>
    <style>
        body {
            background-color: #ffffff; /* White background */
            margin: 0;
            overflow: hidden;
        }

        .loading-container {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Shadow effect */
        }

        .loading-logo {
            max-width: 200px;
            max-height: 200px;
            animation: wave 2s infinite alternate; /* Wave animation */
        }

        @keyframes wave {
            0% {
                transform: translateY(0);
            }
            100% {
                transform: translateY(10px);
            }
        }

        .loading-text {
            opacity: 0;
            animation: fadeIn 2s forwards 2s; /* Fade in after 2 seconds */
        }

        @keyframes fadeIn {
            to {
                opacity: 1;
            }
        }
    </style>
</head>
<body>

<!-- Loading Container -->
<div class="loading-container">
    <img src="./img/BMW_logo_(gray).png" alt="BMW Logo" class="loading-logo">
</div>

<!-- Loading Text -->
<div class="loading-text text-center">
    <h2>Loading...</h2>
</div>

<!-- Bootstrap JS and jQuery (needed for Bootstrap functionality) -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

<script>
    setTimeout(function() {
        window.location.href = "index_1.html"; // Redirect to the next page after a delay
    }, 5000); // Set the delay in milliseconds (5000 = 5 seconds)
</script>

</body>
</html>
