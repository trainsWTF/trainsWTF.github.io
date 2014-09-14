---
layout: page
---
<script>
	function swapstations(){
	
	    var element=document.getElementById('journey_departure_station');
	    temp=element.value
        	element.value=localStorage.journey_departure_station ;              
        var element2=document.getElementById('journey_arrival_station');
        element.value=element2.value
        element2.value=temp		
	}
	

</script>


<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.4.4/jquery.min.js"></script>
{% include JB/setup %}

<img src="{{ site.url }}/logo.jpg" alt="Logo" width="300"/>

Optimised for mobile - since that's where you're most likely to use it.

Fill in your details below, once you hit 'submit' you'll be sent to the Southeastern site with the same details pre-populated -  you just need to hit 'submit' again on Southeastern's site.

BUT as you type details, the ones that are useful for future submissions are stored locally on your device, to pre-populate this form next time you're here... making it easier to comment in the future

This is the Delay Repay page

[Click for: Customer Comments]({{ site.url }}/setrains)

<b>Mandatory fields for Delay Repay:</b>


<div class="container">
<form id="setrains-form" method="post" action="https://www.southeasternrailway.co.uk/mobile/delay-repay/">


	<div class="col-md-9">
	
     	<div class="row">
       		<div class="col-md-3">
       			<label>Date of delay:</label>
    		</div>
        	<div class="col-md-9">			                                            
				<select name="departure_date_day" id="departure_date_day">
					<option value="1">1</option>
					<option value="2">2</option>
					<option value="3">3</option>
					<option value="4">4</option>
					<option value="5">5</option>
					<option value="6">6</option>
					<option value="7">7</option>
					<option value="8">8</option>
					<option value="9">9</option>
					<option value="10">10</option>
					<option value="11">11</option>
					<option value="12">12</option>
					<option value="13">13</option>
					<option value="14">14</option>
					<option value="15">15</option>
					<option value="16">16</option>
					<option value="17">17</option>
					<option value="18">18</option>
					<option value="19">19</option>
					<option value="20">20</option>
					<option value="21" >21</option>
					<option value="22" >22</option>
					<option value="23" >23</option>
					<option value="24" >24</option>
					<option value="25" >25</option>
					<option value="26" >26</option>
					<option value="27" >27</option>
					<option value="28" >28</option>
					<option value="29" >29</option>
					<option value="30" >30</option>
					<option value="31" >31</option>
				</select>
				<select name="departure_date_month" id="departure_date_month">
					<option value="01">January</option>
					<option value="02">February</option>
					<option value="03">March</option>
					<option value="04">April</option>
					<option value="05">May</option>
					<option value="06">June</option>
					<option value="07">July</option>
					<option value="08">August</option>
					<option value="09">September</option>
					<option value="10">October</option>
					<option value="11">November</option>
					<option value="12">December</option>
				</select>
				<select name="departure_date_year" id="departure_date_year">
					<option value="2014">2014</option>
					<option value="2015">2015</option>
				</select>                                                 
            </div>
        </div>          
     	<div class="row">
       		<div class="col-md-3">
       			<label>Train departure time:</label>
    		</div>
    		<div class="col-md-9">		                       	  
                <select name="departure_time_hours" id="departure_time_hours">
                    <option  value="00">00</option>
                    <option  value="01">01</option>
                    <option  value="02">02</option>
                    <option  value="03">03</option>
                    <option  value="04">04</option>
                    <option  value="05">05</option>
                    <option  value="06">06</option>
                    <option  value="07">07</option>
                    <option  value="08">08</option>
                    <option  value="09">09</option>
                    <option  value="10">10</option>
                    <option  value="11">11</option>
                    <option  value="12">12</option>
                    <option  value="13">13</option>
                    <option  value="14">14</option>
                    <option  value="15">15</option>
                    <option  value="16">16</option>
                    <option  value="17">17</option>
                    <option  value="18">18</option>
                    <option  value="19">19</option>
                    <option  value="20">20</option>
                    <option  value="21">21</option>
                    <option  value="22">22</option>
                    <option  value="23">23</option>
                </select>       
                <select name="departure_time_minutes">
                    <option value="">-</option>
                    <option  value="00">00</option>
                    <option  value="01">01</option>
                    <option  value="02">02</option>
                    <option  value="03">03</option>
                    <option  value="04">04</option>
                    <option  value="05">05</option>
                    <option  value="06">06</option>
                    <option  value="07">07</option>
                    <option  value="08">08</option>
                    <option  value="09">09</option>
                    <option  value="10">10</option>
                    <option  value="11">11</option>
                    <option  value="12">12</option>
                    <option  value="13">13</option>
                    <option  value="14">14</option>
                    <option  value="15">15</option>
                    <option  value="16">16</option>
                    <option  value="17">17</option>
                    <option  value="18">18</option>
                    <option  value="19">19</option>
                    <option  value="20">20</option>
                    <option  value="21">21</option>
                    <option  value="22">22</option>
                    <option  value="23">23</option>
                    <option  value="24">24</option>
                    <option  value="25">25</option>
                    <option  value="26">26</option>
                    <option  value="27">27</option>
                    <option  value="28">28</option>
                    <option  value="29">29</option>
                    <option  value="30">30</option>
                    <option  value="31">31</option>
                    <option  value="32">32</option>
                    <option  value="33">33</option>
                    <option  value="34">34</option>
                    <option  value="35">35</option>
                    <option  value="36">36</option>
                    <option  value="37">37</option>
                    <option  value="38">38</option>
                    <option  value="39">39</option>
                    <option  value="40">40</option>
                    <option  value="41">41</option>
                    <option  value="42">42</option>
                    <option  value="43">43</option>
                    <option  value="44">44</option>
                    <option  value="45">45</option>
                    <option  value="46">46</option>
                    <option  value="47">47</option>
                    <option  value="48">48</option>
                    <option  value="49">49</option>
                    <option  value="50">50</option>
                    <option  value="51">51</option>
                    <option  value="52">52</option>
                    <option  value="53">53</option>
                    <option  value="54">54</option>
                    <option  value="55">55</option>
                    <option  value="56">56</option>
                    <option  value="57">57</option>
                    <option  value="58">58</option>
                    <option  value="59">59</option>
                </select>
			</div>
		</div>
                                        

     	<div class="row">
       		<div class="col-md-3">
       			<label>Departure station:</label>
    		</div>
        	<div class="col-md-9">		
    			<select name="journey_departure_station" id="journey_departure_station" class="stored">
    				<option value=""></option>
					<option value="ABW">Abbey Wood</option>
					<option value="ADM">Adisham</option>
					<option value="AYP">Albany Park</option>
					<option value="AFK">Ashford International</option>
					<option value="AYL">Aylesford</option>
					<option value="AYH">Aylesham</option>
					<option value="BMG">Barming</option>
					<option value="BNH">Barnehurst</option>
					<option value="BBL">Bat & Ball</option>
					<option value="BAT">Battle</option>
					<option value="BSD">Bearsted</option>
					<option value="BEC">Beckenham Hill</option>
					<option value="BKJ">Beckenham Junction</option>
					<option value="BKS">Bekesbourne</option>
					<option value="BGM">Bellingham</option>
					<option value="BEG">Beltring</option>
					<option value="BVD">Belvedere</option>
					<option value="BXY">Bexley</option>
					<option value="BXH">Bexleyheath</option>
					<option value="BKL">Bickley</option>
					<option value="BCH">Birchington-on-Sea</option>
					<option value="BKH">Blackheath</option>
					<option value="BRG">Borough Green & Wrotham</option>
					<option value="BRX">Brixton</option>
					<option value="BSR">Broadstairs</option>
					<option value="BMN">Bromley North</option>
					<option value="BMS">Bromley South</option>
					<option value="CBE">Canterbury East</option>
					<option value="CBW">Canterbury West</option>
					<option value="CTF">Catford</option>
					<option value="CFB">Catford Bridge</option>
					<option value="CHG">Charing</option>
					<option value="CTN">Charlton</option>
					<option value="CRT">Chartham</option>
					<option value="CTM">Chatham</option>
					<option value="CLD">Chelsfield</option>
					<option value="CSW">Chestfield & Swalecliffe</option>
					<option value="CIL">Chilham</option>
					<option value="CIT">Chislehurst</option>
					<option value="CTK">City Thameslink</option>
					<option value="CLK">Clock House</option>
					<option value="CRY">Crayford</option>
					<option value="CFT">Crofton Park</option>
					<option value="CWU">Crowhurst</option>
					<option value="CUX">Cuxton</option>
					<option value="DFD">Dartford</option>
					<option value="DEA">Deal</option>
					<option value="DMK">Denmark Hill</option>
					<option value="DEP">Deptford</option>
					<option value="DVP">Dover Priory</option>
					<option value="DMP">Dumpton Park</option>
					<option value="DNG">Dunton Green</option>
					<option value="EFL">East Farleigh</option>
					<option value="EML">East Malling</option>
					<option value="EBD">Ebbsfleet Intl</option>
					<option value="EDN">Eden Park</option>
					<option value="EPH">Elephant & Castle</option>
					<option value="ELE">Elmers End</option>
					<option value="ESD">Elmstead Woods</option>
					<option value="ELW">Eltham</option>
					<option value="ERH">Erith</option>
					<option value="ETC">Etchingham</option>
					<option value="EYN">Eynsford</option>
					<option value="FCN">Falconwood</option>
					<option value="FNR">Farningham Road</option>
					<option value="ZFD">Farringdon</option>
					<option value="FAV">Faversham</option>
					<option value="FKC">Folkestone Central</option>
					<option value="FKW">Folkestone West</option>
					<option value="FRT">Frant</option>
					<option value="GLM">Gillingham (Kent)</option>
					<option value="GRV">Gravesend</option>
					<option value="GNH">Greenhithe</option>
					<option value="GNW">Greenwich</option>
					<option value="GRP">Grove Park</option>
					<option value="HAI">Halling</option>
					<option value="HRM">Harrietsham</option>
					<option value="HGS">Hastings</option>
					<option value="HYS">Hayes</option>
					<option value="HCN">Headcorn</option>
					<option value="HNB">Herne Bay</option>
					<option value="HNH">Herne Hill</option>
					<option value="HIB">High Brooms</option>
					<option value="HGM">Higham</option>
					<option value="HLB">Hildenborough</option>
					<option value="HGR">Hither Green</option>
					<option value="HBN">Hollingbourne</option>
					<option value="KSN">Kearsney</option>
					<option value="KMS">Kemsing</option>
					<option value="KML">Kemsley</option>
					<option value="KTH">Kent House</option>
					<option value="KDB">Kidbrooke</option>
					<option value="KCK">Knockholt</option>
					<option value="LAD">Ladywell</option>
					<option value="LEE">Lee</option>
					<option value="LEN">Lenham</option>
					<option value="LEW">Lewisham</option>
					<option value="BFR">London Blackfriars</option>
					<option value="LBG">London Bridge</option>
					<option value="CST">London Cannon Street</option>
					<option value="CHX">London Charing Cross</option>
					<option value="STP">London St Pancras Intl</option>
					<option value="VIC">London Victoria</option>
					<option value="WAE">London Waterloo East</option>
					<option value="LGF">Longfield</option>
					<option value="LGJ">Loughborough Junction</option>
					<option value="LSY">Lower Sydenham</option>
					<option value="MDB">Maidstone Barracks</option>
					<option value="MDE">Maidstone East</option>
					<option value="MDW">Maidstone West</option>
					<option value="MRN">Marden</option>
					<option value="MAR">Margate</option>
					<option value="MTM">Martin Mill</option>
					<option value="MZH">Maze Hill</option>
					<option value="MEP">Meopham</option>
					<option value="MSR">Minster</option>
					<option value="MTG">Mottingham</option>
					<option value="NBC">New Beckenham</option>
					<option value="NWX">New Cross</option>
					<option value="NEH">New Eltham</option>
					<option value="NHE">New Hythe</option>
					<option value="NGT">Newington</option>
					<option value="NFL">Northfleet</option>
					<option value="NHD">Nunhead</option>
					<option value="ORE">Ore</option>
					<option value="ORP">Orpington</option>
					<option value="OTF">Otford</option>
					<option value="PDW">Paddock Wood</option>
					<option value="PMR">Peckham Rye</option>
					<option value="PNE">Penge East</option>
					<option value="PET">Petts Wood</option>
					<option value="PLC">Pluckley</option>
					<option value="PLU">Plumstead</option>
					<option value="QBR">Queenborough</option>
					<option value="RAI">Rainham</option>
					<option value="RAM">Ramsgate</option>
					<option value="RVB">Ravensbourne</option>
					<option value="RBR">Robertsbridge</option>
					<option value="RTR">Rochester</option>
					<option value="RYE">Rye</option>
					<option value="SDG">Sandling</option>
					<option value="SDW">Sandwich</option>
					<option value="SEG">Selling</option>
					<option value="SEV">Sevenoaks</option>
					<option value="SSS">Sheerness on Sea</option>
					<option value="SPH">Shepherds Well</option>
					<option value="SEH">Shoreham</option>
					<option value="SRT">Shortlands</option>
					<option value="SID">Sidcup</option>
					<option value="SIT">Sittingbourne</option>
					<option value="SGR">Slade Green</option>
					<option value="SDA">Snodland</option>
					<option value="SWO">Snowdown</option>
					<option value="SOR">Sole Street</option>
					<option value="SAJ">St Johns</option>
					<option value="SLQ">St Leonards Warrior Square</option>
					<option value="SMY">St Mary Cray</option>
					<option value="SPU">Staplehurst</option>
					<option value="SCG">Stone Crossing</option>
					<option value="SOG">Stonegate</option>
					<option value="SFA">Stratford Intl</option>
					<option value="SOO">Strood</option>
					<option value="STU">Sturry</option>
					<option value="SUP">Sundridge Park</option>
					<option value="SWL">Swale</option>
					<option value="SAY">Swanley</option>
					<option value="SWM">Swanscombe</option>
					<option value="SYH">Sydenham Hill</option>
					<option value="TEY">Teynham</option>
					<option value="TON">Tonbridge</option>
					<option value="TBW">Tunbridge Wells</option>
					<option value="WAD">Wadhurst</option>
					<option value="WAM">Walmer</option>
					<option value="WTR">Wateringbury</option>
					<option value="WLI">Welling</option>
					<option value="WDU">West Dulwich</option>
					<option value="WMA">West Malling</option>
					<option value="WLD">West St Leonards</option>
					<option value="WWI">West Wickham</option>
					<option value="WCB">Westcombe Park</option>
					<option value="WHA">Westenhanger</option>
					<option value="WGA">Westgate on Sea</option>
					<option value="WHI">Whitstable</option>
					<option value="WWA">Woolwich Arsenal</option>
					<option value="WWD">Woolwich Dockyard</option>
					<option value="WYE">Wye</option>
					<option value="YAL">Yalding</option>                            
				</select>
    		</div>
    	</div>  
    	
 		<div class="row">
       		<div class="col-md-3">
       			<label>Arrival station:</label>
    		</div>
        	<div class="col-md-9">		
    			<select name="journey_arrival_station" id="journey_arrival_station" class="stored">
    				<option value=""></option>
					<option value="ABW">Abbey Wood</option>
					<option value="ADM">Adisham</option>
					<option value="AYP">Albany Park</option>
					<option value="AFK">Ashford International</option>
					<option value="AYL">Aylesford</option>
					<option value="AYH">Aylesham</option>
					<option value="BMG">Barming</option>
					<option value="BNH">Barnehurst</option>
					<option value="BBL">Bat & Ball</option>
					<option value="BAT">Battle</option>
					<option value="BSD">Bearsted</option>
					<option value="BEC">Beckenham Hill</option>
					<option value="BKJ">Beckenham Junction</option>
					<option value="BKS">Bekesbourne</option>
					<option value="BGM">Bellingham</option>
					<option value="BEG">Beltring</option>
					<option value="BVD">Belvedere</option>
					<option value="BXY">Bexley</option>
					<option value="BXH">Bexleyheath</option>
					<option value="BKL">Bickley</option>
					<option value="BCH">Birchington-on-Sea</option>
					<option value="BKH">Blackheath</option>
					<option value="BRG">Borough Green & Wrotham</option>
					<option value="BRX">Brixton</option>
					<option value="BSR">Broadstairs</option>
					<option value="BMN">Bromley North</option>
					<option value="BMS">Bromley South</option>
					<option value="CBE">Canterbury East</option>
					<option value="CBW">Canterbury West</option>
					<option value="CTF">Catford</option>
					<option value="CFB">Catford Bridge</option>
					<option value="CHG">Charing</option>
					<option value="CTN">Charlton</option>
					<option value="CRT">Chartham</option>
					<option value="CTM">Chatham</option>
					<option value="CLD">Chelsfield</option>
					<option value="CSW">Chestfield & Swalecliffe</option>
					<option value="CIL">Chilham</option>
					<option value="CIT">Chislehurst</option>
					<option value="CTK">City Thameslink</option>
					<option value="CLK">Clock House</option>
					<option value="CRY">Crayford</option>
					<option value="CFT">Crofton Park</option>
					<option value="CWU">Crowhurst</option>
					<option value="CUX">Cuxton</option>
					<option value="DFD">Dartford</option>
					<option value="DEA">Deal</option>
					<option value="DMK">Denmark Hill</option>
					<option value="DEP">Deptford</option>
					<option value="DVP">Dover Priory</option>
					<option value="DMP">Dumpton Park</option>
					<option value="DNG">Dunton Green</option>
					<option value="EFL">East Farleigh</option>
					<option value="EML">East Malling</option>
					<option value="EBD">Ebbsfleet Intl</option>
					<option value="EDN">Eden Park</option>
					<option value="EPH">Elephant & Castle</option>
					<option value="ELE">Elmers End</option>
					<option value="ESD">Elmstead Woods</option>
					<option value="ELW">Eltham</option>
					<option value="ERH">Erith</option>
					<option value="ETC">Etchingham</option>
					<option value="EYN">Eynsford</option>
					<option value="FCN">Falconwood</option>
					<option value="FNR">Farningham Road</option>
					<option value="ZFD">Farringdon</option>
					<option value="FAV">Faversham</option>
					<option value="FKC">Folkestone Central</option>
					<option value="FKW">Folkestone West</option>
					<option value="FRT">Frant</option>
					<option value="GLM">Gillingham (Kent)</option>
					<option value="GRV">Gravesend</option>
					<option value="GNH">Greenhithe</option>
					<option value="GNW">Greenwich</option>
					<option value="GRP">Grove Park</option>
					<option value="HAI">Halling</option>
					<option value="HRM">Harrietsham</option>
					<option value="HGS">Hastings</option>
					<option value="HYS">Hayes</option>
					<option value="HCN">Headcorn</option>
					<option value="HNB">Herne Bay</option>
					<option value="HNH">Herne Hill</option>
					<option value="HIB">High Brooms</option>
					<option value="HGM">Higham</option>
					<option value="HLB">Hildenborough</option>
					<option value="HGR">Hither Green</option>
					<option value="HBN">Hollingbourne</option>
					<option value="KSN">Kearsney</option>
					<option value="KMS">Kemsing</option>
					<option value="KML">Kemsley</option>
					<option value="KTH">Kent House</option>
					<option value="KDB">Kidbrooke</option>
					<option value="KCK">Knockholt</option>
					<option value="LAD">Ladywell</option>
					<option value="LEE">Lee</option>
					<option value="LEN">Lenham</option>
					<option value="LEW">Lewisham</option>
					<option value="BFR">London Blackfriars</option>
					<option value="LBG">London Bridge</option>
					<option value="CST">London Cannon Street</option>
					<option value="CHX">London Charing Cross</option>
					<option value="STP">London St Pancras Intl</option>
					<option value="VIC">London Victoria</option>
					<option value="WAE">London Waterloo East</option>
					<option value="LGF">Longfield</option>
					<option value="LGJ">Loughborough Junction</option>
					<option value="LSY">Lower Sydenham</option>
					<option value="MDB">Maidstone Barracks</option>
					<option value="MDE">Maidstone East</option>
					<option value="MDW">Maidstone West</option>
					<option value="MRN">Marden</option>
					<option value="MAR">Margate</option>
					<option value="MTM">Martin Mill</option>
					<option value="MZH">Maze Hill</option>
					<option value="MEP">Meopham</option>
					<option value="MSR">Minster</option>
					<option value="MTG">Mottingham</option>
					<option value="NBC">New Beckenham</option>
					<option value="NWX">New Cross</option>
					<option value="NEH">New Eltham</option>
					<option value="NHE">New Hythe</option>
					<option value="NGT">Newington</option>
					<option value="NFL">Northfleet</option>
					<option value="NHD">Nunhead</option>
					<option value="ORE">Ore</option>
					<option value="ORP">Orpington</option>
					<option value="OTF">Otford</option>
					<option value="PDW">Paddock Wood</option>
					<option value="PMR">Peckham Rye</option>
					<option value="PNE">Penge East</option>
					<option value="PET">Petts Wood</option>
					<option value="PLC">Pluckley</option>
					<option value="PLU">Plumstead</option>
					<option value="QBR">Queenborough</option>
					<option value="RAI">Rainham</option>
					<option value="RAM">Ramsgate</option>
					<option value="RVB">Ravensbourne</option>
					<option value="RBR">Robertsbridge</option>
					<option value="RTR">Rochester</option>
					<option value="RYE">Rye</option>
					<option value="SDG">Sandling</option>
					<option value="SDW">Sandwich</option>
					<option value="SEG">Selling</option>
					<option value="SEV">Sevenoaks</option>
					<option value="SSS">Sheerness on Sea</option>
					<option value="SPH">Shepherds Well</option>
					<option value="SEH">Shoreham</option>
					<option value="SRT">Shortlands</option>
					<option value="SID">Sidcup</option>
					<option value="SIT">Sittingbourne</option>
					<option value="SGR">Slade Green</option>
					<option value="SDA">Snodland</option>
					<option value="SWO">Snowdown</option>
					<option value="SOR">Sole Street</option>
					<option value="SAJ">St Johns</option>
					<option value="SLQ">St Leonards Warrior Square</option>
					<option value="SMY">St Mary Cray</option>
					<option value="SPU">Staplehurst</option>
					<option value="SCG">Stone Crossing</option>
					<option value="SOG">Stonegate</option>
					<option value="SFA">Stratford Intl</option>
					<option value="SOO">Strood</option>
					<option value="STU">Sturry</option>
					<option value="SUP">Sundridge Park</option>
					<option value="SWL">Swale</option>
					<option value="SAY">Swanley</option>
					<option value="SWM">Swanscombe</option>
					<option value="SYH">Sydenham Hill</option>
					<option value="TEY">Teynham</option>
					<option value="TON">Tonbridge</option>
					<option value="TBW">Tunbridge Wells</option>
					<option value="WAD">Wadhurst</option>
					<option value="WAM">Walmer</option>
					<option value="WTR">Wateringbury</option>
					<option value="WLI">Welling</option>
					<option value="WDU">West Dulwich</option>
					<option value="WMA">West Malling</option>
					<option value="WLD">West St Leonards</option>
					<option value="WWI">West Wickham</option>
					<option value="WCB">Westcombe Park</option>
					<option value="WHA">Westenhanger</option>
					<option value="WGA">Westgate on Sea</option>
					<option value="WHI">Whitstable</option>
					<option value="WWA">Woolwich Arsenal</option>
					<option value="WWD">Woolwich Dockyard</option>
					<option value="WYE">Wye</option>
					<option value="YAL">Yalding</option>                            
				</select>
    		</div>
    	</div> 
    	<div class="row">
    		<a onclick="swapstations()">Swap Arrival/Departure stations</a>  
    	</div>	
    	<div class="row">
       		<div class="col-md-3">
    			<label>Length of delay:</label>
    		</div>
        	<div class="col-md-9">		    	
        		<select name="delay_length" id="delay_length">
                    <option value="30-59 mins">30-59 minutes</option>
                    <option value="60-119 mins">60-119 minutes</option>
                    <option value="120+ mins">120+ minutes</option>
                </select>
			</div>
    	</div>
    	<div class="row">
       		<div class="col-md-3">
    			<label>Reason for delay:</label>
    		</div>
        	<div class="col-md-9">		
        		<select name="delay_reason" id="delay_reason">
                    <option value="">Select reason for delay</option>
                    <option value="Train Delayed">Train Delayed</option>
                    <option value="Train Diverted">Train Diverted</option>
                    <option value="Train Cancelled">Train Cancelled</option>
                    <option value="Journey Abandoned">Journey Abandoned</option>
                </select>
        	</div>
        </div>   
    	<div class="row">
       		<div class="col-md-3">
    			<label>Ticket type:</label>
    		</div>
        	<div class="col-md-9">	
				<select name="ticket_type" id="ticket_type" class="stored">
                    <option selected="selected" value="">Select ticket type</option>
                    <option value="single journey">Single Journey</option>
                    <option value="return">Return Journey</option>
                    <option value="7 day season">7 Day Season</option>
                    <option value="monthly season">Monthly Season</option>
                    <option value="quarterly season">Quarterly Season</option>
                    <option value="annual season">Annual Season</option>
                    <option value="oyster payg">Oyster PAYG</option>
                </select>
			</div>
		</div>
    	<div class="row">
       		<div class="col-md-3">
    			<label>Ticket cost:</label>
    		</div>
        	<div class="col-md-9">			
                &pound;
                <input type="text" value="" name="ticket_cost_pound" style="width:45px;" maxlength="4" id="ticket_cost_pound" class="stored">
                .
                <input type="text" value="" name="ticket_cost_pence" style="width:25px;" maxlength="2" id="ticket_cost_pence" class="stored">
            </div>
		</div>
		<div class="row">
				Submit your claim to Southeastern. 
       			Check your details on their site, attach a photo of your ticket, then hit 'Send Message'
       	</div>
    	<div class="row">	
    		<input type="submit" class="demo-button" formaction="https://www.southeasternrailway.co.uk/mobile/delay-repay/" value="Go to Delay Repay form" />

    	</div>
  	
    	<div class="row">
    		These fields are required for Delay Repay - once you fill this in once your browser will remember for your next Delay Repay claim or Customer Service contact
    	</div>
    	<div class="row">
       		<div class="col-md-3">
    			<label>Title:</label>
         	</div>
         	
        	<div class="col-md-9">
        		<select name="name_title" id="name_title" class="stored">
        		<option value="Mr">Mr</option>
        		<option value="Ms">Ms</option>
        		<option value="Miss">Miss</option>
        		<option value="Mrs">Mrs</option>
        		<option value="Dr">Dr</option>
        		<option value="Other">Other</option>
        		</select>
    		</div>
    	</div>

    	<div class="row">
       		<div class="col-md-3">
    			<label>Surname:</label>
         	</div>
        	<div class="col-md-9">
    			<input type="text" name="surname" id="surname" class="stored" value="" />
    		</div>
    	</div>
    	<div class="row">
       		<div class="col-md-3">
    			<label>Email:</label>
    		</div>
        	<div class="col-md-9">	
    			<input type="email" name="email" id="email" class="stored" value="" />
			</div>
    	</div>

    	<div class="row">
       		<div class="col-md-3">
    			<label>First name:</label>
         	</div>
        	<div class="col-md-9">
    			<input type="text" name="first_name" id="first_name" class="stored" value="" />
    		</div>
    	</div>
    	<div class="row">
       		<div class="col-md-3">
    			<label>Address Line 1:</label>
    		</div>
        	<div class="col-md-9">	
    			<input type="text" name="address_line_1" id="address_line_1" class="stored" value="" />
			</div>
    	</div>  
    	<div class="row">
       		<div class="col-md-3">
    			<label>Address Line 2:</label>
    		</div>
        	<div class="col-md-9">	
    			<input type="text" name="address_line_2" id="address_line_2" class="stored" value="" />
			</div>
    	</div> 
    	

    	<div class="row">
       		<div class="col-md-3">
    			<label>Town/City:</label>
    		</div>
        	<div class="col-md-9">	
    			<input type="text" name="town_or_city" id="town_or_city" class="stored" value="" />
			</div>
    	</div>      
	    	
    	<div class="row">
       		<div class="col-md-3">
    			<label>Postcode:</label>
    		</div>
        	<div class="col-md-9">	
    			<input type="text" name="post_code" id="post_code" class="stored" value="" />
			</div>
    	</div>   
    	  	
    	<div class="row">
       		<div class="col-md-3">
    			<label>County:</label>
    		</div>
        	<div class="col-md-9">	
    			<input type="text" name="county" id="county" class="stored" value="" />
			</div>
    	</div>   

    	<div class="row">
       		<div class="col-md-3">
    			<label>Telephone:</label>
    		</div>
        	<div class="col-md-9">	
    			<input type="text" name="telephone" id="telephone" class="stored" value="" />
			</div>
    	</div>    	
    	<div class="row">	
    		<input type="submit" class="demo-button" formaction="https://www.southeasternrailway.co.uk/mobile/delay-repay/" value="Go to Delay Repay form" />

    	</div>

	</div>
