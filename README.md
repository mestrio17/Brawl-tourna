<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grind Tournament</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 min-h-screen p-6">
    <nav class="mb-4">
        <a href="#home" class="mr-4">Home</a>
        <a href="#tournaments">Tournaments</a>
    </nav>

    <section id="home" class="p-4">
        <h1 class="text-xl font-bold">Grind Tournament</h1>
        <p class="text-gray-600">Compete and win cash prizes!</p>
        <a href="#tournaments" class="mt-4 inline-block bg-blue-500 text-white px-4 py-2 rounded">View Tournaments</a>
    </section>

    <section id="tournaments" class="p-4">
        <h2 class="text-lg font-bold">Upcoming Tournaments</h2>
        <div class="mt-4 bg-white p-4 rounded-lg shadow">
            <h3 class="text-md font-semibold">Battle Royale Showdown</h3>
            <p class="text-sm text-gray-500">Win up to $1000!</p>
            <button class="mt-2 bg-green-500 text-white px-4 py-2 rounded">Join Now</button>
        </div>
    </section>
</body>
</html>
