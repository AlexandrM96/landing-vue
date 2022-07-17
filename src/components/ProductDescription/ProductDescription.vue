<template>
    <section class="product-description">
        <div class="product-description__container">
            <div class="product-description__container-content">
                <div class="container-content__image">
                    <img alt="world" src="../../assets/image/Group39482.svg" />
                </div>
                <div class="container-content__text">
                    <h3>Product description</h3>
                    <p>
                        P2Pseller matches ecommerce sellers to best options for 3PL services, warehousing, fulfillment,
                        labor and shipping rates and make your customers happy
                    </p>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'HelloWorld',
    props: {
        msg: String
    }
}
</script>

<style scoped>
.product-description__container {
    width: 1440px;
    margin: 0 auto;
    padding: 140px 144px 26px 150px;
}

.product-description__container-content {
    display: flex;
}

.container-content__text {
    margin-top: 120px;
    margin-left: 90px;
    padding-right: 280px;
}

.container-content__text h3 {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 32px;
    line-height: 42px;
    color: #212B36;
    margin: 0
}

.container-content__text p {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 500;
    font-size: 17px;
    line-height: 28px;
    color: #637381;
    margin: 0;
}
</style>