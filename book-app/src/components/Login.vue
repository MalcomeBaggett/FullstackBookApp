<template>
    <div class="container">
        <div class="row">
            <div class="col">
                <h1 class="mt-5">Login</h1>
                <hr>
                <form method="post" action="/login" class="need-validation">
                    <text-input  label="Email" type="email" name="email" required="true">
                    </text-input>
                    <text-input label="Password" type="password" name="email" required="true"></text-input>
                </form>
                <hr>
                <input type="submit" class="btn btn-primary" value="Login"/>
            </div>
        </div>
    </div>
</template>

<script>
import TextInput from "./forms/TextInput.vue"
export default {
    name: 'login',
    components: {
        TextInput
    }
}
</script>