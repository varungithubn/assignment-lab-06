<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="css/style.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css"/>
    <title>HTML Form</title>
</head>
<body>
    <nav>
        <h1> <i>DAVIE'S</i> <i class="fa-solid fa-burger"></i> <i>BURGERS</i></h1>
</nav>                  
<h2>Create a burger!</h2>
<section>
    <label>What type of protien would you like?</label>
    <input type="text" name="What type of protien would you like?" >
</section>
<h3>__________________</h3>
<section>
    <label>How many patties would you like?</label>
    <input type="text" name="How many patties would you like?" >
    <h3>__________________</h3>
    <h3>How do you want your patty cooked</h3>
</section>
<h4>Rare <input type="range" id="Rare"> Well-Done</h4>
<h3>__________________</h3>
<h4>What toppings would you like?</h4>

<h5>
<label for="Lettuce">Lettuce</label>
<input type="radio" id="Lettuce" name="package">
<label for="tomato">Tomato</label>
<input type="radio" id="tomato" name="package">
<label for="onion">Onion</label>
<input type="radio" id="onion" name="package">
</h5>
<h3>__________________</h3>
<h4>Would you like to add cheese?</h4>
<h5>
    <label for="yes">Yes</label>
    <input type="radio" id="yes" name="package">
    <label for="no">NO</label>
    <input type="radio" id="no" name="package">
    </h5>
    <h3>__________________</h3>
    
<h5>
        <label for="food">What type of bun would you like?</label>
        <input type="text" list="foods" id="food" name="food">
       
        <datalist id="foods" name="food">
          <option value="Sesame"></option>
          <option value="Hot"></option>
          <option value="Normal"></option>
          <option value="Double Decker"></option>
          <option value="Single Decker"></option>
          <option value="Other"></option>  
        </datalist>
    </h5>  
    <h3>__________________</h3>

    <section>
        <label>What type of sauce would you like?</label>
        <input type="text" name="What type of protien would you like?" >
    </section>
    <h3>__________________</h3>

    <br>
<section>
    <label for="blog">Anything else you want to add? </label>
    <br>
    <textarea id="blog" name="blog" rows="5" cols="30">
    </textarea>
  
</section>
<h3>__________________</h3>
<footer>
    <button class="btn">Submit</button>
</footer>
</body>
</html>
