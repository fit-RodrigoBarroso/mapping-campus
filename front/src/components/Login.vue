<template>
<<<<<<< HEAD
<form id="login-form" class="block" @submit="onSubmit">
    <img class="iconMedium"  src="../res/icons/user2.svg">
    <label class="form-label">Login</label>
    <input required class="form-control-md" id="email" v-model="login" type="text">
    <label class="form-label" for="">Senha</label>
    <input required class="form-control-md" id="password" v-model="password" type="text">
    <div class="buttons">
        <button class="button">Voltar</button>
        <button class="button">Entrar</button>
    </div>
</form>
=======
<h1>
    <div >
        <form @submit="onSubmit">
            <div>
                <label for="">Login</label><br><input v-model="login" type="text">
            </div>
            <div>
                <label for="">Senha</label><br><input v-model="password" type="text">
            </div>
            <button>login</button>
            <button >Cadastrar</button>
        </form>
    </div>
</h1>
>>>>>>> 660dbeb378d531b8945acce4d803541e24ec1298
</template>

<script>

export default{
    name: "Login",
    data() {
        return {
            login: "",
            password: ""
        }
    },
    methods: {
        onSubmit() {
            console.log("login: ",this.login, "senha:", this.password)
        }
    }
}
</script>
<<<<<<< HEAD
    
<style>
=======

<style scoped>
>>>>>>> 660dbeb378d531b8945acce4d803541e24ec1298

</style>
