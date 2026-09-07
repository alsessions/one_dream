---
title: Our Menu
description: One Dream Kitchen menu
fullWidth: true
templateEngineOverride: njk
---

{% set menuCard = "scroll-mt-36 rounded-2xl border-2 border-[#c98532] bg-[#080808] p-4 text-white shadow-2xl sm:p-6" %}
{% set titleRow = "mb-4 flex items-start justify-between gap-4 border-b-2 border-[#c98532] pb-3" %}
{% set title = "text-4xl font-black uppercase leading-none text-[#f6b83f] md:text-5xl" %}
{% set sectionHeading = "text-2xl font-black uppercase text-[#f6b83f]" %}
{% set itemTitle = "text-xl font-black leading-tight text-white" %}
{% set itemBody = "font-bold text-white" %}
{% set note = "font-black text-[#f7e8be]" %}
{% set price = "inline-flex shrink-0 items-center justify-center border border-[#f6b83f] bg-[#9c27b0] px-3 py-2 text-3xl font-black leading-none text-[#f6b83f] md:text-4xl" %}
{% set tag = "inline-flex shrink-0 items-center justify-center border border-[#f6b83f] bg-[#9c27b0] px-3 py-2 text-base font-black uppercase leading-none text-[#f6b83f]" %}
{% set list = "grid gap-x-6 gap-y-1 font-bold text-white" %}
{% set line = "flex justify-between gap-3 border-b-2 border-dotted border-white/75 text-lg font-black text-white" %}
{% set lineLabel = "bg-[#080808] pr-2" %}
{% set linePrice = "bg-[#080808] pl-2" %}
{% set subhead = "mb-2 mt-4 border-b border-[#c98532] pb-1 text-2xl font-black uppercase text-[#f6b83f]" %}
{% set navLink = "inline-flex min-h-9 items-center rounded-full border border-[#c98532]/70 bg-[#080808] px-3 py-2 text-sm font-black uppercase leading-none text-[#f6b83f] no-underline hover:bg-[#9c27b0] hover:text-white" %}

