<template>
    <div class="main_section">
        <h2>{{subTitle}}</h2>
        <p>{{paragraph}}</p>
    </div>
</template>

<script>
    export default {
        name: 'AppMain',
        data(){
            return {
                subTitle: 'Io sono un H2 e sopra di me trovi il Jumbo!',
                
                paragraph: '  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptas veritatis optio autem, voluptatum rem repudiandae ducimus laudantium suscipit, iure a inventore, cum tenetur corporis? Iusto earum voluptatem repellat suscipit provident aut ducimus optio deserunt quam quibusdam magnam, illum autem molestiae dolore omnis reiciendis eligendi maiores ut dignissimos reprehenderit porro quia.'
            }
        },
    }
</script>

<style lang="css">
.main_section {
    width: 60%;
    margin: 0 auto;
}
h2 {
    font-size: 2rem;
    text-align: center;
    padding: 1.5rem;
    color: #41B884;
}
p {
    font-size: 1.3rem;
    text-align: justify;
    line-height: 1.8rem;
    padding: 1rem;
}
</style>