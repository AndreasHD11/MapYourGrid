<div class="page-headers">
<h1>Our Progress</h1>
</div>

<div style="float: right; margin: 5px 0 20px 20px; width: 450px; max-width: 100%">
<img src="../images/progress/mapyourgrid-globalprogress.jpg" style="width: 100%; border: 4px solid #2a6d3c;"></a> 
<figcaption class="image-caption">Global overview of all lines mapped by MapYourGrid in 2025. Click to enlarge.
</figcaption>
</div>


MapYourGrid measures its progress at user, hashtag and country level. We would be honoured to make your progress part of the initiative. If you use our tools and training courses please use the #MapYourGrid hashtag in your changesets or add your user id to our [KPI script](https://github.com/open-energy-transition/MapYourGrid/blob/main/.github/workflows/update-tower-count.yml). If you would like to contribute to our development or keep up to date with our progress, take a look at our public [organization project management](https://github.com/orgs/open-energy-transition/projects/25/views/7) and [roadmap](https://github.com/orgs/open-energy-transition/projects/25/views/13). You may have noticed that our KPIs currently prioritise coverage over data quality. This is because our initiative is working to increase coverage in low- and middle-income countries, resulting in more issues appearing in this grid. However, quality KPIs are currently under development and will be based on the [quality assurance layers that we are implementing simultaneously](tools.md/#quality-assurance-and-validation).


<div class="starter-kit-buttons">
     <a href="#country-list" class="btn btn-primary">
      Country list 🌐
     </a>
      <a href="#community-mapping-progress" class="btn btn-primary">
        Community Mapping Progress 👥
      </a>
      <a href="#line-length-growth-per-country" class="btn btn-primary">
        Line Length Growth per Country 📈
      </a>
      <a href="#interconnectors" class="btn btn-primary">
        Interconnectors ⚡
      </a>
</div>

<!-- Countries Section -->
## **<div class="tools-header">Country list </div>**

We contribute to mapping the grid all around the world. Discover our main contributions in different countries:

![Flag Bangladesh](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Bangladesh.svg){width=20px} [Bangladesh](countrypages/Bangladesh.md) - 
![Flag Benin](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Benin.svg){width=20px} [Benin](countrypages/Benin.md) -
![Flag Bolivia](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Bolivia.svg){width=20px} [Bolivia](countrypages/Bolivia.md) - 
![Flag Bosnia and Herzegovina](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Bosnia%20and%20Herzegovina.svg){width=20px} [Bosnia and Herzegovina](countrypages/Bosnia and Herzegovina.md) - 
![Flag Cambodia](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Cambodia.svg){width=20px} [Cambodia](countrypages/Cambodia.md) - 
![Flag Colombia](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Colombia.svg){width=20px} [Colombia](countrypages/Colombia.md) -
![Flag Georgia](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Georgia.svg){width=20px} [Georgia](countrypages/Georgia.md) - 
![Flag Kazakhstan](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Kazakhstan.svg){width=20px} [Kazakhstan](countrypages/Kazakhstan.md) - 
![Flag Kenya](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Kenya.svg){width=20px} [Kenya](countrypages/Kenya.md) - 
![Flag Mongolia](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Mongolia.svg){width=20px} [Mongolia](countrypages/Mongolia.md) - 
![Flag Nepal](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Nepal.svg){width=20px} [Nepal](countrypages/Nepal.md) -
![Flag Nigeria](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Nigeria.svg){width=20px} [Nigeria](countrypages/Nigeria.md) - 
![Flag Pakistan](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Pakistan.svg){width=20px} [Pakistan](countrypages/Pakistan.md) - 
![Flag Sri Lanka](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Sri%20Lanka.svg){width=20px} [Sri Lanka](countrypages/Sri Lanka.md) - 
![Flag Turkmenistan](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Turkmenistan.svg){width=20px} [Turkmenistan](countrypages/Turkmenistan.md) -
![Flag Uganda](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Uganda.svg){width=20px} [Uganda](countrypages/Uganda.md) - 
![Flag Uzbekistan](http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Uzbekistan.svg){width=20px} [Uzbekistan](countrypages/Uzbekistan.md) - 


<!-- Progress Bars Section -->
## **<div class="tools-header">Community Mapping Progress </div>**

