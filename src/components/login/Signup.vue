<template>
    <div class="vue-tempalte">
        <form>
            <h3>Créer ton compte</h3>

            <div class="form-group">
                <label>Nom</label>
                <input type="text" class="form-control form-control-lg"/>
            </div>

            <div class="form-group">
                <label>Prénom</label>
                <input type="text" class="form-control form-control-lg"/>
            </div>

            <div class="form-group">
                <label>Email</label>
                <input type="email" class="form-control form-control-lg" />
            </div>

            <div class="form-group">
                <label>Mot de passe</label>
                <input type="password" class="form-control form-control-lg" />
            </div>

            <button type="submit" class="btn btn-dark btn-lg btn-block">S'enregistrer</button>

            <p class="forgot-password text-right">
                Déjà enregistrer ?
                <router-link :to="{name: 'login'}">se connecter</router-link>
            </p>
        </form>
    </div>
</template>

<script>
    export default {
        data() {
            return {}
        }
    }
</script>