<script>
    import IconoInforma from "./Iconos/IconoInforma.svelte";
    import TituloMapa from "./Iconos/TituloMapa.svelte";
</script>

<style>

        /* * {
            outline: 1px solid blue;
        } */

        article {
            max-width: 360px;
            height: 30rem;
            background-color: rgb(255, 255, 255);
        }

        .Informacion {
            max-width: 32%;
            display: flex;
            align-items: center;
            flex-direction: column;
        }

        .Encabezado {
            width: 100%;
            height: 7rem;
            background: #516980;
            box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.1);
            border-radius: 0px 0px 0px 40px;
        }

        .Acerca {
            padding: 0 2rem;
        }

        .Texto {
            width: 100%;
            max-height: 17rem;
            overflow: auto;
            color: #5E5E5E;
            font-style: normal;
            font-weight: normal;
            font-size: 1rem;
            line-height: 1.5rem;
        }

        .Subtitulo {
            font-style: normal;
            font-weight: normal;
            font-size: 1.2rem;
            color: #878787;
        }

        .TituloEncabezado {
            display: flex;
            flex-direction: row;
            flex-wrap: nowrap;
            justify-content: space-between;
            align-items: center;
        }

        .TituloMapa {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 1;
        }

        .IconoInforma {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 1.5;
        }
        
    
</style>
    
<article class="Informacion">
    <header class="Encabezado">
    <div class="TituloEncabezado">
        <figure class="TituloMapa">
            <TituloMapa/>
        </figure>
        <figure class="IconoInforma">
            <IconoInforma/>
        </figure>
    </div>
    </header>
    <div class="Acerca">
        <p class="Subtitulo">
            ACERCA DE 
        </p>
        <div class="Texto">
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente quod quidem delectus hic aspernatur sit eum rem laborum sequi, recusandae similique ut totam, dolores dignissimos veniam. Voluptatem error ipsam ipsa!
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Assumenda veritatis hic illo dolore a voluptate perspiciatis, beatae nisi odit distinctio maiores reiciendis corporis obcaecati veniam, illum possimus at? Delectus, vitae.
            </p>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit maxime quisquam optio quis aut nihil vero, ex fugiat non totam quidem modi, suscipit laboriosam molestiae placeat eligendi vel qui perspiciatis!
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit maxime quisquam optio quis aut nihil vero, ex fugiat non totam quidem modi, suscipit laboriosam molestiae placeat eligendi vel qui perspiciatis!
            </p>
            <p>
                Lore ipsum dolor sit amet consectetur adipisicing elit. Quo consequuntur autem repudiandae ducimus nobis possimus facere sunt sint vero laudantium ex aperiam ipsa a, beatae neque, nostrum dolor animi sit!
                Lore ipsum dolor sit amet consectetur adipisicing elit. Quo consequuntur autem repudiandae ducimus nobis possimus facere sunt sint vero laudantium ex aperiam ipsa a, beatae neque, nostrum dolor animi sit!
            </p>
        </div>
    </div>
</article>