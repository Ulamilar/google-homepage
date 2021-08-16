# google-homepage
***
This is a code challenge to re-create the basic version of the google homepage using Visual Studio Code from The Odin Project course on Microverse.
#Header
***
This part of the page within a <header> element has the elements of the top navigation bar in the google home page. The elements are Gmail, Images,Products and Sign In. The navigation bar is created using the comman <ul> and each element with its hyperlink listed using the command <li>.
```
<ul class="header">
  <li><a class="gmail" href="https://accounts.google.com/signin/v2/identifier?service=mail&passive=true&rm=false&continue=https%3A%2F%2Fmail.google.com%2Fmail%2F%26ogbl%2F&ss=1&scc=1&ltmpl=default&ltmplcache=2&emr=1&osid=1&flowName=GlifWebSignIn&flowEntry=ServiceLogin">Gmail</a> </li>
  <li><a class="images" href="https://www.google.com.fj/imghp?hl=en&ogbl">Images</a></li>
  <li><a class="products" href="https://about.google/intl/en/products/">Products</a></li>
  <li><a class="signin" href="https://accounts.google.com/signin/v2/identifier?hl=en&passive=true&continue=https%3A%2F%2Fwww.google.com%2F&ec=GAZAmgQ&flowName=GlifWebSignIn&flowEntry=ServiceLogin"> <button>Sign In</button></a></li>
</ul>
```
## Body
***
This part of the page within a <body> element contains the Google logo, google search bar,google search button and google "I feel Lucky" button.
### Google Logo
The Google logo is inserted using the <form> and <div> element which included the image link in the <img> command with a descriptive note.
```
<form>    
    <div class="logo">
        <img src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" alt="Google logo">
    </div>
</form
```
#### Search Bar
The Google search bar is inserted using the <form> and <div> element with an <input> type and placeholder included.
```
<form>
    <div class="searchbar">
        <input type ="text" placeholder="Google Seach">
    </div>
</form>
```
##### Search Button
The search buttons are inserted using the <div> and <form> element with a <button> type included. The two search buttons are Goodle Search and I'm feeling lucky.
```
<form>
    <div class="searchbutton">
        <button type="Google Search">Google Search</button>
        <button type="I'm feeling Lucky">I'm feeling Lucky</button>
    </div>
</form>
```
###### Footer
This part of the page within a <footer> element has the elements of the bottom navigation bar in the google home page. The elements are About, Advertising, Business, How Search Works, Privacy, Terms, Settings.The navigation bar is created using the comman <ul> and each element with its hyperlink listed using the command <li>.
```
<ul>
        <li><a class="about" href="https://about.google/?utm_source=google-FJ&utm_medium=referral&utm_campaign=hp-footer&fg=1">About</a> </li>
        <li><a class="advertising" href="https://ads.google.com/intl/en_fj/home/?subid=ww-ww-et-g-awa-a-g_hpafoot1_1!o2&utm_source=google.com&utm_medium=referral&utm_campaign=google_hpafooter&fg=1"> Advertising</a></li>
        <li><a class="business" href="https://www.google.com/services/?subid=ww-ww-et-g-awa-a-g_hpbfoot1_1!o2&utm_source=google.com&utm_medium=referral&utm_campaign=google_hpbfooter&fg=1#?modal_active=none"> Business</a></li>
        <li><a class="howsearchworks" href="https://www.google.com/search/howsearchworks/?fg=1"> How Search works</a></li>
        <li><a class="privacy" href="https://policies.google.com/privacy?hl=en-FJ&fg=1"> Privacy </a></li>
        <li><a class="terms" href="https://policies.google.com/terms?hl=en-FJ&fg=1"> Terms </a></li>
        <li><a class="settings" href="https://www.google.com/preferences?hl=en-FJ&fg=1"> Settings </a></li>

</ul>
```
