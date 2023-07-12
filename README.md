<html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM" crossorigin="anonymous">
    <style>
      .card-container {
  display: flex;
  justify-content: center;
}

.card {
  margin: 0 10px; /* Adjust the horizontal margin as needed */
  width: 300px; /* Adjust the width of the cards as needed */
  border: 1px solid #ccc;
  border-radius: 8px;
  padding: 10px;
  text-align: center;
  background: linear-gradient(to bottom, #f5f5f5, #dcdcdc);
}

.card img {
  max-width: 100%;
  height: auto;
  margin-top: 10px;
}

.card h3 {
  margin-top: 0;
  background-color: black;
  color: white;
  padding: 10px;
  border-radius: 4px;
  font-size: 16px; /* Adjust the font size as needed */
}

.card p {
  margin-bottom: 10px;
}

.card button {
  background-color: transparent;
  color: #007bff;
  border: none;
  padding: 8px 16px;
  border-radius: 4px;
}

    </style>
    </head>
<body>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-geWF76RCwLtnZ8qwWowPQNguL3RmwHVBC9FhGdlKrxdiJJigb/j/68SIy3Te4Bkz" crossorigin="anonymous"></script>
    
    
    <div class="card-container">
      <div class="card">
        <h3>Afghanistan</h3>
        <img src="data:image/png;base64,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" alt="Card Image">
        <p>Capital : Cabul</p>
        <p>Region : Asia</p>
        <p>Country code : AFG</p>
        <button onclick="window.location.href = 'https://www.google.com/search?q=weather+in+afghanistan+today&rlz=1C1GCEB_enIN1061IN1061&oq=weather+in+afghanish&aqs=chrome.2.69i57j0i13i512l9.12547j1j7&sourceid=chrome&ie=UTF-8';">Click for Weather</button>

      </div>
    
      <div class="card"   >
        <h3>Aland Island</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/52/Flag_of_%C3%85land.svg" alt="Card Image">
        <p>Capital : Marihamn</p>
        <p>Region : Europe</p>
        <p>Country code : ALA</p>
        <button onclick="window.location.href =' https://www.google.com/search?q=weather+in+aland+islands+today&rlz=1C1GCEB_enIN1061IN1061&ei=HVGuZJ7uEtfp4-EPj6y30A8&oq=weather+in+aland++today&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQARgAMggIIRCgARDDBDoKCAAQRxDWBBCwAzoKCAAQigUQsAMQQzoGCAAQBxAeOgcIABANEIAEOgsIABAHEB4Q8QQQCjoJCAAQDRCABBAKOggIABAIEAcQHjoPCAAQCBAHEB4QDxDxBBAKOggIABCKBRCGA0oECEEYAFCOCFixIGCMKGgBcAF4AIABf4gB0wOSAQM0LjGYAQCgAQHAAQHIAQk&sclient=gws-wiz-serp';">Click for Weather</button>

      </div>
    
      <div class="card">
        <h3>Albania</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/3/36/Flag_of_Albania.svg" alt="Card Image">
        <p>Capital : Tirana</p>
        <p>Region : Europe</p>
        <p>Country code : ALB</p>
        <button onclick="window.location.href = 'https://www.google.com/search?q=weather+in+albaniA+islands+today&rlz=1C1GCEB_enIN1061IN1061&ei=LVGuZO61Bs-f4-EPn8uJ2A8&ved=0ahUKEwiugJrxzYiAAxXPzzgGHZ9lAvsQ4dUDCBA&uact=5&oq=weather+in+albaniA+islands+today&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAzIICCEQoAEQwwQ6CggAEEcQ1gQQsAM6BggAEAcQHjoICAAQCBAHEB46CAgAEIoFEIYDOgUIABCiBDoKCCEQoAEQwwQQCjoECCEQCkoECEEYAFDwBli4OmCQQWgBcAF4AIABjQGIAYIIkgEDMS44mAEAoAEBwAEByAEI&sclient=gws-wiz-serp';">Click for Weather</button>
</div>
    </div>
    
</body>
</html></html>
