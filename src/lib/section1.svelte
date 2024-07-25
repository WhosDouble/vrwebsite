<script>
    import Button from "../shared/button.svelte";
</script>

    <div class="flex p-20 w-full gap-10 justify-center items-center" id="container">
        <div class="flex flex-col text-left  w-[600px]" id="div1">
            <h1 class="text-[50px] text-[#000]">A new era for</h1> 
            <h1 class="text-[50px]">Virtual <span class="text-orange-600">Reality</span></h1>
            <div class="w-full max-w-[600px]">
                <p class="text-[15px]">We are revolutionizing the future of virtual reality. By pushing the boundaries of technology and creativity, we aim to create immersive, interactive experiences that transform how people connect, learn, and explore.</p>
                <div class="flex">
                    <Button>learn More</Button>
                    <Button inverse=true>test</Button>
                </div>
            </div>
        </div>
        <div>
            <div class="flex w-[500px] h-[300px] rounded-lg bg-black" id="block">

            </div>
        </div>
    </div>

    <style>
        @import url('https://fonts.googleapis.com/css2?family=Anton+SC&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
        @media (max-width:850px) {
            #container{
                flex-direction: column;
            }
            #div1{
                width: 500px;
            }
        }
        @media (max-width: 430px) {
            #block{
                width: 400px;
            }
            #container{
                flex-direction: column;
            }
            #div1{
                width: 400px;
            }
        }
    </style>