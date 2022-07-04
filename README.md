<style>
    .a1 {
        color: red;
        width: 10%
    }
    .flex {
        display: flex;
        gap: 30px;
        min-width: 100%;
    }
    .p,.ul,.li {
        margin: 0;
        padding: 0;
    }
    .info {
        padding: 5px 0;
        color: #8f8f8f;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .info__name {
        font-size: 24px;
        font-weight: 700;
        color: #000;
    }
    .info__position {
        color: #8f8f8f;
    }
    .linked__list {
        padding: 5px 0;
    }
    .li {
        list-style: none;
    }
    .info__text {
    }
</style>

<div class="header flex">
    <img width="150" src="https://dummyimage.com/300.png/09f/fff" alt="">
    <div class="info">
        <div class="info__text">
            <p class="p info__name">Артем Прокопенко</p>
            <p class="p info__position">Frontend Developer</p>
            <p class="p info__age">02.05.1994(28)</p>
            <p class="p info__location">Россия, Воронеж</p>
        </div>
        <ul class="ul linked__list">
            <li class="li linked__item">
                GitHub
                <a class="a linked__link" href="https://github.com/ArtProEs">
                    github.com/ArtProEs
                </a>
            </li>
            <li class="li linked__item">
                Maill 
                <a class="a linked__link" href="mailto:artproesk@gmail.co">
                    artproesk@gmail.com
                </a>
            </li>
            <li class="li linked__item">
                Phone
                <a class="a linked__link" href="tel:79805363063">
                    +7 (980) 536-30-63
                </a>
            </li>
            <li class="li linked__item">
                Telegram
                <a class="a linked__link" href="https://t.me/Art_Pro_Esk">
                    @Art_Pro_Esk
                </a>
            </li>
        </ul>
    </div>
</div>