<div class="progress-section"> 
   <button id="refresh-btn" style="margin-bottom:1rem;">
     🔄 Refresh stats (only click if the bars are not "loading...")
   </button>


  <div class="progress-item">
    <label>Contributors mapping with <code>#MapYourGrid</code> hashtag:</label>
    <div class="progress"> <div class="progress-bar" id="contributors-bar" style="background-color: #28a745;"></div> </div>
    <span id="contributors-count">Loading…</span>
  </div>

  <div class="progress-item">
    <label>Total Edits for <code>#MapYourGrid</code> hashtag:</label>
    <div class="progress">
      <div class="progress-bar" id="edits-bar" style="background-color: #28a745;"></div> </div>
    <span id="edits-count">Loading…</span>
  </div>

  <div class="progress-item">
    <label>Total estimated power towers added by mappers of the MapYourGrid funding organisations:</label>
    <div class="progress">
      <div class="progress-bar" id="tower-bar" style="background-color: #17a2b8;"></div>
    </div>
    <span id="tower-count">Loading…</span>
    <br>
    <span id="tower-updated" style="font-size:0.8em; color:#666">Last updated: —</span>
  </div>

  <div class="progress-item">
    <label>Total estimated length of power lines added by mappers of the MapYourGrid funding organisations:</label>
    <div class="progress">
      <div class="progress-bar" id="line-length-bar" style="background-color: #17a2b8;"></div>
    </div>
    <span id="line-length-count">Loading…</span><br>
    <span id="line-length-updated" style="font-size:0.8em; color:#666">
      Last updated: —
    </span>
  </div>

  <div class="progress-item">
    <label>Total Estimated Global Power Capacity added by mappers of the MapYourGrid funding organisations:</label>
    <div class="progress">
      <div class="progress-bar" id="plant-capacity-bar" style="background-color: #17a2b8;"></div>
    </div>
    <span id="plant-capacity-count">Loading…</span>
    <br>
    <span id="plant-capacity-updated" style="font-size:0.8em; color:#666">Last updated: —</span>
  </div>

  <div class="progress-item">
    <label>Total estimated substations added by mappers of the MapYourGrid funding organisations:</label>
    <div class="progress">
      <div class="progress-bar" id="substation-bar" style="background-color: #17a2b8;"></div>
    </div>
    <span id="substation-count">Loading…</span>
    <br>
    <span id="substation-updated" style="font-size:0.8em; color:#666">Last updated: —</span>
  </div>

  <div class="progress-item">
    <label>Total estimated power towers added by people using the <code>#MapYourGrid</code>:</label>
    <div class="progress">
      <div class="progress-bar" id="community-tower-bar" style="background-color: #28a745;"></div>
    </div>
    <span id="community-tower-count">Loading…</span>
    <br>
    <span id="community-tower-updated" style="font-size:0.8em; color:#666">Last updated: —</span>
  </div>

  <div class="progress-item">
    <label>Total estimated length of power lines added by people using the <code>#MapYourGrid</code>:</label>
    <div class="progress">
      <div class="progress-bar" id="community-line-length-bar" style="background-color: #28a745;"></div>
    </div>
    <span id="community-line-length-count">Loading…</span><br>
    <span id="community-line-length-updated" style="font-size:0.8em; color:#666">
      Last updated: —
    </span>
  </div>


</div>


