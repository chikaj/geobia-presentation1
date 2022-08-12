<section data-auto-animate>
  <h2 class="r-fit-text">NDVI</h2>
  <h5 class="r-fit-text">
    <small>Normalized Difference Vegetation Index</small>
  </h5>
</section>

<section data-auto-animate>
  <h2>NDVI</h2>
  <h5>
    <small>Normalized Difference Vegetation Index</small>
  </h5>
  <div class="fade-in">
    {`
      
      \\[NDVI = \\frac{\\rho _{nir} - \\rho _{red}}{\\rho _{nir} + \\rho _{red}}\\]
  
    `}
  </div>
  <aside class="notes">
    NDVI is the ratio of the 
    <ul>
        <li>difference of NIR and RED</li>
        <li>to the sum of NIR + RED</li>
    </ul>
  </aside>
</section>

<section>
    <section>
        <h2>GEOBIA Steps</h2>
        <ul>
            <li>Segmentation</li>
            <li>Attribution (aka Feature extraction)</li>
            <li>Classification</li>
        </ul>
    </section>
    <section>
        <h2>Segmentation Algorithms</h2>
        <p class="fragment fade-in fade-out">Many!</p>
        <ul class="fragment">
            <li>Simple Linear Iterative Clustering (SLIC)</li>
            <li>Quickshift</li>
            <li>Felzenschwalb</li>
        </ul>
    </section>
</section>
