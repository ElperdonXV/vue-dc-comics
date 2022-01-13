<template>
    <div class="container">
        <header>
            <img src="../assets/img/dc-logo.png" alt="Dc Comics" class="logo">
            <ul>
                <li>
                    <a href="">Characters</a>
                </li>
                <li>
                    <a href="">Comics</a>
                </li>
                <li>
                    <a href="">Movies</a>
                </li>
                <li>
                    <a href="">Tv</a>
                </li>
                <li>
                    <a href="">Games</a>
                </li>
                <li>
                    <a href="">Collections</a>
                </li>
                <li>
                    <a href="">Videos</a>
                </li>
                <li>
                    <a href="">Fans</a>
                </li>
                <li>
                    <a href="">News</a>
                </li>
                <li>
                    <a href="">Shop</a>
                </li>
            </ul>
        </header>
    </div>
    
</template>

<script>
export default {
    name:'Header',
    data (){

    }
}
</script>

<style lang="scss" scoped>
    
    header{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    ul{
        list-style: none;
        display: flex;
        gap: 10px;
        li a {
            text-decoration: none;
            color: black;
            font-weight: bold;
            text-transform: uppercase;
            font-size: 1.2em;
        }
    }
    .logo{
        width: 60px;
    }
</style>