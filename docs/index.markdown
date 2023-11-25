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
				<img src="meat-thermometer.jpg" class="card-img-top" alt="Meat Thermometer">
				<div class="card-body">
					<h5 class="card-title">Meat Thermometer</h5>
					<p class="card-text">Ensure your prime rib is cooked perfectly with a reliable meat thermometer.</p>
				</div>
			</div>
		</div>

		<!-- Card 2: Roasting Pan -->
		<div class="col-md-4 mb-3">
			<div class="card">
				<img src="roasting-pan.jpg" class="card-img-top" alt="Roasting Pan">
				<div class="card-body">
					<h5 class="card-title">Roasting Pan</h5>
					<p class="card-text">A durable roasting pan is essential for even cooking and easy cleanup.</p>
				</div>
			</div>
		</div>

		<!-- Card 3: Carving Set -->
		<div class="col-md-4 mb-3">
			<div class="card">
				<img src="carving-set.jpg" class="card-img-top" alt="Carving Set">
				<div class="card-body">
					<h5 class="card-title">Carving Set</h5>
					<p class="card-text">A sharp carving set makes serving your prime rib a breeze.</p>
				</div>
			</div>
		</div>
    </div>
</div>
