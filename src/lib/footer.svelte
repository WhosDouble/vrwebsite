<script>
    import Button from "../shared/button.svelte";
    import FooterC1 from "./footerC1.svelte";
</script>

<footer class="w-full">
    <div class=" flex items-center p-10 gap-10 w-full h-20 bg-gray-600">
        <h2 class="text-[20px] pl-34">Learn about our, <span class="text-[23px]">Project</span></h2>
        <div class="flex justify-end w-2/4">
            <Button>Projects</Button>
        </div>
    </div>
    <FooterC1 /> 
</footer>

<style>
    footer{
        overflow-y: hidden;
    }
</style>