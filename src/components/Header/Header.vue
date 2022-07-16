<template>
    <header class="header">
        <div class="header__container">
            <div class="header__container__logo-and-buttons">
                <div class="container-logo">
                    <div class="container-logo__image">
                        <img alt="Vue logo" src="../../assets/image/logo.svg" />
                    </div>
                </div>
                <div class="container-buttons">
                    <nav class="container-buttons__navigation">
                        <li>Product</li>
                        <li>Integrations</li>
                        <li>How it works</li>
                    </nav>
                    <div class="container-buttons__authorize">
                        <button class="container-buttons__authorize-btn-contact">Contact form</button>
                        <button class="container-buttons__authorize-btn-sign">Sign up</button>
                    </div>
                </div>
            </div>
        </div>
    </header>
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
.header {
    box-shadow: 0px 0px 2px rgba(145, 158, 171, 0.24), 0px 16px 32px -4px rgba(145, 158, 171, 0.24);
}

.header__container {
    width: 1440px;
    margin: 0 auto;
    padding: 26px 144px 26px 150px;
}

.header__container__logo-and-buttons {
    display: flex;
    justify-content: space-between;
}

.container-buttons {
    display: flex;
}

.container-buttons nav {
    display: flex;
}

.container-buttons nav li {
    list-style-type: none;
    padding-right: 20px;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 15px;
    line-height: 24px;
    color: #637381;
    cursor: pointer;
}

.container-buttons {
    display: flex;
    align-items: center;
}

.container-buttons__authorize-btn-contact {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 24px;
    color: #00D5E5;
    background: #FFFFFF;
    border-radius: 8px;
    border: 1px solid #00D5E5;
    margin-right: 20px;
    padding: 6px 16px;
    cursor: pointer;
}

.container-buttons__authorize-btn-sign {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 24px;
    color: #FFFFFF;
    background: #00D5E5;
    border-radius: 8px;
    border: none;
    padding: 6px 16px;
    cursor: pointer;
}
</style>