<script>

    // —— CONFIGURE THESE GOALS ——
  const CONTRIBUTORS_GOAL = 1;
  const EDITS_GOAL        = 10000;
  const TOWER_GOAL        = 10000;
  const LINE_LENGTH_GOAL = 5000;
  const COMMUNITY_TOWER_GOAL = 5000;
  const COMMUNITY_LINE_LENGTH_GOAL = 2500;
  const PLANT_CAPACITY_GOAL = 5000;
  const SUBSTATION_GOAL = 250

   // —— UPDATE Ohsome (#MapYourGrid) ——
  async function updateOhsome() {
    const contribCountEl = document.getElementById('contributors-count');
    const editsCountEl   = document.getElementById('edits-count');
    const contribBar     = document.getElementById('contributors-bar');
    const editsBar       = document.getElementById('edits-bar');

    // set loading
    contribCountEl.textContent = 'Loading…';
    editsCountEl.textContent   = 'Loading…';
    contribBar.style.width     = '0%';
    editsBar.style.width       = '0%';

    try {
      const startDate = '2025-03-12T22:00:00Z';
      const endDate   = new Date().toISOString();
      const hashtags = ['mapyourgrid', 'ohmygrid'];
      const url       = `https://stats.now.ohsome.org/api/stats/MapYourGrid?startdate=${startDate}&enddate=${endDate}`;
      const urls = hashtags.map(tag => `https://stats.now.ohsome.org/api/stats/${tag}?startdate=${startDate}&enddate=${endDate}`);

      const responses = await Promise.all(urls.map(url => fetch(url)));
      for (const resp of responses) {
        if (!resp.ok) throw new Error(`HTTP error! status: ${resp.status}`);
      }

      const dataArray = await Promise.all(responses.map(resp => resp.json()));

      // Aggregate the results (sum of users and edits)
      const totalEdits = dataArray.reduce((acc, data) => {
      acc += data.result.edits ?? 0;
      return acc;
      }, 0);

      const OHMYGRID_LEGACY_USERS = 3; //Hazem, Jbcharron, nolan, (cidomo but he also used the new one)
      const mapyourgridData = dataArray[0]; // mapyourgrid is first in the array
      const users = (mapyourgridData.result.users ?? 0) + OHMYGRID_LEGACY_USERS;
      const edits = totalEdits;

      // write DOM
      contribCountEl.textContent = users.toLocaleString();
      editsCountEl.textContent   = edits.toLocaleString('en-US');

      contribBar.style.width = Math.min(100, users / CONTRIBUTORS_GOAL * 100) + '%';
      editsBar.style.width   = Math.min(100, edits / EDITS_GOAL        * 100) + '%';

      // cache
      localStorage.setItem('Combined-ohsome', JSON.stringify({
        users,
        edits,
        ts: Date.now()
      }));
    } catch (err) {
      console.error('Ohsome error', err);
      contribCountEl.textContent = 'Error';
      editsCountEl.textContent = 'Error';
    }
  }

 async function loadTowerCount() {
  const towerCountEl   = document.getElementById('tower-count');
  const towerBar       = document.getElementById('tower-bar');
  const towerUpdatedEl = document.getElementById('tower-updated');

  towerCountEl.textContent   = 'Loading…';
  towerBar.style.width       = '0%';
  towerUpdatedEl.textContent = 'Last updated: —';

  try {
    const resp = await fetch('/data/tower-count.json');
    if (!resp.ok) throw new Error(resp.statusText);
    const { towerCount: count, updated } = await resp.json();

    towerCountEl.textContent   = count.toLocaleString('en-US');
    towerBar.style.width       = Math.min(100, count / TOWER_GOAL * 100) + '%';
    towerUpdatedEl.textContent = `Last updated: ${new Date(updated).toLocaleString()}`;
  }
  catch(err) {
    console.error('Error loading tower count', err);
    towerCountEl.textContent = 'Error';
    towerUpdatedEl.textContent = '';
  }
}

async function loadLineLength() {
  const lengthEl      = document.getElementById('line-length-count');
  const lengthBar     = document.getElementById('line-length-bar');
  const updatedEl     = document.getElementById('line-length-updated');

  lengthEl.textContent   = 'Loading…';
  lengthBar.style.width  = '0%';
  updatedEl.textContent  = 'Last updated: —';

  try {
    const resp = await fetch('/data/line-length.json');
    if (!resp.ok) throw new Error(resp.statusText);
    const data = await resp.json();
    const { lengthKm, mediumHighVoltageKm, percentageOfMediumHigh, updated } = data;

    // Always show the length, even if percentage calculation failed
    let displayText = `${Math.round(lengthKm).toLocaleString('en-US')} km`;

   // Only add percentage if we have valid data
    if (percentageOfMediumHigh !== null && percentageOfMediumHigh !== undefined && mediumHighVoltageKm) {
      displayText += `<br><small style="color: #666; font-size: 0.85em;">${percentageOfMediumHigh}% of all high-voltage lines in OpenStreetMap (source: openinframap.org)</small>`;
    }

    lengthEl.innerHTML = displayText;
    lengthBar.style.width  = Math.min(100, lengthKm / LINE_LENGTH_GOAL * 100) + '%';
    updatedEl.textContent  = `Last updated: ${new Date(updated).toLocaleString()}`;
  } catch(err) {
    console.error('Error loading line length', err);
    lengthEl.textContent = 'Error';
    updatedEl.textContent = '';
  }
}

