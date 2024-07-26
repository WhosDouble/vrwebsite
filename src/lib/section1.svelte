<script>
    import Button from "../shared/button.svelte";
    import Icons from "../shared/icons.svelte";
</script>

    <div class="flex p-20 w-full gap-10 justify-center items-center" id="container">
        <div class="flex flex-col text-center  w-[600px]" id="div1">
            <h1 class="text-[70px] text-[#eee] relative">AI IN ANY APP</h1> 
                <div class="icon1"><Icons> <i class='bx bxl-typescript text-[60px] text-[#3178c6]'></i> </Icons></div>
            <h1 class="text-[70px] relative text-[#eee]">UNLOCK <span class="text-[#5C8374]">AI</span> TODAY</h1>
                <div class="icon2"><Icons><i class='bx bxl-react text-[60px] text-[#1a86c9]'></i></Icons></div>
            <div class="w-full max-w-[600px]">
                <p class="text-[15px] text-[#eee]">Discover the power of <span class="text-[#5C8374]">AI</span> to revolutionize your business</p>
                <p class="text-[#eee] pb-5">Embrace the future with AI and watch your business thrive like never before.</p>
                <div class="flex justify-center">
                    <Button>GET STARTED</Button>
                    <Button type=secondary>LEARN MORE</Button>
                </div>
            </div>
        </div>
        
        
    </div>
    <svg class="p-0 m-0" id="visual" viewBox="0 0 2000 600" width="2000" height="600" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1"><rect x="0" y="0" width="2000" height="600" fill="#040D12"></rect><path d="M0 438L47.7 442.7C95.3 447.3 190.7 456.7 285.8 449.7C381 442.7 476 419.3 571.2 412.3C666.3 405.3 761.7 414.7 857 430.3C952.3 446 1047.7 468 1143 465C1238.3 462 1333.7 434 1428.8 419.5C1524 405 1619 404 1714.2 401.7C1809.3 399.3 1904.7 395.7 1952.3 393.8L2000 392L2000 601L1952.3 601C1904.7 601 1809.3 601 1714.2 601C1619 601 1524 601 1428.8 601C1333.7 601 1238.3 601 1143 601C1047.7 601 952.3 601 857 601C761.7 601 666.3 601 571.2 601C476 601 381 601 285.8 601C190.7 601 95.3 601 47.7 601L0 601Z" fill="#000" stroke-linecap="round" stroke-linejoin="miter"></path></svg>

    <style>
        @import url('https://fonts.googleapis.com/css2?family=Anton+SC&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
        .icon1{
            position: absolute;
            transform: rotate(-15deg);
        }
        .icon2{
            position: absolute;
            right: 32%;
            top: 22.5%;
            transform: rotate(15deg);
        }
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