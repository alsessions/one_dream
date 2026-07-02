---
title: Our Menu
description: One Dream Kitchen menu
fullWidth: true
templateEngineOverride: njk
---

<style>
  .menu-board {
    background: #050505 !important;
    color: #fff !important;
  }

  .menu-board,
  .menu-board * {
    color: #fff !important;
  }

  .menu-card {
    scroll-margin-top: calc(var(--site-header-height, 5rem) + 4.25rem);
    border: 2px solid #c98532;
    border-radius: 1.25rem;
    background: #080808 !important;
    padding: clamp(1rem, 2vw, 1.5rem);
    box-shadow: 0 1rem 2.5rem rgb(0 0 0 / 35%);
  }

  .menu-title-row {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    gap: 1rem;
    border-bottom: 2px solid #c98532;
    padding-bottom: 0.65rem;
    margin-bottom: 1rem;
  }

  .menu-card h2,
  .menu-card h3,
  .menu-card h4 {
    color: #f6b83f !important;
    text-transform: uppercase;
  }

  .menu-card h2 {
    font-size: clamp(2rem, 4vw, 3rem);
    font-weight: 950;
    line-height: 0.9;
  }

  .menu-card h3 {
    font-size: clamp(1.2rem, 2.5vw, 1.7rem);
    font-weight: 950;
  }

  .menu-card h4 {
    font-size: 1.15rem;
    font-weight: 950;
  }

  .menu-price,
  .menu-tag {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
    border: 1px solid #f6b83f;
    background: #9c27b0 !important;
    color: #f6b83f !important;
    font-size: clamp(1.5rem, 3vw, 2.4rem);
    font-weight: 950;
    line-height: 1;
    padding: 0.35rem 0.8rem;
  }

  .menu-tag {
    font-size: 1rem;
    text-transform: uppercase;
  }

  .menu-item {
    margin-top: 0.85rem;
  }

  .menu-item h3,
  .menu-item h4 {
    color: #fff !important;
    text-transform: none;
  }

  .menu-item h3 {
    font-size: 1.25rem;
    line-height: 1.1;
  }

  .menu-item p,
  .menu-note,
  .menu-list {
    font-weight: 700;
  }

  .menu-note {
    color: #f7e8be !important;
  }

  .menu-list {
    display: grid;
    gap: 0.15rem 1.5rem;
  }

  .menu-list.two {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .menu-list.three {
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }

  .menu-line {
    display: flex;
    justify-content: space-between;
    gap: 0.75rem;
    border-bottom: 2px dotted rgb(255 255 255 / 75%);
    font-size: 1.15rem;
    font-weight: 950;
  }

  .menu-line span {
    background: #080808 !important;
  }

  .menu-subhead {
    margin: 1rem 0 0.5rem;
    border-bottom: 1px solid #c98532;
    padding-bottom: 0.25rem;
  }

  .menu-nav {
    position: sticky;
    top: var(--site-header-height, 5rem);
    z-index: 20;
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin-bottom: 1.5rem;
    padding: 0.75rem;
    border: 1px solid #c98532;
    border-radius: 1rem;
    background: rgb(5 5 5 / 92%) !important;
    backdrop-filter: blur(8px);
  }

  .menu-nav a {
    display: inline-flex;
    align-items: center;
    min-height: 2.25rem;
    padding: 0.45rem 0.75rem;
    border: 1px solid rgb(201 133 50 / 70%);
    border-radius: 999px;
    background: #080808 !important;
    color: #f6b83f !important;
    font-size: 0.9rem;
    font-weight: 900;
    line-height: 1;
    text-decoration: none;
    text-transform: uppercase;
  }

  .menu-nav a:hover {
    background: #9c27b0 !important;
    color: #fff !important;
  }
</style>

<section class="menu-board w-full font-sans">
  <nav class="menu-nav" aria-label="Menu sections">
    <a href="#burgers">Burgers</a>
    <a href="#subs">Subs</a>
    <a href="#tacos">Tacos</a>
    <a href="#wraps">Wraps</a>
    <a href="#pizza">Pizza</a>
    <a href="#quesadillas">Quesadillas</a>
    <a href="#reuben">Reuben</a>
    <a href="#paninis">Paninis</a>
    <a href="#mediterranean-favorites">Mediterranean</a>
    <a href="#chicken-wings">Wings</a>
    <a href="#crispy-fish-specials">Fish Specials</a>
  </nav>

  <div class="grid gap-6 lg:grid-cols-2">
    <!-- BURGERS -->
    <article id="burgers" class="menu-card">
      <div class="menu-title-row">
        <h2>Burgers</h2>
        <p class="menu-price">$11.99</p>
      </div>
      <div class="grid gap-4 md:grid-cols-2">
        <div class="menu-item"><h3>Mexican Burger</h3><p>Beef patty topped with pico de gallo, guacamole, pepper jack cheese, lettuce, tomato, onion, jalapeno. Served with fries.</p></div>
        <div class="menu-item"><h3>Veggie Burger</h3><p>Roasted peppers and onions, cilantro, jalapeno, spinach, broccoli, pepper jack cheese. Served with fries.</p></div>
        <div class="menu-item"><h3>Santa Fe Burger</h3><p>Beef patty, chipotle sauce, bacon, pepper jack cheese, lettuce, tomato, onion, jalapeno. Served with fries.</p></div>
        <div class="menu-item"><h3>American Burger</h3><p>Beef patty, BBQ sauce, American cheese, lettuce, tomato, onion, and pickles. Served with fries.</p></div>
      </div>
    </article>

    <!-- SUBS -->
    <article id="subs" class="menu-card">
      <div class="menu-title-row">
        <h2>Subs</h2>
        <p class="menu-price">$10.99</p>
      </div>
      <div class="grid gap-5 md:grid-cols-3">
        <div>
          <h3>American Sub</h3>
          <ul class="menu-list"><li>Italian bread</li><li>Oven-roasted turkey</li><li>Black forest ham</li><li>Bacon</li><li>American cheese</li><li>Lettuce</li><li>Tomatoes</li><li>Red onions</li><li>Mayonnaise</li></ul>
        </div>
        <div>
          <h3>Grilled Chicken</h3>
          <ul class="menu-list"><li>Italian bread</li><li>Grilled chicken</li><li>American cheese</li><li>Lettuce</li><li>Tomatoes</li><li>Red onions</li><li>Green peppers</li><li>Mayonnaise</li></ul>
        </div>
        <div>
          <h3>BLT</h3>
          <ul class="menu-list"><li>Italian bread</li><li>Bacon</li><li>American cheese</li><li>Lettuce</li><li>Tomatoes</li><li>Mayonnaise</li></ul>
          <p class="menu-tag mt-4">Meal with Chips and Soda $14.99</p>
        </div>
      </div>
    </article>

    <!-- TACOS -->
    <article id="tacos" class="menu-card">
      <div class="menu-title-row">
        <div>
          <h2>Tacos</h2>
          <p class="menu-note font-black">Chipotle Style Chicken Tacos</p>
        </div>
      </div>
      <p class="menu-tag mb-4">3 Tacos - $11.99</p>
      <h3>Toppings</h3>
      <ul class="menu-list two">
        <li>Lettuce</li><li>Pickle</li><li>Onions</li><li>Jalapeno</li><li>Cucumber</li><li>Fresh Lime</li><li>Tomatoes</li><li>Guacamole</li><li>Bell Peppers</li><li>Sour Cream</li>
      </ul>
    </article>

    <!-- WRAPS -->
    <article id="wraps" class="menu-card">
      <div class="menu-title-row">
        <h2>Wraps</h2>
        <p class="menu-price">$10.99</p>
      </div>
      <div class="grid gap-4 sm:grid-cols-2">
        <div class="menu-item"><h3>Napa Valley Wrap</h3><p>Grilled chicken, lettuce, avocado, roasted red peppers, tomato, and ranch</p></div>
        <div class="menu-item"><h3>Grilled Chicken Wrap</h3><p>Grilled chicken, lettuce, tomato, mozzarella cheese, and aioli dressing</p></div>
        <div class="menu-item"><h3>Chicken Tikka Masala</h3><p>Chicken tikka masala, American cheese, mayo, lettuce, tomato</p></div>
        <div class="menu-item"><h3>Tuna Wrap</h3><p>Tuna salad, lettuce, tomato, roasted red peppers, American cheese</p></div>
        <div class="menu-item"><h3>Turkey Avocado Wrap</h3><p>Turkey, lettuce, tomato, avocado, and mayo</p></div>
        <div class="menu-item"><h3>Crispy Chicken Wrap</h3><p>Crispy chicken, pesto mayo, lettuce, tomato</p></div>
      </div>
    </article>

    <!-- PIZZA -->
    <article id="pizza" class="menu-card">
      <div class="menu-title-row">
        <div>
          <h2>Pizza</h2>
          <p class="menu-note">Fresh Pizza Made Your Way</p>
        </div>
      </div>
      <h3>Personal Size 10" <span class="menu-note">Buy 4, Get 1 Free!</span></h3>
      <div class="space-y-2">
        <p class="menu-line"><span>Cheese Pizza</span><span>$7.99</span></p>
        <p class="menu-line"><span>Veggie Pizza</span><span>$7.99</span></p>
        <p class="menu-line"><span>Pepperoni</span><span>$8.99</span></p>
        <p class="menu-line"><span>Chicken Pizza</span><span>$8.99</span></p>
        <p class="menu-line"><span>Chipotle Buffalo</span><span>$8.99</span></p>
        <p class="menu-line"><span>Philly Steak Pizza</span><span>$8.99</span></p>
      </div>
      <h3 class="menu-subhead">Personal Size Large 18"</h3>
      <div class="space-y-2">
        <p class="menu-line"><span>Cheese Pizza</span><span>$19.99</span></p>
        <p class="menu-line"><span>Veggie Pizza</span><span>$19.99</span></p>
        <p class="menu-line"><span>Pepperoni Pizza</span><span>$20.99</span></p>
        <p class="menu-line"><span>Chicken Pizza</span><span>$20.99</span></p>
        <p class="menu-line"><span>Chipotle Buffalo</span><span>$20.99</span></p>
        <p class="menu-line"><span>Philly Steak Pizza</span><span>$20.99</span></p>
      </div>
      <p class="mt-3 font-black">Free 2 Liter Soda with Purchase of 18 Inch Pizza</p>
      <div class="mt-4 grid gap-5 sm:grid-cols-2">
        <div>
          <h3>Toppings</h3>
          <ul class="menu-list two">
            <li>Tomato</li><li>Onions</li><li>Jalapenos</li><li>Pickles</li><li>Mushrooms</li><li>Banana Peppers</li><li>Roasted Sweet Onions</li><li>Green Peppers</li><li>Roasted Red Peppers</li>
          </ul>
        </div>
        <div>
          <h3>Choice of Meat</h3>
          <ul class="menu-list two">
            <li>Bacon</li><li>Grilled Chicken Breast</li><li>Philly Steak</li><li>Pepperoni</li>
          </ul>
          <p class="mt-2 font-black">Extra Meat $2.99 each</p>
        </div>
      </div>
    </article>

    <!-- QUESADILLAS -->
    <article id="quesadillas" class="menu-card">
      <div class="menu-title-row">
        <h2>Quesadillas</h2>
        <p class="menu-price">$11.99</p>
      </div>
      <div class="grid gap-4 sm:grid-cols-2">
        <div class="menu-item"><h3>Grilled Chicken Quesadilla</h3><p>Grilled chicken, shredded cheese, roasted peppers, and onions</p></div>
        <div class="menu-item"><h3>Corn Bread Quesadilla</h3><p>Corned beef, roasted pepper and onions, shredded cheese</p></div>
        <div class="menu-item"><h3>Philly Cheesesteak</h3><p>Philly cheese steak, roasted peppers and onions, shredded cheese</p></div>
        <div class="menu-item"><h3>Crispy Chicken</h3><p>Crispy chicken, roasted green peppers, onions, shredded cheese</p></div>
        <div class="menu-item"><h3>Veggie Quesadilla</h3><p>Roasted peppers and onions, broccoli, pico de gallo, jalapenos, pepper jack cheese, and chipotle sauce</p></div>
      </div>
    </article>

    <!-- REUBEN -->
    <article id="reuben" class="menu-card">
      <div class="menu-title-row">
        <div>
          <h2>Reuben</h2>
          <p class="menu-note uppercase font-black">Served on Rye Bread</p>
        </div>
        <p class="menu-price">$10.99</p>
      </div>
      <p class="menu-note font-black">Served with fries</p>
      <div class="space-y-3">
        <div class="menu-item"><h3>Corned Beef Reuben</h3><p>Corned beef, Swiss cheese, sauerkraut, Russian dressing</p></div>
        <div class="menu-item"><h3>Pastrami Reuben</h3><p>Pastrami, Swiss cheese, sauerkraut, deli mustard</p></div>
        <div class="menu-item"><h3>Turkey Reuben</h3><p>Turkey, Swiss cheese, sauerkraut, roasted peppers and onions, deli mustard</p></div>
      </div>
    </article>

    <!-- PANINIS -->
    <article id="paninis" class="menu-card">
      <div class="menu-title-row">
        <h2>Paninis</h2>
        <p class="menu-price">$11.99</p>
      </div>
      <div class="space-y-3">
        <div class="menu-item"><h3>Turkey Bacon Guacamole</h3><p>Turkey, bacon, guacamole, pepper jack cheese and ranch</p></div>
        <div class="menu-item"><h3>Tuna Melt</h3><p>Tuna salad, roasted red peppers and American cheese</p></div>
        <div class="menu-item"><h3>Cabana</h3><p>Turkey, ham, Swiss, pickles and Russian</p></div>
        <div class="menu-item"><h3>Buffalo Chicken</h3><p>Grilled chicken, bacon, cheddar cheese, lettuce, tomato and ranch</p></div>
        <div class="menu-item"><h3>Veggie Melt</h3><p>Roasted peppers and onions, cilantro, jalapeno, spinach, broccoli, pepper jack cheese and chipotle</p></div>
        <div class="menu-item"><h3>Spicy Pepperoni</h3><p>Pepperoni, pepper jack cheese, pickles, jalapeno and chipotle sauce</p></div>
        <div class="menu-item"><h3>Philly Cheese Steak</h3><p>Sliced steak, American cheese, roasted peppers and onions, roasted red peppers and mayo</p></div>
      </div>
    </article>

    <!-- MEDITERRANEAN FAVORITES -->
    <article id="mediterranean-favorites" class="menu-card">
      <div class="menu-title-row">
        <h2>Mediterranean Favorites <span class="menu-note">(Halal)</span></h2>
      </div>
      <div class="space-y-2">
        <p class="menu-line"><span>Chicken Over Rice</span><span>$11.99</span></p>
        <p class="menu-line"><span>Lamb Over Rice</span><span>$11.99</span></p>
        <p class="menu-line"><span>Combo Mix Over Rice</span><span>$11.99</span></p>
        <p class="menu-line"><span>Chicken/Lamb Gyro</span><span>$11.99</span></p>
      </div>
      <p class="mt-2 font-black">Wrapped in Pita Bread</p>
      <p class="mb-4 font-black">Extra Meat $2.99 | Pita $0.99</p>
      <div class="grid gap-5 sm:grid-cols-2">
        <div>
          <h3>Salads Included</h3>
          <ul class="menu-list two">
            <li>Lettuce</li><li>Pickle</li><li>Tomato</li><li>Jalapeno</li><li>Onion</li><li>Guacamole</li><li>Cucumber</li><li>Bell Peppers</li><li>Cilantro Mix</li>
          </ul>
        </div>
        <div>
          <h3>Sauces <span class="menu-note text-sm normal-case">All sauces homemade</span></h3>
          <ul class="menu-list">
            <li>White Dill Sauce</li>
            <li>Buffalo Chipotle Mayo</li>
            <li>Mint and Cilantro Mix</li>
          </ul>
        </div>
      </div>
    </article>

    <!-- CHICKEN WINGS -->
    <article id="chicken-wings" class="menu-card">
      <h2 class="border-b-2 pb-3" style="border-color: #c98532;">Chicken Wings</h2>
      <div class="mt-4 space-y-3">
        <p class="menu-line"><span>5 Chicken Wings</span><span>$7.99</span></p>
        <p class="menu-line"><span>15 Chicken Wings</span><span>$20.99</span></p>
        <p class="menu-line"><span>25 Chicken Wings</span><span>$31.99</span></p>
        <p class="menu-line"><span>40 Chicken Wings</span><span>$44.99</span></p>
      </div>
      <div class="mt-5 rounded-xl p-4" style="border: 1px solid #c98532;">
        <h3>Flavors</h3>
        <p class="font-semibold">Garlic Parmesan, Honey Gold, Lemon Pepper, Mild, Buffalo, Hot, Mango Habanero, Asian Zing</p>
      </div>
    </article>

    <!-- CRISPY FISH SPECIALS -->
    <article id="crispy-fish-specials" class="menu-card">
      <h2 class="border-b-2 pb-3" style="border-color: #c98532;">Crispy Fish Specials</h2>
      <div class="mt-4 space-y-3">
        <p class="menu-line"><span>Crispy Fish and Chips</span><span>$8.99</span></p>
        <p class="menu-line"><span>Crispy Fish Sandwich</span><span>$8.99</span></p>
        <p class="menu-line"><span>Crispy Fish Quesadilla</span><span>$8.99</span></p>
      </div>
    </article>

  </div>
</section>
