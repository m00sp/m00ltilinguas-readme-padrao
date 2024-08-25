# Multilanguage README Pattern
[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/m00sp/m00ltilinguas-readme-padrao/blob/main/README.md)
[![pt-BR](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/m00sp/m00ltilinguas-readme-padrao/blob/main/README.pt.md)
[![es-UY](https://img.shields.io/badge/lang-es-yellow.svg)](https://github.com/m00sp/m00ltilinguas-readme-padrao/blob/main/README.es.md)

Or with flags

[![en](/icons/usa-48.png)](https://github.com/m00sp/m00ltilinguas-readme-padrao/blob/main/README.md) \
[![pt-BR](/icons/brasil-48.png)](https://github.com/m00sp/m00ltilinguas-readme-padrao/blob/main/README.pt.md) \
[![es-UY](/icons/uy-48.png)](https://github.com/m00sp/m00ltilinguas-readme-padrao/blob/main/README.es.md) \

or with html

<p align="center"> Hello 👋! Wellcome to my site.</p>
<p align="center"> Please, select your language 👇.</p>
<p align="center"> Default set to: </p>
<p align="center"><a class="top" href="https://github.com/m00sp/m00ltilinguas-readme-padrao/blob/main/README.pt.md">Português</a>
</p>
<p align="center"><a class="top" href="https://github.com/m00sp/m00ltilinguas-readme-padrao/blob/main/README.es.md">Español</a>
</p>
<p align="center">🔴 <a class="top" href="https://github.com/m00sp/m00ltilinguas-readme-padrao/blob/main/README.md">English</a>
</p>

or with javascript

<!DOCTYPE html>
<html>
<head>
    <title></title>

    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</head>

<body>

<div class="container">
  <h1 id="description">Show English Text</h1>
   <div class="dropdown">
    <button class="btn btn-default dropdown-toggle" type="button" data-toggle="dropdown">Language Option
    <span class="caret"></span></button>
    <ul class="dropdown-menu">
      <li onclick="toggleLanguage('English')"><a href="#">English</a></li>
      <li onclick="toggleLanguage('Korean')"><a href="#">Korean</a></li>
    </ul>
  </div>
</div>

</body>
<script>
  function toggleLanguage(language) {
    let description = document.getElementById("description");
    if (language === "Korean") {
      description.innerHTML = "Show Korean Text";
    }
    else {
      description.innerHTML = "Show English Text";
    }
  }
</script>
</html>

Just another way to enable more than one language in our README.md files.

---
[![how-to](https://img.shields.io/badge/how--to-use-blue.svg)](https://github.com/m00sp/m00ltilinguas-readme-padrao/blob/main/STEPS.md)
