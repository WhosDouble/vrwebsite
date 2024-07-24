<script>
    import Button from "../shared/button.svelte";
</script>

<div class="flex gap-20 justify-center w-full h-full bg-black p-24">
    <div>
        <h2 class="text-white">Join our Newsletter</h2>
        <p class="text-white">We'll send you a update about new vr tech twice a month</p>
    </div>
    <form class="flex flex-col justify-center items-center gap-4">
        <input class="rounded bg-neutral-700 text-white placeholder:text-white" type="email" placeholder="Enter Email" required>
            <Button type=secondary bigify=true>
                Subscribe
            </Button>
    </form>
</div>


<style>
    input{
        width: 400px;
        padding: 7px;
    }
</style>