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
                    <nav>
                        <li>Product</li>
                        <li>Integrations</li>
                        <li>How it works</li>
                    </nav>
                    <div>
                        <button>Contact form</button>
                        <button>Sign up</button>
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
#header {
    box-shadow: 0px 0px 2px rgba(145, 158, 171, 0.24)
}

#header__container {
    width: 1440px;
    padding: 20px;
}

#header__container__logo-and-buttons {
    display: flex;
    justify-content: space-between;
}
</style>