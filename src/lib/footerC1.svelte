<script>
    import Button from "../shared/button.svelte";
</script>

<div class="flex gap-20 w-full h-full bg-black p-24">
    <div>
        <h2 class="text-white">Join our Newsletter</h2>
        <p class="text-white">We'll send you a update about new vr tech twice a month</p>
    </div>
    <form class="flex flex-col w-full justify-end items-center gap-4">
        <input class="rounded bg-neutral-700 text-white placeholder:text-white" type="email" placeholder="Enter Email" required>
            <Button type=secondary bigify=true>
                Subscribe
            </Button>
    </form>
</div>

<div class="flex w-full gap-20 bg-black pt-0 p-24">
    <div>
        <img src="" alt="websites logo">
        <p class="text-white">experience new worlds with VR</p>
        <p class="text-white pt-24">Texas, dallas</p>
    </div>
    <div class="flex gap-20 w-3/4 justify-around">
        <div class="flex flex-col gap-2">
            <h2 class="text-white text-[19px]">Company</h2>
            <p class="text-white">About us</p>
            <p class="text-white">Vr</p>
            <p class="text-white">Contact Us</p>
            <p class="text-white">FAQs</p>
        </div>
        <div class="flex flex-col gap-2">
            <h2 class="text-white text-[19px]">Products</h2>
            <p class="text-white">headsets</p>
            <p class="text-white">software</p>
        </div>
        <div class="flex flex-col gap-2">
            <h2 class="text-white text-[19px]">Products</h2>
            <p class="text-white">headsets</p>
            <p class="text-white">software</p>
        </div>
        <div class="flex flex-col gap-2"> 
            <h2 class="text-white text-[19px]">Resources</h2>
            <p class="text-white">How VR works</p>
            <p class="text-white">VR Events</p>
            <p class="text-white">Blog</p>
            <p class="text-white">newsletter</p>
            <p class="text-white">Careers</p>
            <p class="text-white">Dev kit</p>
        </div>
    </div>
</div>

<style>
    input{
        width: 400px;
        padding: 7px;
    }
</style>