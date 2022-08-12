<script>
  import { onMount } from "svelte";

  import 'ol/ol.css';
  import OSM from "ol/source/OSM";
  import TileLayer from "ol/layer/Tile";
  import { Map, View } from "ol";
  import { fromLonLat } from "ol/proj";

  onMount(() => {
    new Map({
      target: "map-container",
      layers: [
        new TileLayer({
          source: new OSM(),
        }),
      ],
      view: new View({
        center: fromLonLat([0, 0]),
        zoom: 2,
      }),
    });
  });
</script>

<section>
  <div id="map-container" />
</section>

<style>
    #map-container {
        width: 100vw;
        height: 100vh;
    }
</style>
