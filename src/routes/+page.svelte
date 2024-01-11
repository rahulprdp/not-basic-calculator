<script>
	let arr = new Array(10);
</script>

<div class="h-screen w-screen bg-neutral-950 flex font-primary overflow-hidden">
    <div class="h-screen w-1/4 bg-neutral-950"></div>
    <div class="flex w-full items-center justify-end">   
        <div class="h-screen w-fit flex flex-col">
            <div class=" w-full px-10 py-6 bg-neutral-900 flex justify-between">
                <span class="text-neutral-300 font-semibold ">Not Basic</span>
            </div>
            <div class="h-1/3 bg-neutral-900 flex flex-col justify-end text-right px-4 py-4">
                <div class="text-neutral-300 text-8xl font-light">1723</div>
            </div>
            <div class="h-full w-fit bg-neutral-800 flex justify-between">
                <div class="h-fit w-fit grid space-x-0 space-y-0 grid-cols-6 gap-1 grid-flow-row ">
                    {#each arr as item}
                        <button class="h-40 w-40  bg-neutral-600 m-0 opacity-90 hover:scale-105 hover:opacity-100 ease-in duration-100  shadow-white hover:shadow-lg"></button>
                    {/each}
                    {#each arr as item}
                        <button class="h-40 w-40 bg-orange m-0 opacity-90 hover:scale-105 hover:opacity-100 ease-in duration-100"></button>
                    {/each}
                </div>
            </div>
        </div>
    </div>
    
	
	
</div>
