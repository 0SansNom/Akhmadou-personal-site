<div class="h-16">
  <div class="fixed left-0 z-20 flex justify-center w-full bg-base-100 backdrop-blur-lg bg-opacity-90">
    <div class="relative z-10 w-full max-w-6xl navbar">
      <div class="flex-1">
        <a aria-label="Homepage" href="/" class="text-2xl tracking-widest uppercase font-title btn btn-ghost">
          <svg width="66" height="65" viewBox="0 0 486 265" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect width="486" height="265" fill="black"/>
            <path d="M166.288 97.96L190.624 193H166.288L160.816 169.528H134.176L128.848 193H111.424L137.632 97.96H166.288ZM136.912 158.152H158.224L147.424 112.072L136.912 158.152ZM222.574 193H198.67V97.96H222.574V193ZM249.214 97.96H273.262L248.206 142.168L275.278 193H250.222L225.454 144.904L249.214 97.96ZM329.611 193L295.771 125.176V193H280.795V97.96H305.275L339.115 165.784V97.96H353.947V193H329.611Z" fill="white"/>
            </svg>
        </a>
      </div> 
      <div class="flex-none">
        <slot/>
      </div>
    </div>
  </div>
</div>

<script>
export let title = 'Akhmadou Ndiaye'
</script>