<template>
    <div style="margin-top: 115px;">
        <div class="option">
            <h1>Варианты коворкинга</h1>
        </div>
        <div class="coworking_of">
            <div class="coworking">
                <div class="cow_info">
                    <h1>Бьюти Коворкинг `Персона`</h1>
                    <p>Разовое: 800Р</p>
                </div>
                <div class="loc">
                    <div class="location">
                        <img src="../assets/img/Location_Icon.svg" alt="">
                        <p>ул. Серафимовича 108</p>
                    </div>
                    <div>
                        <button class="but but_three">Подробнее</button>
                    </div>
                </div>
            </div>
            <div class="coworking_mini">
                <div class="cow_info cow_info_mini">
                    <h1>А-Центр, офисное пространство, коворкинг</h1>
                    <p>Разовое: 450Р</p>
                </div>
                
                <div class="loc loc_mini">
                    <div class="location location_mini">
                        <img src="../assets/img/Location_Icon.svg" alt="">
                        <p>ул. Максима Горького 151</p>
                    </div>
                    <div>
                        <button class="but but_three">Подробнее</button>
                    </div>
                </div>
            </div>
        </div>
        <div class="coworking_of">
            <div class="coworking_mini coworking_mini_two">
                <div class="cow_info cow_info_mini cow_info_mini_two" >
                    <h1>Коворкинг Рубин</h1>
                    <p>Разовое: 1 700Р</p>
                </div>
                <div class="loc loc_mini">
                    <div class="location location_mini">
                        <img src="../assets/img/Location_Icon.svg" alt="">
                        <p>ул. Театраяльная 85</p>
                    </div>
                    <div>
                        <button class="but but_three">Подробнее</button>
                    </div>
                </div>
            </div>
            <div class="coworking coworking_two">
                <div class="cow_info">
                    <h1>Коворкинг Место</h1>
                    <p>Разовое: 7 000Р</p>
                </div>
                <div class="loc">
                    <div class="location">
                        <img src="../assets/img/Location_Icon.svg" alt="">
                        <p>ул. Максима Горького 151</p>
                    </div>
                    <div>
                        <button class="but but_three">Подробнее</button>
                    </div>
                </div>
            </div>

        </div>
        <div style="display: flex; justify-content: center;">
            <button class="but but_two">Смотреть все</button>
        </div>
    </div>
</template>

<script></script>

<style>
.option h1{
    color: #2B7AF1;
    font-size: 36px;
    margin-left: 80px;
}

.coworking{
    background-image: url(../assets/img/coworking.jpg);
    width: 738px;
    height: 300px;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.4);
}

.coworking_mini{
    background-image: url(../assets/img/coworking_mini.jpg);
    width: 522px;
    height: 300px;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.4);
}

.cow_info{
    padding-left: 40px;
    padding-top: 116px;
}


.cow_info h1{
    font-size: 24px;
    color: white;
}

.cow_info p{
    margin-top: 65px;
    color: white;
    font-size: 18px;
}

.cow_info_mini p{
    margin-top: 36px;
}

.cow_info_mini_two p{
    margin-top: 65px;
}

.loc{
    margin-top: 24px;
    margin-right: 20px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.location{
    margin-left: 40px;
    display: flex;
    column-gap: 10px;
}
.location p{

    color: white;
    font-size: 18px;
}
.location img{
    width: 22px;
    height: 22px;
}

.but_three{
    width: 126px;
    height: 33px;
    font-size: 14px;
}

.coworking_of{
    column-gap: 20px;
    display: flex;
    justify-content: center;
}

.coworking_of{
    margin-top: 20px;
}

.coworking_mini_two{
    background-image: url(../assets/img/coworking_mini_two.jpg);
}

.coworking_two{
    background-image: url(../assets/img/coworking_two.jpg);
}

</style>