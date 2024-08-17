<script>
    import pawnslogo from "$lib/img/pwnslg.png"
    import honeygainlogo from "$lib/img/honeygainlg.png"
    import { Indicator, Card} from 'flowbite-svelte';
    import { GiftBoxSolid} from 'flowbite-svelte-icons';

</script>

<h1 class="pt-28 text-center text-3xl font-bold">Digital Creator <span class="animate-pulse">✪</span></h1>

<div class="my-4">
    <h1 class="text-center">𝐌𝐚𝐤𝐢𝐧𝐠 𝐦𝐨𝐧𝐞𝐲 𝐟𝐫𝐨𝐦 𝐭𝐡𝐞 𝐢𝐧𝐭𝐞𝐫𝐧𝐞𝐭 ✅</h1>
</div>

<div class="border-4 rounded m-4 font-mono">
 <h1 class="text-xl py-2 px-11 text-center">Welcome To Our Virtual Home. Start making money by flowing the steps.</h1>
</div>


<div class="m-8 p-4 text-center">
    <h1><Indicator color="green" class="animate-pulse md:ml-10 lg:ml-32 xl:ml-60"/>
    <span class="font-extrabold md:text-2xl xl:text-3xl bg-green-400 rounded-sm px-2">BEST Free Automatic Profitable Apps</span></h1>
</div>

<div class="grid grid-cols-1 md:grid-cols-2 gap-10 mb-10">
    <div class="col-span-1 m-auto">
        <Card>
            <img class="w-9 h-9 rounded-full" src={pawnslogo} alt="Karen profile" />
            <a href="https://pawns.app/?r=1255808" target="_blank" rel="noreferrer">
              <h5 class="mb-2 text-2xl font-semibold tracking-tight text-purple-700">Pawns App</h5>
            </a>
            <p class="mb-3 font-normal text-gray-500 dark:text-gray-400">If you care for your time, Pawns.app lets you earn money instantly.</p>
            <h1 style="font-family: 'Courier New', Courier, monospace;">Mobile | Desktop</h1>
            <a href="https://pawns.app/?r=1255808" target="_blank" rel="noreferrer" class="inline-flex items-center text-purple-600 hover:underline font-semibold">
              Join now
              <GiftBoxSolid class="w-4 h-4 ms-2.5" />
            </a>
        </Card>
    </div>
    <div class="col-span-1 m-auto">
        <Card>
            <img class="w-9 h-9 rounded-full" src={honeygainlogo} alt="Karen profile" />
            <a href="https://r.honeygain.me/CRYPTDED49" target="_blank" rel="noreferrer">
              <h5 class="mb-2 text-2xl font-semibold tracking-tight text-amber-500">Honeygain App</h5>
            </a>
            <p class="mb-3 font-normal text-gray-500 dark:text-gray-400">Download the Honeygain app today and make money effortlessly.
            </p>
            <h1 style="font-family: 'Courier New', Courier, monospace;">Mobile | Desktop</h1>
            <a href="https://r.honeygain.me/CRYPTDED49" target="_blank" rel="noreferrer" class="inline-flex items-center text-amber-500 hover:underline font-semibold">
              Join now
              <GiftBoxSolid class="w-4 h-4 ms-2.5" />
            </a>
        </Card>
    </div>
</div>

