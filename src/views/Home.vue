<template>

            <p class="font-normal text-2xl mt-5 ml-10">Личный блог</p>

        <div class="flex flex-col md:flex-row ml-3 lg:ml-10 mt-8" >
            <div class="flex justify-between items-center bg-[#7b9e4b] w-[94vw] md:w-[220px] lg:w-[200px] xl:w-[250px] px-6 py-8 rounded-2xl">
                <div>
                    <p class="font-normal text-xl">Посты</p>
                    <p class="font-light text-3xl  mt-2">69</p>
                </div>
                <img src="/asset/icon-write.png" alt="">
            </div>
            <div class="flex justify-between items-center bg-[#8fb758] w-[94vw] md:w-[220px] lg:w-[230px] xl:w-[250px] px-6 py-8 rounded-2xl md:ml-7 md:mt-0 mt-4">
                <div>
                    <p class="font-normal text-xl">Категории</p>
                    <p class="font-light text-3xl mt-2">3</p>
                </div>
                <img src="/asset/icon-square.png" alt="">
            </div>
            <div class="flex justify-between items-center bg-[#a3d164] w-[94vw] md:w-[220px] lg:w-[200px] xl:w-[250px] px-6 py-8 rounded-2xl md:ml-7 md:mt-0 mt-4">
                <div>
                    <p class="font-normal text-xl">Пользователи</p>
                    <p class="font-light text-3xl  mt-2">9</p>
                </div>
                <img src="/asset/icon-pp.png" class="imageee" alt="">
            </div>
        </div>

<!-- table start -->
<div class="ml-2 md:ml-10 mt-10 pb-14">
    <p class="font-normal text-xl">Последние посты</p>
    
    <div>
        <div class="flex w-[94vw] md:w-[500px] mt-4">
            <img src="/asset/1.jpeg" class="w-[200px] h-[110px] rounded-xl object-cover object-center" alt="">
            <div class="ml-4 mt-1 flex flex-col justify-between">
                <p class="text-lg font-medium">Новейшие гетероструктуры</p>
                <div class="flex items-center mb-3">
                    <p class="font-normal text-sm text-[#FF6A64] mr-3">Читать далее</p>
                    <img src="/asset/arrow-orange-right.png" class="w-[30px]" alt="">
                </div>
            </div>
        </div>
        <div class="flex w-[94vw] md:w-[500px] mt-5">
            <img src="/asset/2.png" class="w-[200px] h-[110px] rounded-xl object-cover object-center" alt="">
            <div class="ml-4 mt-1 flex flex-col justify-between">
                <p class="text-lg font-medium">Лучшие библиотеки</p>
                <div class="flex items-center mb-3">
                    <p class="font-normal text-sm text-[#FF6A64] mr-3">Читать далее</p>
                    <img src="/asset/arrow-orange-right.png" class="w-[30px]" alt="">
                </div>
            </div>
        </div>
        <div class="flex w-[94vw] md:w-[500px] mt-5">
            <img src="/asset/3.png" class="w-[200px] h-[110px] rounded-xl object-cover object-center" alt="">
            <div class="ml-4 mt-1 flex flex-col justify-between">
                <p class="text-lg font-medium">Экзистенциализм</p>
                <div class="flex items-center mb-3">
                    <p class="font-normal text-sm text-[#FF6A64] mr-3">Читать далее</p>
                    <img src="/asset/arrow-orange-right.png" class="w-[30px]" alt="">
                </div>
            </div>
        </div>
        <div class="flex w-[94vw] md:w-[500px] mt-5">
            <img src="/asset/4.jpg" class="w-[200px] h-[110px] rounded-xl object-cover object-center" alt="">
            <div class="ml-4 mt-1 flex flex-col justify-between">
                <p class="text-lg font-medium">Ведьмак 3
                    <p class="font-light text-sm">Разбор</p>
                </p>
                <div class="flex items-center mb-3">
                    <p class="font-normal text-sm text-[#FF6A64] mr-3">Читать далее</p>
                    <img src="/asset/arrow-orange-right.png" class="w-[30px]" alt="">
                </div>
            </div>
        </div>
    </div>
</div>
<!-- end table start -->
</template>

<script>
export default {
}
</script>

