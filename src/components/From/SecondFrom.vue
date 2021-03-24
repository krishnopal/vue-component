<template>
    <form action="">
                                <div class="flex flex-wrap overflow-hidden mb-1">
                                    <div class="w-full overflow-hidden">
                                        <label for="name">Name:</label>
                                    </div>
                                    <div class="w-full overflow-hidden py-2 px-1">
                                        <input class="py-2 px-2 rounded-md border-2 border-gray-400 border-transparent focus:ring-2 focus:ring-blue-600 focus:border-transparent focus:outline-none transition duration-300 ease-in-out w-full" type="text" name="name" id="name" required autocomplete="off" >
                                    </div>
                                </div>
                                <div class="flex flex-wrap overflow-hidden mb-1">
                                    <div class="w-full overflow-hidden">
                                        <label for="email">Email:</label>
                                    </div>
                                    <div class="w-full overflow-hidden py-2 px-1">
                                        <input class="py-2 px-2 rounded-md border-2 border-gray-400 border-transparent focus:ring-2 focus:ring-blue-600 focus:border-transparent focus:outline-none transition duration-300 ease-in-out w-full" type="email" name="email" id="email" required autocomplete="off" >
                                    </div>
                                </div>
                                <div class="flex flex-wrap overflow-hidden mb-1">
                                    <div class="w-full overflow-hidden">
                                        <label for="select">Select:</label>
                                    </div>
                                    <div class="w-full overflow-hidden py-2 px-1">
                                        <select class="py-2 px-2 rounded-md border-2 border-gray-400 border-transparent focus:ring-2 focus:ring-blue-600 focus:border-transparent focus:outline-none transition duration-300 ease-in-out w-full" required name="select" id="select">
                                            <option value="1">Selection</option>
                                            <option value="1">Shuvo</option>
                                            <option value="1">Hazzaz</option>
                                            <option value="1">Shohan</option>
                                        </select>
                                    </div>
                                </div>
                                <div class="flex flex-wrap overflow-hidden mb-1">
                                    <div class="w-full overflow-hidden">
                                        <label for="Textarea">Textarea:</label>
                                    </div>
                                    <div class="w-full overflow-hidden py-2 px-1">
                                        <textarea class="py-2 px-2 rounded-md border-2 border-gray-400 border-transparent focus:ring-2 focus:ring-blue-600 focus:border-transparent focus:outline-none transition duration-300 ease-in-out w-full" required name="Textarea" id="Textarea" cols="30" rows="4"></textarea>
                                    </div>
                                </div>
                                <div class="flex flex-wrap overflow-hidden mb-1">
                                    <div class="w-full overflow-hidden">
                                        <label for="image">Image:</label>
                                    </div>
                                    <div class="w-full overflow-hidden py-2 px-1">
                                        <input class="py-1 px-2 rounded-md border-2 border-gray-400 border-transparent focus:ring-2 focus:ring-blue-600 focus:border-transparent focus:outline-none transition duration-300 ease-in-out w-full" type="file" name="image" id="image" required autocomplete="off" >
                                    </div>
                                </div>
                                <div>
                                    <input class="" id="checkbox1" type="checkbox" name="checkbox" > <label class="ml-1" for="checkbox1" required >Remembar Me</label>
                                </div>
                                <div class="mt-3">
                                    <button class="bg-blue-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50">Button</button>
                                </div>
                                
                            </form>
</template>