<section class="w-full bg-[#050505] font-sans text-white">
  <nav class="sticky top-[var(--site-header-height)] z-20 mb-6 flex flex-wrap gap-2 rounded-2xl border border-[#c98532] bg-[#050505]/90 p-3 backdrop-blur" aria-label="Menu sections">
    <a class="{{ navLink }}" href="#burgers">Burgers</a>
    <a class="{{ navLink }}" href="#subs">Subs</a>
    <a class="{{ navLink }}" href="#tacos">Tacos</a>
    <a class="{{ navLink }}" href="#wraps">Wraps</a>
    <a class="{{ navLink }}" href="#pizza">Pizza</a>
    <a class="{{ navLink }}" href="#quesadillas">Quesadillas</a>
    <a class="{{ navLink }}" href="#reuben">Reuben</a>
    <a class="{{ navLink }}" href="#paninis">Paninis</a>
    <a class="{{ navLink }}" href="#mediterranean-favorites">Mediterranean</a>
    <a class="{{ navLink }}" href="#chicken-wings">Wings</a>
    <a class="{{ navLink }}" href="#crispy-fish-specials">Fish Specials</a>
  </nav>

  <div class="grid gap-6 lg:grid-cols-2">
    <!-- BURGERS -->
    <article id="burgers" class="{{ menuCard }}">
      <div class="{{ titleRow }}">
        <h2 class="{{ title }}">Burgers</h2>
        <p class="{{ price }}">$11.99</p>
      </div>
      <div class="grid gap-4 md:grid-cols-2">
        <div class="mt-3"><h3 class="{{ itemTitle }}">Mexican Burger</h3><p class="{{ itemBody }}">Beef patty topped with pico de gallo, guacamole, pepper jack cheese, lettuce, tomato, onion, jalapeno. Served with fries.</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">Veggie Burger</h3><p class="{{ itemBody }}">Roasted peppers and onions, cilantro, jalapeno, spinach, broccoli, pepper jack cheese. Served with fries.</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">Santa Fe Burger</h3><p class="{{ itemBody }}">Beef patty, chipotle sauce, bacon, pepper jack cheese, lettuce, tomato, onion, jalapeno. Served with fries.</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">American Burger</h3><p class="{{ itemBody }}">Beef patty, BBQ sauce, American cheese, lettuce, tomato, onion, and pickles. Served with fries.</p></div>
      </div>
    </article>

    <!-- SUBS -->
    <article id="subs" class="{{ menuCard }}">
      <div class="{{ titleRow }}">
        <h2 class="{{ title }}">Subs</h2>
        <p class="{{ price }}">$10.99</p>
      </div>
      <div class="grid gap-5 md:grid-cols-3">
        <div>
          <h3 class="{{ sectionHeading }}">American Sub</h3>
          <ul class="{{ list }}"><li>Italian bread</li><li>Oven-roasted turkey</li><li>Black forest ham</li><li>Bacon</li><li>American cheese</li><li>Lettuce</li><li>Tomatoes</li><li>Red onions</li><li>Mayonnaise</li></ul>
        </div>
        <div>
          <h3 class="{{ sectionHeading }}">Grilled Chicken</h3>
          <ul class="{{ list }}"><li>Italian bread</li><li>Grilled chicken</li><li>American cheese</li><li>Lettuce</li><li>Tomatoes</li><li>Red onions</li><li>Green peppers</li><li>Mayonnaise</li></ul>
        </div>
      
      </div>
    </article>

    <!-- TACOS -->
    <article id="tacos" class="{{ menuCard }}">
      <div class="{{ titleRow }}">
        <div>
          <h2 class="{{ title }}">Tacos</h2>
          <p class="{{ note }} font-black">Chipotle Style Chicken Tacos</p>
           <p class="{{ note }} font-black">Soft or Hard Shell</p>
        </div>
      </div>
      <p class="{{ tag }} mb-4">3 Tacos - $11.99</p>
      <h3 class="{{ sectionHeading }}">Toppings</h3>
      <ul class="{{ list }} grid-cols-2">
        <li>Lettuce</li><li>Pickle</li><li>Onions</li><li>Jalapeno</li><li>Cucumber</li><li>Fresh Lime</li><li>Tomatoes</li><li>Guacamole</li><li>Bell Peppers</li><li>Sour Cream</li>
      </ul>
    </article>

    <!-- WRAPS -->
    <article id="wraps" class="{{ menuCard }}">
      <div class="{{ titleRow }}">
        <h2 class="{{ title }}">Wraps</h2>
        <p class="{{ price }}">$10.99</p>
      </div>
      <div class="grid gap-4 sm:grid-cols-2">
        <div class="mt-3"><h3 class="{{ itemTitle }}">Napa Valley Wrap</h3><p class="{{ itemBody }}">Grilled chicken, lettuce, avocado, roasted red peppers, tomato, & ranch</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">Grilled Chicken Wrap</h3><p class="{{ itemBody }}">Grilled chicken, lettuce, tomato, mozzarella cheese & aioli dressing</p></div>
      
        <div class="mt-3"><h3 class="{{ itemTitle }}">Tuna Wrap</h3><p class="{{ itemBody }}">Tuna salad, lettuce, tomato, roasted red peppers, American cheese</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">Turkey Avocado Wrap</h3><p class="{{ itemBody }}">Turkey, lettuce, tomato, avocado, & mayo</p></div>
      

      </div>
    </article>

    <!-- PIZZA -->
    <article id="pizza" class="{{ menuCard }}">
      <div class="{{ titleRow }}">
        <div>
          <h2 class="{{ title }}">Pizza</h2>
          <p class="{{ note }}">Fresh Pizza Made Your Way</p>
        </div>
      </div>
      <h3 class="{{ sectionHeading }}">Personal Size 10" <span class="{{ note }}">Buy 4, Get 1 Free!</span></h3>
      <div class="space-y-2">
        <p class="{{ line }}"><span class="{{ lineLabel }}">Cheese Pizza</span><span class="{{ linePrice }}">$7.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">Veggie Pizza</span><span class="{{ linePrice }}">$7.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">Pepperoni</span><span class="{{ linePrice }}">$8.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">Chicken Pizza</span><span class="{{ linePrice }}">$8.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">Chipotle Buffalo</span><span class="{{ linePrice }}">$8.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">Philly Steak Pizza</span><span class="{{ linePrice }}">$8.99</span></p>
      </div>
      <h3 class="{{ subhead }}">Personal Size Large 18"</h3>
      <div class="space-y-2">
        <p class="{{ line }}"><span class="{{ lineLabel }}">Cheese Pizza</span><span class="{{ linePrice }}">$19.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">Veggie Pizza</span><span class="{{ linePrice }}">$19.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">Pepperoni Pizza</span><span class="{{ linePrice }}">$20.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">Chicken Pizza</span><span class="{{ linePrice }}">$20.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">Chipotle Buffalo</span><span class="{{ linePrice }}">$20.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">Philly Steak Pizza</span><span class="{{ linePrice }}">$20.99</span></p>
      </div>
      <p class="mt-3 font-black">Free 2 Liter Soda with Purchase of 18 Inch Pizza</p>
      <div class="mt-4 grid gap-5 sm:grid-cols-2">
        <div>
          <h3 class="{{ sectionHeading }}">Toppings</h3>
          <ul class="{{ list }} grid-cols-2">
            <li>Tomato</li><li>Onions</li><li>Jalapenos</li><li>Pickles</li><li>Mushrooms</li><li>Banana Peppers</li><li>Roasted Sweet Onions</li><li>Green Peppers</li><li>Roasted Red Peppers</li>
          </ul>
        </div>
        <div>
          <h3 class="{{ sectionHeading }}">Choice of Meat</h3>
          <ul class="{{ list }} grid-cols-2">
            <li>Bacon</li><li>Grilled Chicken Breast</li><li>Philly Steak</li><li>Pepperoni</li>
          </ul>
          <p class="mt-2 font-black">Extra Meat $2.99 each</p>
        </div>
      </div>
    </article>

    <!-- QUESADILLAS -->
    <article id="quesadillas" class="{{ menuCard }}">
      <div class="{{ titleRow }}">
        <h2 class="{{ title }}">Quesadillas</h2>
        <p class="{{ price }}">$11.99</p>
      </div>
      <div class="grid gap-4 sm:grid-cols-2">
        <div class="mt-3"><h3 class="{{ itemTitle }}">Grilled Chicken Quesadilla</h3><p class="{{ itemBody }}">Grilled chicken, shredded cheese, roasted peppers, & onions</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">Corn Bread Quesadilla</h3><p class="{{ itemBody }}">Corned beef, roasted pepper & onions, shredded cheese</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">Philly Cheesesteak</h3><p class="{{ itemBody }}">Philly cheese steak, roasted peppers & onions, shredded cheese</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">Crispy Chicken</h3><p class="{{ itemBody }}">Crispy chicken, roasted green peppers, onions, shredded cheese</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">Veggie Quesadilla</h3><p class="{{ itemBody }}">Roasted peppers & onions, broccoli, pico de gallo, jalapenos, pepper jack cheese, & chipotle sauce</p></div>
      </div>
    </article>

    <!-- REUBEN -->
    <article id="reuben" class="{{ menuCard }}">
      <div class="{{ titleRow }}">
        <div>
          <h2 class="{{ title }}">Reuben</h2>
          <p class="{{ note }} uppercase font-black">Served on Rye Bread</p>
        </div>
        <p class="{{ price }}">$10.99</p>
      </div>
      <p class="{{ note }} font-black">Served with fries</p>
      <div class="space-y-3">
        <div class="mt-3"><h3 class="{{ itemTitle }}">Corned Beef Reuben</h3><p class="{{ itemBody }}">Corned beef, Swiss cheese, sauerkraut, Russian dressing</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">Pastrami Reuben</h3><p class="{{ itemBody }}">Pastrami, Swiss cheese, sauerkraut, deli mustard</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">Turkey Reuben</h3><p class="{{ itemBody }}">Turkey, Swiss cheese, sauerkraut, roasted peppers & onions, deli mustard</p></div>
      </div>
    </article>

    <!-- PANINIS -->
    <article id="paninis" class="{{ menuCard }}">
      <div class="{{ titleRow }}">
        <h2 class="{{ title }}">Paninis</h2>
        <p class="{{ price }}">$11.99</p>
      </div>
      <div class="space-y-3">
        <div class="mt-3"><h3 class="{{ itemTitle }}">Turkey Bacon Guacamole</h3><p class="{{ itemBody }}">Turkey, bacon, guacamole, pepper jack cheese & ranch</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">Tuna Melt</h3><p class="{{ itemBody }}">Tuna salad, roasted red peppers & American cheese</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">Cabana</h3><p class="{{ itemBody }}">Turkey, ham, Swiss, pickles & Russian</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">Buffalo Chicken</h3><p class="{{ itemBody }}">Grilled chicken, bacon, cheddar cheese, lettuce, tomato & ranch</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">Veggie Melt</h3><p class="{{ itemBody }}">Roasted peppers & onions, cilantro, jalapeno, spinach, broccoli, pepper jack cheese & chipotle</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">Spicy Pepperoni</h3><p class="{{ itemBody }}">Pepperoni, pepper jack cheese, pickles, jalapeno & chipotle sauce</p></div>
        <div class="mt-3"><h3 class="{{ itemTitle }}">Philly Cheese Steak</h3><p class="{{ itemBody }}">Sliced steak, American cheese, roasted peppers & onions, roasted red peppers & mayo</p></div>
      </div>
    </article>

    <!-- MEDITERRANEAN FAVORITES -->
    <article id="mediterranean-favorites" class="{{ menuCard }}">
      <div class="{{ titleRow }}">
        <h2 class="{{ title }}">Mediterranean Favorites <span class="{{ note }}">(Halal)</span></h2>
      </div>
      <div class="space-y-2">
        <p class="{{ line }}"><span class="{{ lineLabel }}">Chicken Over Rice</span><span class="{{ linePrice }}">$11.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">Lamb Over Rice</span><span class="{{ linePrice }}">$11.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">Combo Mix Over Rice</span><span class="{{ linePrice }}">$11.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">Chicken/Lamb Gyro</span><span class="{{ linePrice }}">$11.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">Falafal Over Rice</span><span class="{{ linePrice }}">$10.99</span></p>
      </div>
      <p class="mt-2 font-black">Wrapped in Pita Bread</p>
      <p class="mb-4 font-black">Extra Meat $2.99 | Pita $0.99</p>
      <div class="grid gap-5 sm:grid-cols-2">
        <div>
          <h3 class="{{ sectionHeading }}">Salads Included</h3>
          <ul class="{{ list }} grid-cols-2">
            <li>Lettuce</li><li>Pickle</li><li>Tomato</li><li>Jalapeno</li><li>Onion</li><li>Guacamole</li><li>Cucumber</li><li>Bell Peppers</li><li>Cilantro Mix</li>
          </ul>
        </div>
        <div>
          <h3 class="{{ sectionHeading }}">Sauces <span class="{{ note }} text-sm normal-case">All sauces homemade</span></h3>
          <ul class="{{ list }}">
            <li>White Dill Sauce</li>
            <li>Buffalo Chipotle Mayo</li>
            <li>Mint & Cilantro Mix</li>
          </ul>
        </div>
      </div>
    </article>

    <!-- CHICKEN WINGS -->
    <article id="chicken-wings" class="{{ menuCard }}">
      <h2 class="{{ title }} border-b-2 border-[#c98532] pb-3">Chicken Wings</h2>
      <div class="mt-4 space-y-3">
        <p class="{{ line }}"><span class="{{ lineLabel }}">5 Chicken Wings</span><span class="{{ linePrice }}">$7.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">15 Chicken Wings</span><span class="{{ linePrice }}">$20.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">25 Chicken Wings</span><span class="{{ linePrice }}">$31.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">40 Chicken Wings</span><span class="{{ linePrice }}">$44.99</span></p>
      </div>
      <div class="mt-5 rounded-xl border border-[#c98532] p-4">
        <h3 class="{{ sectionHeading }}">Flavors</h3>
        <p class="font-semibold">Garlic Parmesan, Honey Gold, Lemon Pepper, Mild, Buffalo, Hot, Mango Habanero, Asian Zing</p>
      </div>
    </article>

    <!-- CRISPY FISH SPECIALS -->
    <article id="crispy-fish-specials" class="{{ menuCard }}">
      <h2 class="{{ title }} border-b-2 border-[#c98532] pb-3">Crispy Fish Specials</h2>
      <div class="mt-4 space-y-3">
        <p class="{{ line }}"><span class="{{ lineLabel }}">Crispy Fish & Chips</span><span class="{{ linePrice }}">$12.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">Crispy Fish Sandwich</span><span class="{{ linePrice }}">$12.99</span></p>
        <p class="{{ line }}"><span class="{{ lineLabel }}">Crispy Fish Quesadilla</span><span class="{{ linePrice }}">$12.99</span></p>
      </div>
    </article>

  </div>
</section>
