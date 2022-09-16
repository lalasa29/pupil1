<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com"></script>
    <title>FORM</title>

</head>
<div>

<body style="background-color:rgb(98, 228, 120)"> 
     
        <div
            class="relative bg-white px-6 pt-5 pb-5 shadow-xl ring-1 ring-gray-900/5 sm:mx-auto sm:max-w-lg sm:rounded-lg sm:px-10">
            <div class="mx-auto max-w-md">
                <h2 class="text-3xl text-center font-bold leading-tight">
                   
                    <h1 style="background-color:rgb(98, 228, 120);">FORM REGISTRATION</h1>
                </h2>
                <div class="divide-y divide-gray-300/50">
                    <div class="space-y-6 py-8 text-base leading-7 text-gray-600">
                        <form id="FORM">
                            <label for="name" class="text-md w-40 inline-block font-medium leading-5 text-gray-700">
                                <h1 style="background-color:rgb(98, 228, 120);">Name of user</h1>
                            </label>
                            <input required type="text" id="name of user" name="name of the user" class="bg-gray-100 inline-block rounded-lg shadow-md px-4 py-3 mb-5 text-base leading-6 placeholder-gray-500 focus:outline-none focus:placeholder-gray-400 transition duration-150 ease-in-out invalid:border-pink-500 invalid:text-pink-600
                            focus:invalid:border-pink-500 focus:invalid:ring-pink-500"
                                placeholder="Enter full name"></br>

                            <label for="email" class="text-md w-40 inline-block font-medium leading-5 text-gray-700">
                                <h1 style="background-color:rgb(98, 228, 120);">Email of user</h1>
                            </label>
                            <input required type="email" id="email of user" name="email" class="bg-gray-100 inline-block rounded-lg shadow-md px-4 py-3 mb-5 text-base leading-6 placeholder-gray-500 focus:outline-none focus:placeholder-gray-400 transition duration-150 ease-in-out invalid:border-pink-500 invalid:text-pink-600
                            focus:invalid:border-pink-500 focus:invalid:ring-pink-500" placeholder="Enter email"></br>

                            <label for="password" class="text-md w-40 inline-block font-medium leading-5 text-gray-700">
                                <h1 style="background-color:rgb(98, 228, 120);">password of user</h1>
                            </label>
                            <input required type="password " id="password of user" name="password" class="bg-gray-100 inline-block rounded-lg shadow-md px-4 py-3 mb-5 text-base leading-6 placeholder-gray-500 focus:outline-none focus:placeholder-gray-400 transition duration-150 ease-in-out invalid:border-pink-500 invalid:text-pink-600
                            focus:invalid:border-pink-500 focus:invalid:ring-pink-500"
                                placeholder="Enter password"></br>

                            <label for="dob" class="text-md w-40 inline-block font-medium leading-5 text-gray-700">
                                <h1 style="background-color:rgb(98, 228, 120);">DOB</h1>
                            </label>
                            <input required type="date" id="dob" name="dob" class="bg-gray-100 inline-block rounded-lg shadow-md px-4 py-3 mb-5 text-base leading-6 placeholder-gray-500 focus:outline-none focus:placeholder-gray-400 transition duration-150 ease-in-out invalid:border-pink-500 invalid:text-pink-600
                            focus:invalid:border-pink-500 focus:invalid:ring-pink-500"></br>

                            <label for="acceptTerms"
                                class="text-md w-50 inline-block font-medium leading-5 text-gray-700">
                                <h1 style="background-color:rgb(98, 228, 120);">Accept terms and conditions</h1>
                            </label>
                            <input required type="checkbox" id="acceptTerms" name="acceptTerms"
                                class="bg-gray-100 inline-block rounded-lg shadow-md px-4 py-3 mb-5 text-base leading-6 placeholder-gray-500 focus:outline-none focus:placeholder-gray-400 transition duration-150 ease-in-out"></br>

                            <button type="submit"
                                class="w-fit rounded-lg shadow-lg px-8 py-4 bg-green-500 text-white hover:bg-green-400 focus:outline-none focus:shadow-outline transition duration-150 ease-in-out">
                               submit
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>

        <div
            class="relative bg-white px-6 mt-5 pt-10 pb-8 shadow-xl ring-1 ring-gray-900/5 sm:mx-auto sm:rounded-lg sm:px-10">
            <div class="mx-auto">
                <h2 class="text-3xl text-center font-bold leading-tight">
                    Details added
                </h2>
                <div class="divide-y divide-gray-300/50" id="user-entries">
                </div>
            </div>
        </div>
    </div>

    <script src="index.js"></script>

</body>
</html>
Footer
