<template>
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

<style scoped>

</style>
