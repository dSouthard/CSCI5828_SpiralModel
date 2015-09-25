
<!DOCTYPE html>
<html class="safari">
<head>

<title>
The Spiral Model
</title>
</head>

<body id="public" class="noI" onorientationchange="window.scrollTo(0, 1)">


<div id="container" class="ltr">
	
<header id="header" class="info">
	<h2>The Spiral Model</h2>
	<div>This is my form. Please fill it out. It's awesome!</div>
</header>

	
<ul>
		
	
	
<li id="fo1li1" 		class="likert notranslate
	col4
			 ">
	<table cellspacing="0">
		<caption id="title1">
			Evaluate the following statements.
					</caption>
		<thead>
			<tr>
				<th>&nbsp;</th>
								<td >Strongly Disagree</td>
								<td >Disagree</td>
								<td >Agree</td>
								<td >Strongly Agree</td>
							</tr>
		</thead>
		<tbody>
						<tr class="statement1">
				<th><label for="Field1">Statement One</label></th>
								<td title="Strongly Disagree">
					<input id="Field1_1" 						name="Field1" 						type="radio" 						tabindex="1" 						value="Strongly Disagree" 												onchange="handleInput(this);" 						            												/>
					<label for="Field1_1">1</label>
				</td>
								<td title="Disagree">
					<input id="Field1_2" 						name="Field1" 						type="radio" 						tabindex="2" 						value="Disagree" 												onchange="handleInput(this);" 						            												/>
					<label for="Field1_2">2</label>
				</td>
								<td title="Agree">
					<input id="Field1_3" 						name="Field1" 						type="radio" 						tabindex="3" 						value="Agree" 												onchange="handleInput(this);" 						            												/>
					<label for="Field1_3">3</label>
				</td>
								<td title="Strongly Agree">
					<input id="Field1_4" 						name="Field1" 						type="radio" 						tabindex="4" 						value="Strongly Agree" 												onchange="handleInput(this);" 						            												/>
					<label for="Field1_4">4</label>
				</td>
							</tr>
						<tr class="alt statement2">
				<th><label for="Field2">Statement Two</label></th>
								<td title="Strongly Disagree">
					<input id="Field2_1" 						name="Field2" 						type="radio" 						tabindex="5" 						value="Strongly Disagree" 												onchange="handleInput(this);" 						            												/>
					<label for="Field2_1">1</label>
				</td>
								<td title="Disagree">
					<input id="Field2_2" 						name="Field2" 						type="radio" 						tabindex="6" 						value="Disagree" 												onchange="handleInput(this);" 						            												/>
					<label for="Field2_2">2</label>
				</td>
								<td title="Agree">
					<input id="Field2_3" 						name="Field2" 						type="radio" 						tabindex="7" 						value="Agree" 												onchange="handleInput(this);" 						            												/>
					<label for="Field2_3">3</label>
				</td>
								<td title="Strongly Agree">
					<input id="Field2_4" 						name="Field2" 						type="radio" 						tabindex="8" 						value="Strongly Agree" 												onchange="handleInput(this);" 						            												/>
					<label for="Field2_4">4</label>
				</td>
							</tr>
						<tr class="statement3">
				<th><label for="Field3">Statement Three</label></th>
								<td title="Strongly Disagree">
					<input id="Field3_1" 						name="Field3" 						type="radio" 						tabindex="9" 						value="Strongly Disagree" 												onchange="handleInput(this);" 						            												/>
					<label for="Field3_1">1</label>
				</td>
								<td title="Disagree">
					<input id="Field3_2" 						name="Field3" 						type="radio" 						tabindex="10" 						value="Disagree" 												onchange="handleInput(this);" 						            												/>
					<label for="Field3_2">2</label>
				</td>
								<td title="Agree">
					<input id="Field3_3" 						name="Field3" 						type="radio" 						tabindex="11" 						value="Agree" 												onchange="handleInput(this);" 						            												/>
					<label for="Field3_3">3</label>
				</td>
								<td title="Strongly Agree">
					<input id="Field3_4" 						name="Field3" 						type="radio" 						tabindex="12" 						value="Strongly Agree" 												onchange="handleInput(this);" 						            												/>
					<label for="Field3_4">4</label>
				</td>
							</tr>
					</tbody>
	</table>
	</li>



<li id="fo1li101" 		class="notranslate       ">
	<label class="desc" id="title101" for="Field101">
		Website
			</label>
	<div>
		<input id="Field101" 			name="Field101" 			type="url" 			class="field text medium" 			value="" 			maxlength="255" 			tabindex="13" 						onkeyup="handleInput(this);" 			onchange="handleInput(this);" 			      						/>
	</div>
	</li>



<li id="fo1li102" 		class="time notranslate      ">
	<label class="desc" id="title102" for="Field102">
		Time
			</label>
	<span class="hours">
		<input id="Field102" 			name="Field102" 			type="text" 			class="field text" 			value="" 			size="2" 			maxlength="2" 			tabindex="14" 						onkeyup="handleInput(this);" 			onchange="handleInput(this);" 						      			/>
		<label for="Field102">HH</label>
	</span>
	<span class="symbol minutes">:</span>
	<span class="minutes">
		<input id="Field102-1" 			name="Field102-1" 			type="text" 			class="field text" 			value="" 			size="2" 			maxlength="2" 			tabindex="15" 						onkeyup="handleInput(this);" 			onchange="handleInput(this);" 									/>
		<label for="Field102-1">MM</label>
	</span>
	<span class="symbol seconds">:</span>
	<span class="seconds">
	 	<input id="Field102-2" 			name="Field102-2" 			type="text" 			class="field text" 			value="" 			size="2" 			maxlength="2" 			tabindex="16" 						onkeyup="handleInput(this);" 			onchange="handleInput(this);" 						/>
		<label for="Field102-2">SS</label>
	</span>
	<span class="ampm">
		<select id="Field102-3" 			name="Field102-3" 			class="field select" 			style="width:4em" 			tabindex="17" 						onclick="handleInput(this);" 			onkeyup="handleInput(this);" 						>
			<option value="AM" selected="selected">AM</option>
			<option value="PM" >PM</option>
		</select>
		<label for="Field102-3">AM/PM</label>
	</span>
	</li>


 

	

	</ul>
</form>
 

</div><!--container-->

</body>
</html>
