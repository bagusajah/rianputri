<template>
    <div id="invitation">
        <h1 class="uk-heading-line uk-text-center uk-h1 uk-padding-small title" uk-scrollspy="cls:uk-animation-slide-top-small"><span>Our Invitation</span></h1>
        <div class="uk-responsive-width uk-padding-large uk-overflow-hidden uk-padding-remove-top">
            <div class="text-nama">
                <h1 uk-scrollspy="cls:uk-animation-slide-top-small">Muhammad Rian Rahadian</h1>
                <h4 uk-scrollspy="cls:uk-animation-slide-top-small">dengan</h4>
                <h1 uk-scrollspy="cls:uk-animation-slide-top-small">Putri Windasari</h1>
            </div>
            <div class="uk-responsive-width uk-padding-large uk-padding-remove-bottom">
                <h2>Akad Nikah</h2>
                <p>Kamis, 20 Agustus 2020<br>10:00 WIB</p>
                <div class="countdown uk-flex uk-visible@l">
                    <div uk-grid uk-countdown="date: 2020-08-20T11:00:00+00:00" class="uk-margin-auto">
                        <div>
                            <div class="uk-countdown-number uk-countdown-days"></div>
                            <div class="uk-countdown-label uk-margin-small uk-text-center">Days</div>
                        </div>
                        <div class="uk-countdown-separator">:</div>
                        <div>
                            <div class="uk-countdown-number uk-countdown-hours"></div>
                            <div class="uk-countdown-label uk-margin-small uk-text-center">Hours</div>
                        </div>
                        <div class="uk-countdown-separator">:</div>
                        <div>
                            <div class="uk-countdown-number uk-countdown-minutes"></div>
                            <div class="uk-countdown-label uk-margin-small uk-text-center">Minutes</div>
                        </div>
                        <div class="uk-countdown-separator">:</div>
                        <div>
                            <div class="uk-countdown-number uk-countdown-seconds"></div>
                            <div class="uk-countdown-label uk-margin-small uk-text-center">Seconds</div>
                        </div>
                    </div>
                </div>
                <div class="countdown uk-flex uk-hidden@l">
                    <div uk-grid uk-countdown="date: 2017-12-30T11:00:00+00:00" class="uk-margin-auto">
                        <div>
                            <div class="uk-countdown-number uk-countdown-days"></div>
                            <div class="uk-countdown-label uk-margin-small uk-text-center">Days</div>
                        </div>
                        <div class="uk-countdown-separator">:</div>
                        <div>
                            <div class="uk-countdown-number uk-countdown-hours"></div>
                            <div class="uk-countdown-label uk-margin-small uk-text-center">Hours</div>
                        </div>
                        <div class="uk-countdown-separator">:</div>
                        <div>
                            <div class="uk-countdown-number uk-countdown-minutes"></div>
                            <div class="uk-countdown-label uk-margin-small uk-text-center">Minutes</div>
                        </div>
                        <div class="uk-countdown-separator">:</div>
                        <div>
                            <div class="uk-countdown-number uk-countdown-seconds"></div>
                            <div class="uk-countdown-label uk-margin-small uk-text-center">Seconds</div>
                        </div>
                    </div>
                </div>
                <p>Kesehatan dan keselamatan bersama menjadi perhatian utama kami. Oleh karena itu process pernikahan akan digelar secara tertutup dan sesuai tengan protokol kesehatan yang berlaku<br>
                <a class="uk-button uk-button-small" href="https://www.google.co.id/maps/place/Medan,+Kota+Medan,+Sumatera+Utara/@3.6426183,98.5294069,11z/data=!3m1!4b1!4m5!3m4!1s0x303131cc1c3eb2fd:0x23d431c8a6908262!8m2!3d3.5951956!4d98.6722227" target="_blank"><img title="Directions" uk-tooltip="pos: bottom" class="uk-width-1-4" src="https://4.bp.blogspot.com/-Zt-ZsOW1AOI/Wi3wqJgMl3I/AAAAAAAAH-Q/fgrzu20YPBE9zCVR9vbm1h4d5QweXmARgCLcBGAs/s1600/maps.png" alt="Maps"></a>
                </p>
                <a class="uk-button uk-button-small uk-button-primary" href="#" target="_blank" title="Ucapan Selamat" uk-tooltip="pos: bottom">Berikan Ucapan <i uk-icon="icon: pencil"></i></a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Invitation',
};
</script>

<style lang="scss" scoped>
    $colorprimary : #dd183f;

    #invitation {
        padding-top: 1px;
        padding-bottom: 50px;
        background-color: #c1ebf7;
    } 
    .countdown  * {
        font-size: 30px !important;
        color: $colorprimary !important;
    }
    .uk-countdown-number, .uk-countdown-separator {
        line-height: 1 !important;
    }
    .countdown .uk-countdown-label {
        font-size: 20px !important;
    }
    .countdown .uk-grid > * {
        padding-left: 10px !important;
    }
    .text-nama {
        padding-top: 10px;
        padding-bottom: 10px !important;
    }
    .text-nama h1{
        font-size: 50px !important;
        margin: 0 !important;
    }
    .text-nama h5, .text-nama h3 {
        margin: 0 !important;
    }
    .text-nama p,.text-nama h4 {
        padding-top: 10px !important;
        padding-bottom: 10px !important;
    }
    .uk-width-1-4 {
        padding: 0 !important;
        margin: 0 !important;
    }
    h4 {
        margin-top: 15px !important;
    }
    h5 {
        color: #666666 !important;
    }

    @media screen and (max-width: 1024px) {
        .countdown  * {
            font-size: 20px !important;
            color: $colorprimary !important;
        }
        .uk-countdown-number, .uk-countdown-separator {
            line-height: 1 !important;
        }
        .countdown .uk-countdown-label {
            font-size: 12px !important;
        }
        .countdown .uk-grid > * {
            padding-left: 5px !important;
        }
        .text-nama h1 {
            font-size : 27px !important;
        }
        .text-nama h5 {
            font-size : 12px !important;
        }
    }
</style>