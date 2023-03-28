<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3'

defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
})
</script>

<style>
body { text-align: center; padding: 20px; font: 20px Helvetica, sans-serif; color: #333; }
@media (min-width: 768px){
    body{ padding-top: 150px; }
}
h1 { font-size: 50px; }
article { display: block; text-align: left; max-width: 650px; margin: 0 auto; }
a { color: #dc8100; text-decoration: none; }
a:hover { color: #333; text-decoration: none; }
</style>

<template>
    <article>
        <h1>Voltaremos em breve!</h1>
        <div>
            <p>Desculpe pelo inconveniente, mas logo estaremos de volta com um novo site! estamos trabalhando para trazer a melhor expêriencia para você! caso precise você pode nos contactar <a href="mailto:contato@adconstrucoes.com.br">Clicando aqui</a>, Obrigado!</p>
            <p>&mdash; Equipe AD Construções</p>
        </div>
    </article>
</template>
