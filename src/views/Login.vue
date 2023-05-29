<template>
    <div class="sm:flex sm:flex-row">
        <div class="hidden sm:h-screen sm:w-1/2 sm:flex sm:items-center sm:justify-center">
            <div class="flex flex-col items-center">
                <img class="w-[210px]" src="../assets/bike-roubada-logo.jpeg" alt="">
                <p class="text-2xl text-[#003F51] text-center font-bold whitespace-pre-wrap">APENAS ALGUNS CLIQUES PARA O CONTROLE DA SUA BIKE.</p>
            </div>
        </div>
        <div class="bg-[#003F51] sm:w-1/2 h-screen flex items-center justify-center">
            <div class="flex flex-col items-center gap-4">
                <h1 class="text-center text-2xl font-semibold text-[#F0F8FF]">Login do Usuário</h1>
                <header>
                    <div class="flex flex-col gap-2">
                        <img class="w-[185px] sm:hidden" src="../assets/bike-roubada-logo.jpeg" alt="Logo do Projeto Bike Roubada">
                    </div>
                </header>
                <div class="flex justify-center items-center">
                    <form action="" class="">
                        <div class="flex justify-center">
                            <div class="flex items-center flex-col gap-4">
                                <div class="flex flex-col gap-1">
                                    <label class="text-[#F0F8FF] text-xl" for="login">Login</label>
                                    <input class="outline-none shadow-xl p-2 h-[34px] w-[270px] rounded-md bg-[#F0F8FF]" name="login"
                                        type="text">
                                </div>
                                <div class="flex flex-col gap-1">
                                    <label class="text-[#F0F8FF] text-xl" for="senha">Senha</label>
                                    <input class="outline-none shadow-xl p-2 h-[34px] w-[270px] rounded-md bg-[#F0F8FF]" name="senha"
                                        type="password">
                                </div>
                                <button
                                    class="bg-[#199442] text-[#F0F8FF] shadow-xl h-[34px] rounded-md text-xl w-full mt-1">Entrar</button>
                                <a href="#" class="text-[#F0F8FF] underline">Criar uma conta</a>
                            </div>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </div>
</template>
    
<script setup>


</script>