</form>
    <div class="col-md-3">

<a class="twitter-timeline" href="https://twitter.com/TrainsWTF" data-widget-id="501443537091575808">Tweets by @TrainsWTF</a>
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>



    </div>



<script type="text/javascript">
$(document).ready(function () {
    function init() {


       	var now = new Date();


    	var element=document.getElementById('departure_date_day');
    	element.value=now.getDate();
    	var element=document.getElementById('departure_date_month');
    	if (now.getMonth()<9){
    		month=now.getMonth()+1;
    		element.value='0'+month.toString();
    	}
    	else{
    		element.value=now.getMonth()+1;
    	}    	
    	var element=document.getElementById('departure_date_year');
    	element.value=now.getFullYear();
    	
    	
     	var element=document.getElementById('departure_time_hours');

    	cur_hours=now.getHours()
    	cur_mins=now.getMinutes();

    	if (cur_mins<30){
    		cur_hours=cur_hours-1;
    	}

    	element.value=cur_hours;     	
        if (localStorage.name_title) {
        	var element=document.getElementById('name_title');
        	element.value=localStorage.name_title ;              
        }
        if (localStorage.surname) {
            $('#surname').val(localStorage.surname);
        }        
        if (localStorage.email) {
            $('#email').val(localStorage.email);
        }

        if (localStorage.journey_departure_station) {
        	var element=document.getElementById('journey_departure_station');
        	element.value=localStorage.journey_departure_station ;              
        } 
        if (localStorage.journey_arrival_station) {
        	var element=document.getElementById('journey_arrival_station');
        	element.value=localStorage.journey_arrival_station ;              
        } 
        if (localStorage.first_name) {
            $('#first_name').val(localStorage.first_name);
        }
        if (localStorage.address_line_1) {
            $('#address_line_1').val(localStorage.address_line_1);
        }
        if (localStorage.address_line_2) {
            $('#address_line_2').val(localStorage.address_line_2);
        }
        if (localStorage.town_or_city) {
            $('#town_or_city').val(localStorage.town_or_city);
        }
    	if (localStorage.post_code) {
            $('#post_code').val(localStorage.post_code);
        }      
    	if (localStorage.county) {
            $('#county').val(localStorage.county);
        }              
      	if (localStorage.telephone) {
            $('#telephone').val(localStorage.telephone);
        }         
       
        //optional fields:
        if (localStorage.forenames) {
            $('#forenames').val(localStorage.forenames);
        }
        if (localStorage["address1"]) {
            $('#address1').val(localStorage["address1"]);
        }
        if (localStorage["address2"]) {
            $('#address2').val(localStorage["address2"]);
        }
        if (localStorage["city"]) {
            $('#city').val(localStorage["city"]);
        }
        if (localStorage["postcode"]) {
            $('#postcode').val(localStorage["postcode"]);
        }
        if (localStorage["county"]) {
            $('#county').val(localStorage["county"]);
        }
        if (localStorage.telephone) {
        	var element=document.getElementById('telephone');
        	element.value=localStorage.telephone ;   
        }         
        if (localStorage.ticket_type) {
        	var element=document.getElementById('ticket_type');
        	element.value=localStorage.ticket_type ;         
        } 
        if (localStorage.ticket_cost_pound) {
        	var element=document.getElementById('ticket_cost_pound');
        	element.value=localStorage.ticket_cost_pound ;         
        } 
        if (localStorage.ticket_cost_pence) {
        	var element=document.getElementById('ticket_cost_pence');
        	element.value=localStorage.ticket_cost_pence ;         
        }                         

        //if (localStorage["yourcomments"]) {
        //    $('#yourcomments').val(localStorage["yourcomments"]);
        //}
        if (localStorage.arrstation) {
        	var element=document.getElementById('arrstation');
        	element.value=localStorage.arrstation ;         
        }             
    }
	init();
});
$('.stored').change(function () {
    localStorage[$(this).attr('name')] = $(this).val();
});




	
$('#localStorageTest').submit(function() {
	//localStorage.clear();
});


jQuery(document).ready(function($) {
// Track submission events.
  $('#setrains-form').submit(function() {
        _gaq.push(['_trackEvent', 'submit', 'setrains_submit']);
  });
});

</script>
<script type="text/javascript">
(function( win ){
	var doc = win.document;
   	
	// If there's a hash, or addEventListener is undefined, stop here
	if( !location.hash && win.addEventListener ){
		//scroll to 1
		window.scrollTo( 0, 1 );
		var scrollTop = 1,
			getScrollTop = function(){
				return win.pageYOffset || doc.compatMode === "CSS1Compat" && doc.documentElement.scrollTop || doc.body.scrollTop || 0;
			},
			//reset to 0 on bodyready, if needed
			bodycheck = setInterval(function(){
				if( doc.body ){
					clearInterval( bodycheck );
					scrollTop = getScrollTop();
					win.scrollTo( 0, scrollTop === 1 ? 0 : 1 );
				}	
			}, 15 );
		win.addEventListener( "load", function(){
			setTimeout(function(){
					//reset to hide addr bar at onload
					win.scrollTo( 0, scrollTop === 1 ? 0 : 1 );
			}, 0);
		} );
	}
})( this );
</script>        