async function loadCommunityStats() {
  const towerCountEl = document.getElementById('community-tower-count');
  const towerBar = document.getElementById('community-tower-bar');
  const communityTowerUpdatedEl = document.getElementById('community-tower-updated'); // Correct ID for tower updated

  const lengthEl = document.getElementById('community-line-length-count');
  const lengthBar = document.getElementById('community-line-length-bar');
  const communityLineLengthUpdatedEl = document.getElementById('community-line-length-updated'); // Correct ID for line length updated

  // Set initial loading states
  towerCountEl.textContent = 'Loading…';
  towerBar.style.width = '0%';
  communityTowerUpdatedEl.textContent = 'Last updated: —';

  lengthEl.textContent = 'Loading…';
  lengthBar.style.width = '0%';
  communityLineLengthUpdatedEl.textContent = 'Last updated: —';

  try {
    const resp = await fetch('/data/community-stats.json');
    if (!resp.ok) throw new Error(resp.statusText);
    const data = await resp.json();

    // Correctly extract data based on your provided JSON structure
    const towerCount = data.towerCount ?? 0;
    const lengthKm = data.lengthKm ?? 0;
    const updated = data.updated;

    // Update Community Towers
    towerCountEl.textContent = towerCount.toLocaleString('en-US');
    towerBar.style.width = Math.min(100, towerCount / COMMUNITY_TOWER_GOAL * 100) + '%';
    communityTowerUpdatedEl.textContent = `Last updated: ${new Date(updated).toLocaleString()}`;

    // Update Community Line Length
    lengthEl.textContent = `${lengthKm.toLocaleString('en-US')} km`;
    lengthBar.style.width = Math.min(100, lengthKm / COMMUNITY_LINE_LENGTH_GOAL * 100) + '%';
    communityLineLengthUpdatedEl.textContent = `Last updated: ${new Date(updated).toLocaleString()}`;

    // Cache community stats
    localStorage.setItem('MapYourGrid-community-stats', JSON.stringify({
      communityTowerCount: towerCount,
      communityLineLengthKm: lengthKm,
      updated: updated, // Store the actual updated timestamp from JSON
      ts: Date.now() // Store current time for cache age
    }));

  } catch (err) {
    console.error('Error loading community stats', err);
    // Change to 'Error' for clarity when something goes wrong fetching data
    towerCountEl.textContent = 'Error';
    lengthEl.textContent = 'Error';
    communityTowerUpdatedEl.textContent = ''; // Clear timestamp on error
    communityLineLengthUpdatedEl.textContent = ''; // Clear timestamp on error
  }
}

async function loadPlantCapacity() {
    const capacityCountEl = document.getElementById('plant-capacity-count');
    const capacityBar = document.getElementById('plant-capacity-bar');
    const capacityUpdatedEl = document.getElementById('plant-capacity-updated');

    capacityCountEl.textContent = 'Loading…';
    capacityBar.style.width = '0%';
    capacityUpdatedEl.textContent = 'Last updated: —';

    try {
      const resp = await fetch('/data/power-stats.json');
      if (!resp.ok) throw new Error(resp.statusText);
      const { total_capacity_mw, updated } = await resp.json();

      capacityCountEl.textContent = `${Math.round(total_capacity_mw).toLocaleString('en-US')} MW`;
      capacityBar.style.width = Math.min(100, total_capacity_mw / PLANT_CAPACITY_GOAL * 100) + '%';
      capacityUpdatedEl.textContent = `Last updated: ${new Date(updated).toLocaleString()}`;
    } catch (err) {
      console.error('Error loading plant capacity', err);
      capacityCountEl.textContent = 'In Progress Feature';
      capacityUpdatedEl.textContent = '';
    }
  }

async function loadSubstationCount() {
    const substationCountEl = document.getElementById('substation-count');
    const substationBar = document.getElementById('substation-bar');
    const substationUpdatedEl = document.getElementById('substation-updated');

    substationCountEl.textContent = 'Loading…';
    substationBar.style.width = '0%';
    substationUpdatedEl.textContent = 'Last updated: —';

    try {
      const resp = await fetch('/data/power-stats.json');
      if (!resp.ok) throw new Error(resp.statusText);
      const { substation_count, updated } = await resp.json();

      substationCountEl.textContent = substation_count.toLocaleString('en-US');
      substationBar.style.width = Math.min(100, substation_count / SUBSTATION_GOAL * 100) + '%';
      substationUpdatedEl.textContent = `Last updated: ${new Date(updated).toLocaleString()}`;
    } catch (err) {
      console.error('Error loading substation capacity', err);
      substationCountEl.textContent = 'In Progress Feature';
      substationUpdatedEl.textContent = '';
    }
  }

