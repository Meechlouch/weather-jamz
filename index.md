<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Anemoi Jam</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.9.1/css/bulma.min.css" />
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <link rel="stylesheet" href="./assets/style/style.css" />
  <link rel="icon" href="./assets/img/anemoi1.png" type="image/x-icon" />
  <script src="https://cdnjs.cloudflare.com/ajax/libs/moment.js/2.29.1/moment.min.js"></script>
</head>

<body>
  <div class="header">
    <img alt="Fill anemoi" class="img-header" src="assets/img/top3.jpg" />
  </div>
  <div class="container">
    <div class="columns">
      <div class="column">
        <!-- REMOVE THE CHECKBOX FOR DEMO -->
        <label class="checkbox mb-3 float-right">
          <input type="checkbox" id="youtubeCheckbox">
          Call YouTube API (only do this if you need to, there's a quota limit)
        </label>
        <div class="card">
          <div class="card-content is-align-content-center">
            <form id="weatherSubmitForm">
              <input class="input is-warning is-rounded has-text-weight-bold" id="citySearch" type="text"
                placeholder="City Name..." />
              <div style="display: flex; justify-content: center;"><button
                  class="button is-warning has-text-black has-text-weight-bold mt-3" id="searchBtn">Search for
                  Weather</button></div>
            </form>
          </div>
          <div class="columns">
            <div class="column is-6">
              <div class="card">
                <div class="card-content">
                  <div id="display ">
                    <h1 class="nameTemp is-size-1 is-size-4-mobile"></h1>
                    <p class="weatherDay is-size-3 is-size-4-mobile"></p>
                    <div id="history">
                      <br>
                      <h2 class="has-text-warning is-size-3 has-text-weight-bold">Previous
                        Searches</h2>
                      <button class="button is-text shiftRight" id="clearLink">CLEAR</button>
                      <ul class="has-text-white is-size-5 " id="historyList"></ul>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="column is-6">
              <div class="card">
                <h4 class="title has-text-warning mt-6 has-text-centered has-text-weight-bold">Play Anemoi Jam</h4>
                <div id="player"></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  </div>
  </div>
  <script defer src="https://use.fontawesome.com/releases/v5.14.0/js/all.js"></script>
  <script src="./assets/script/script.js"></script>

</body>

</html>
