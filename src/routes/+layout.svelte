<script>
// @ts-nocheck
    import '../app.css';
    let src = '../src/lib/illustration-article.svg';
</script>

<slot />

<body class="bg-yellow-300 m-4 flex justify-center" >

    <div class="bg-white p-4 w-6/12 font-sans border border-black rounded-xl shadow-[5px_5px_0px_0px_rgba(1,1,0)]">

        <div class="flex items-aling justify-content ">
            <!-- svelte-ignore a11y-img-redundant-alt -->
            <img {src} alt="image-card" class=" rounded"/>
        </div>
        <div class="mt-6">
            <button class="bg-yellow-300 rounded font-bold px-4 h-8">Learning</button>
        </div>
        <p class="text-sm mt-3 font-medium">
            Published 21 Dec 2023
        </p>
        <h1 class="font-bold text-xl mt-4">
            HTML & CSS foundations
        </h1>
        <p class="mt-5 text-gray-500 text-left">
            These languages are the backbone of every website, defining structure, content, and presentation.
        </p>
        <div class="mt-5 flex items-aling justify-content ">
            <!-- svelte-ignore component-name-lowercase -->
            <!-- svelte-ignore a11y-img-redundant-alt -->
            <img src="../src/lib/image-avatar.webp" alt="image-perfil" class="w-10"/>
            <p class="font-bold flex items-center">Greg Hooper</p>   
        </div>
    </div>
    
</body>
  