// —— MAIN & CACHE HANDLING ——
  function attemptCacheLoad(id, maxAgeMs) {
    try {
      const raw = localStorage.getItem(id);
      if (!raw) return null;
      const { ts, ...rest } = JSON.parse(raw);
      if (Date.now() - ts > maxAgeMs) return null;
      return rest;
    }
    catch { return null; }
  }

  document.addEventListener('DOMContentLoaded', () => {
    // 1h cache
    const oneHour = 60*60*1000;

    // try Ohsome cache
    const oCache = attemptCacheLoad('MapYourGrid-ohsome', oneHour);
    if (oCache) {
      // populate from cache
      document.getElementById('contributors-count').textContent = oCache.users.toLocaleString('en-US');
      document.getElementById('edits-count').textContent       = oCache.edits.toLocaleString('en-US');
      document.getElementById('contributors-bar').style.width = Math.min(100, oCache.users / CONTRIBUTORS_GOAL * 100) + '%';
      document.getElementById('edits-bar').style.width       = Math.min(100, oCache.edits / EDITS_GOAL * 100) + '%';
    } else {
      updateOhsome();
    }

    // try Towers cache
    const tCache = attemptCacheLoad('MapYourGrid-towers', oneHour);
    if (tCache) {
      document.getElementById('tower-count').textContent = tCache.count.toLocaleString('en-US');
      document.getElementById('tower-bar').style.width   = Math.min(100, tCache.count / TOWER_GOAL * 100) + '%';
      document.getElementById('tower-updated').textContent = `Last updated: ${new Date(tCache.updated).toLocaleString()}`; // Populate updated from cache
    } else {
      loadTowerCount();
    }

    loadLineLength();
    loadPlantCapacity();
    loadSubstationCount();

    // Try Community Stats cache
    const csCache = attemptCacheLoad('MapYourGrid-community-stats', oneHour);
    if (csCache) {
      document.getElementById('community-tower-count').textContent = csCache.communityTowerCount.toLocaleString('en-US');
      document.getElementById('community-tower-bar').style.width = Math.min(100, csCache.communityTowerCount / COMMUNITY_TOWER_GOAL * 100) + '%';
      document.getElementById('community-tower-updated').textContent = `Last updated: ${new Date(csCache.updated).toLocaleString()}`;

      document.getElementById('community-line-length-count').textContent = `${csCache.communityLineLengthKm.toLocaleString('en-US')} km`;
      document.getElementById('community-line-length-bar').style.width = Math.min(100, csCache.communityLineLengthKm / COMMUNITY_LINE_LENGTH_GOAL * 100) + '%';
      document.getElementById('community-line-length-updated').textContent = `Last updated: ${new Date(csCache.updated).toLocaleString()}`;
    } else {
      loadCommunityStats();
    }


    // refresh button now refreshes both
    const btn = document.getElementById('refresh-btn');
    if (btn) {
      btn.addEventListener('click', () => {
        localStorage.removeItem('MapYourGrid-ohsome');
        localStorage.removeItem('MapYourGrid-towers');
        localStorage.removeItem('MapYourGrid-line-length');
        localStorage.removeItem('MapYourGrid-community-stats'); // Clear community stats cache
        updateOhsome();
        loadTowerCount();
        loadLineLength();
        loadCommunityStats(); 
        loadPlantCapacity();
        loadSubstationCount();
      });
    }
  });
</script>

You can find more stats for #mapyourgrid at [OhsomeNowstats](https://stats.now.ohsome.org/dashboard#hashtag=MapYourGrid&start=2025-03-12T22:00:00Z&end=2025-05-14T21:59:59Z&interval=P1M&countries=&topics=).

## **<div class="tools-header">Line Length Growth per Country </div>**

This table shows the total growth in line length for all countries around the world, as calculated using pre-processed statistical data of [ohsome stats](https://stats.now.ohsome.org/).

<iframe src="../data/power_line_length_table.html" width="100%" height="600px" style="border:none;"></iframe>

<!-- Countries Section -->
## **<div class="tools-header">Interconnectors </div>**

We mapped several international interconnectors, as it is shown on the map below:

<div style="text-align:center;">
<img src="https://raw.githubusercontent.com/ben10dynartio/apps/refs/heads/main/osm_interconnectors/international-power-grid-connections.jpg" width="75%"></td>
</div>
