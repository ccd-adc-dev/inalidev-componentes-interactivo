<script>
    import IconoTwitterVentana from "./Iconos/IconoTwitterVentana.svelte";
    import Tweet from "./Tweet.svelte";
</script>

<style>

        /* * {
            outline: 1px solid blue;
        } */

        article {
            max-width: 360px;
            height: 30rem;
        }

        .ContenedorTwitter {
            max-width: 32%;
            display: flex;
            align-items: center;
            flex-direction: column;
        }

        .Encabezado {
            width: 100%;
            height: 5rem;
            background: #878787;;
            box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.1);
            border-radius: 10px 10px 0px 0px;
            margin-bottom: 1.5rem;
        }

        .ContenedorTweets {
            padding: 0 2rem;
        }

        .Tweets {
            width: 100%;
            max-height: 22rem;
            overflow: auto;
            font-style: normal;
            font-weight: normal;
            font-size: 1rem;
            line-height: 1.5rem;
            /* margin-bottom: 1rem; */
            display: flex;
            flex-direction: column;
            /* align-content: space-around; */
            /* justify-content: space-around; */
            align-items: center;
        }

        .ContenedorEncabezado {
            display: flex;
            padding: 0 2rem;
            flex-direction: row;
            flex-wrap: nowrap;
            justify-content: space-between;
        }

        
        .IconoTwitter {
            justify-content: flex-start !important;
            flex-basis: 60%;
            color: #fff;
            margin-left: -2.5rem;
        }

        .Activismo {
            display: flex;
            align-items: center;
            flex-basis: 125%;
            font-weight: 400;
            font-size: 1.4rem;
            line-height: 1.5rem;
            color: #fff;
        }

        .IconoCerrar {
            display: flex;
            flex-direction: column;
            color: #fff;
            justify-content: center;
            margin-right: -0.5rem;
        }



</style>
    
<article class="ContenedorTwitter">
    <header class="Encabezado">
    <div class="ContenedorEncabezado">
        <div class="IconoTwitter">
            <IconoTwitterVentana/>
        </div>
        <div class="Activismo">
            <span>
                Activismo lingüístico
            </span>
        </div>
        <div class="IconoCerrar">
           <i>icon</i>
        </div>
    </div>
    </header>
    <div class="ContenedorTweets">
        <div class="Tweets">
            <Tweet/>
            <Tweet/>
            <Tweet/>
            <Tweet/>
            <Tweet/>
        </div>
    </div>
</article>