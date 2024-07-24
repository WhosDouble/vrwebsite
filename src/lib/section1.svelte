<script>
    import Button from "../shared/button.svelte";
    import Card from "../shared/card.svelte";
    import Card2 from "../shared/card2.svelte";
    import Card3 from "../shared/card3.svelte";
    import Card4 from "../shared/card4.svelte";
</script>

    <div class="flex flex-col justify-center items-center">
        <div class="flex flex-col z-40 text-center justify-center w-full">
            <h1 class="text-[50px] text-[#000]">A new era for</h1> 
            <h1 class="text-[50px]">Virtual <span class="text-orange-600">Reality</span></h1>
            <p class="text-[15px]">we are changing the future of VR</p>
            <p class="text-[15px]">using new technologies</p>
        </div>
        <div class="flex justify-center">
            <Button>New Stuff</Button>
        </div>
        <div class="main-card absolute">
            <h1>test</h1>
        </div>
        <Card></Card>
        <Card2></Card2>
        <Card3></Card3>
        <Card4></Card4>
    </div>

    <style>
        @import url('https://fonts.googleapis.com/css2?family=Anton+SC&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
        h1{
            font-family: Poppins, sans-serif;
            font-weight: bold;
            letter-spacing: 2px;
        }
        p{
            font-weight: bold;
            color: gray;
        }
        .main-card{
            position: relative;
            width: 100%;
            height: 100%;
            min-height: 600px;
            max-width: 1000px;
            background: #000;
            margin: 20px;
            margin-top: 40px;
            border-radius: 10px;
        }
    </style>