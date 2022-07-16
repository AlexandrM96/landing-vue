<template>
    <section class="product-information">
        <div class="product-information__container">
            <div class="product-information__container-info-block">
                <div class="info-block__text">
                    <h2>Share your e-commerce infrastructure and get extra profits</h2>
                    <p>
                        Sell more, grow your revenue, and scale your business internationally in just a few clicks.
                        Watch
                        your enterprise grow in real time. Leave the finer points to us!
                    </p>
                    <button>Fill contact form</button>
                </div>
                <div class="info-block__containers">
                    <div class="info-block__containers-container__one">
                        <div class="info-block__containers-container__one-img">
                            <img alt="user" src="../../assets/image/ant-design_user-outlined.svg" />
                        </div>
                        <p>10.000 Sellers on the platform</p>
                    </div>
                    <div class="info-block__containers-container__two">
                        <div class="info-block__containers-container__two-img">
                            <img alt="Discount" src="../../assets/image/Discount.svg" />
                        </div>
                        <p>Do fulfillment for other sellers and earn extra profits</p>
                    </div>
                    <div class="info-block__containers-container__three">
                        <div class="info-block__containers-container__three-img">
                            <img alt="Profit" src="../../assets/image/profit.svg" />
                        </div>
                        <p>Save on seasonality changes</p>
                    </div>
                </div>
            </div>
            <div class="product-information__container-request">
                <div class="request-button"><img alt="Request" src="../../assets/image/File.svg" />Request a from</div>
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

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.product-information__container {
    width: 1440px;
    margin: 0 auto
}

.product-information__container-info-block {
    display: flex;
    justify-content: space-between;
    width: 100%;
    padding: 65px 0px 0px 90px;
}

.info-block__text {
    width: 33%;
    /* margin-right: 50px; */
}

.info-block__containers {
    width: 16%;
    padding-top: 20px;
    padding-right: 270px;
}

.info-block__text h2 {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 48px;
    line-height: 64px;
    color: #212B36;
    margin: 0;
}

.info-block__text p {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 500;
    font-size: 17px;
    line-height: 28px;
    color: #637381;
    margin: 0;
}

.info-block__text button {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 15px;
    line-height: 26px;
    color: #FFFFFF;
    background: #00D5E5;
    box-shadow: 0px 8px 16px rgba(24, 144, 255, 0.24);
    border-radius: 8px;
    border: none;
    padding: 11px 22px;
    margin-top: 32px;
    cursor: pointer;
}

.info-block__containers-container__one {
    border: 1px solid #826AF9;
    border-radius: 8px;
    padding-top: 19px;
    padding-left: 15px;
    padding-bottom: 15px;
    margin-bottom: 16px;
}

.info-block__containers-container__one p {
    margin: 0px;
    color: #826AF9;
}

.info-block__containers-container__two {
    border: 1px solid #2CD9C5;
    border-radius: 8px;
    padding-top: 19px;
    padding-left: 15px;
    padding-right: 10px;
    padding-bottom: 15px;
    margin-bottom: 16px;
}

.info-block__containers-container__two p {
    margin: 0px;
    color: #2CD9C5;
}

.info-block__containers-container__three {
    border: 1px solid #FF6C40;
    border-radius: 8px;
    padding-top: 19px;
    padding-right: 6px;
    padding-left: 15px;
    padding-bottom: 15px;
    margin-bottom: 16px;
}

.info-block__containers-container__three p {
    margin: 0px;
    color: #FF6C40;
}

.product-information__container-request {
    margin-top: 80px;
}
.request-button {
    display: flex;
    align-items: center;
    padding: 8px 16px 8px 20px;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 30px;
    color: #00AAB7;
    background: rgba(0, 213, 229, 0.08);
    border-radius: 8px;
    float:right;
    cursor: pointer;
}

.request-button img{
    margin-right: 12px;
}
</style>