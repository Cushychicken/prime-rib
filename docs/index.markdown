---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Prime Rib Cooking Time Calculator
---

<div class="row mt-5">
    <div class="frosted-glass">
        <!-- Calculator content -->
		<h1 class="mb-4">Prime Rib Cooking Time Calculator</h1>
		<div class="mb-3">
			<label for="weight" class="form-label">Enter the Weight of the Prime Rib (in pounds):</label>
			<input type="number" id="weight" name="weight" class="form-control">
		</div>

		<div class="mb-3">
			<div class="form-check">
				<input type="radio" id="bonein" name="ribType" value="bonein" class="form-check-input" checked>
				<label class="form-check-label" for="bonein">Bone-in</label>
			</div>
			<div class="form-check">
				<input type="radio" id="boneless" name="ribType" value="boneless" class="form-check-input">
				<label class="form-check-label" for="boneless">Boneless</label>
			</div>
		</div>

		<div class="mb-3">
			<label for="doneness" class="form-label">Select Doneness:</label>
			<select id="doneness" name="doneness" class="form-select">
				<option value="rare">Rare</option>
				<option value="mediumrare" selected>Medium Rare</option>
				<option value="medium">Medium</option>
				<option value="welldone">Well Done</option>
			</select>
		</div>

		<button onclick="calculateCookingTime()" class="btn btn-primary">Calculate Cooking Time</button>

		<p id="result" class="mt-3"></p>
    </div>
</div>

<!-- Tools for Cooking Prime Rib -->
<div class="row mt-5">
    <div class="frosted-glass">
        <!-- Cards for tools -->
		<h2 class="mb-3">Tools for Cooking Prime Rib</h2>

		<div class="row">
		<!-- Card 1: Meat Thermometer -->
		<div class="col-md-4 mb-3">
			<div class="card">
				<img src="/images/meat-thermometer.jpg" class="card-img-top" alt="Meat Thermometer">
				<div class="card-body">
					<h5 class="card-title">
					<a target="_blank" href="https://www.amazon.com/ThermoPro-Thermometer-Grilling-Waterproof-Ambidextrous/dp/B07XXSYLL8/ref=sr_1_7?crid=1WBCMEYQLAPRI&amp;keywords=meat+thermometer&amp;qid=1700936498&amp;s=home-garden&amp;sprefix=meat+therm%252Cgarden%252C92&amp;sr=1-7&_encoding=UTF8&tag=primerib04-20&linkCode=ur2&linkId=d782131a3a0cd972860d5932318e50ce&camp=1789&creative=9325">Digital Thermometer</a>
					</h5>
					<p class="card-text">Ensure your prime rib is cooked perfectly with a reliable meat thermometer.</p>
				</div>
			</div>
		</div>

		<!-- Card 2: Roasting Pan -->
		<div class="col-md-4 mb-3">
			<div class="card">
				<img src="/images/roasting-pan.jpg" class="card-img-top" alt="Roasting Pan">
				<div class="card-body">
					<h5 class="card-title">
				    <a target="_blank" href="https://www.amazon.com/Circulon-56539-Nonstick-Bakeware-Roaster/dp/B00GP3XLYI/ref=lp_289826_1_1?sbo=RZvfv%252F%252FHxDF%252BO5021pAnSA%253D%253D&_encoding=UTF8&tag=primerib04-20&linkCode=ur2&linkId=d0626894cfa95a649a694806301ca7e0&camp=1789&creative=9325">Roasting Pan</a>	
					</h5>
					<p class="card-text">A durable roasting pan is essential for even cooking and easy cleanup.</p>
				</div>
			</div>
		</div>

		<!-- Card 3: Carving Set -->
		<div class="col-md-4 mb-3">
			<div class="card">
				<img src="/images/carving-set.jpg" class="card-img-top" alt="Carving Set">
				<div class="card-body">
					<h5 class="card-title">
					<a target="_blank" href="https://www.amazon.com/HENCKELS-Razor-Sharp-Engineered-Lightweight-Dishwasher/dp/B00GHX5HGG/ref=sr_1_1_sspa?c=ts&amp;keywords=Block%252BKnife%252BSets&amp;qid=1700936669&amp;s=kitchen&amp;sr=1-1-spons&amp;ts_id=409670&amp;ufe=app_do%253Aamzn1.fos.304cacc1-b508-45fb-a37f-a2c47c48c32f&amp;sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&amp;th=1&_encoding=UTF8&tag=primerib04-20&linkCode=ur2&linkId=0d24035259bdafe7652e97283f5c3605&camp=1789&creative=9325">Carving Set</a>
					</h5>
					<p class="card-text">A sharp carving set makes serving your prime rib a breeze.</p>
				</div>
			</div>
		</div>
    </div>
</div>

