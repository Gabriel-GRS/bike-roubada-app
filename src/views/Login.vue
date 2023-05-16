<template>
    <header>
        <div class="flex flex-col gap-2 items-center justify-center bg-[#003F51] p-7 shadow-2xl">
            <h1 class="text-2xl font-semibold text-white">BikeRoubada+</h1>
        </div>
    </header>
    <main class="bg-[#262626] h-[95vh]">
        <form>
            <div class="flex flex-col items-center justify-center gap-2 h-[60vh]">
                <div class="flex flex-col gap-2">
                    <label class="text-white text-lg font-medium" for="login">Login</label>
                    <input
                        class="w-[300px] h-8 focus:outline-dashed focus:outline-[#003F51] focus:outline-2 rounded-md bg-[#333333] p-2 text-white ease-linear duration-100"
                        name="login" type="text">
                </div>
                <div class="flex flex-col gap-2">
                    <label class="text-white text-lg font-medium" for="senha">Senha</label>
                    <input
                        class="w-[300px] h-8 focus:outline-dashed focus:outline-[#003F51] focus:outline-2 rounded-md bg-[#333333] p-2 text-white ease-linear duration-100 "
                        name="senha" type="password">
                </div>
                <button class="bg-[#003F51] p-2 w-[300px] rounded-md mt-4 font-semibold text-white">Entrar</button>
            </div>
        </form>
    </main>
</template>

<script setup>


</script>
