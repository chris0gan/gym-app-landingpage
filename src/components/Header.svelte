<script>
    import { openModal } from "../store";
</script>

<header class="flex flex-col relative z-20">
    <div
        class="max-w-[1400px] mx-auto w-full flex items-center justify-between p-4 py-6"
    >
        <a href="/">
            <h1 class="font-semibold hover:text-red-500 cursor-pointer text-black">
                HellDivers <span class="text-yellow-400">2</span>
            </h1>
        </a>
        <button
            on:click={() => ($openModal = true)}
            class="md:hidden grid place-items-center"
        >
            <i class="fa-solid fa-bars"></i>
        </button>
        <nav class="hidden md:flex items-center gap-4 lg:gap-6">
            <a
                href="#game"
                class="duration-200 hover:text-red-500 cursor-pointer"
                >Game</a
            >
            <a
                href="#about"
                class="duration-200 hover:text-red-500 cursor-pointer"
                >About</a
            >
            <a
                href="#reviews"
                class="duration-200 hover:text-red-500 cursor-pointer"
                >Reviews</a
            >
            <button class="specialBtn">
                <p>Purchase</p>
            </button>
            
        </nav>
    </div>
</header>