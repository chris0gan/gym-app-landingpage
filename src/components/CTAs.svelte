<script>
    export let dark;
</script>

<div class="flex items-center gap-4">
    <button class={"specialBtn " + (dark ? " bg-[#e6e600]" : " ")}>
        <p class="text-black sm:text-lg md:text-xl">Learn More</p>
    </button>
    <button class="specialBtnDark">
        <p class="text-black sm:text-lg md:text-xl">Join The Fight &rarr;</p>
    </button>
</div>