---
layout: page
---
<script>
	function filltoday(){
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

	}
	

</script>


<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.4.4/jquery.min.js"></script>
{% include JB/setup %}

<img src="{{ site.url }}/logo.jpg" alt="Logo" width="300"/>

Optimised for mobile - since that's where you're most likely to use it.

Fill in your details below, once you hit 'submit' you'll be sent to the Southeastern site with the same details pre-populated -  you just need to hit 'submit' again on Southeastern's site.

BUT as you type details, the ones that are useful for future submissions are stored locally on your device, to pre-populate this form next time you're here... making it easier to comment in the future

This is the Customer Comments page

[Click for: Delay Repay]({{ site.url }}/setrains_dr)

<b>Mandatory fields:</b>

Select
DELAY REPAY
COMMENT
(these will then rewrite form data ready for the submit, and also restyle the page for the correct data, and pre-pop with today's date)

<div class="container">
<form id="setrains-form" method="post" action="https://www.southeasternrailway.co.uk/mobile/contact-us/feedback-form">


	<div class="col-md-9">
	
    	<div class="row">
       		<div class="col-md-3">
    			<label>Title:</label>
         	</div>
         	
        	<div class="col-md-9">
        		<select name="title" id="title" class="stored">
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
    			<label>Subject:</label>
    		</div>
        	<div class="col-md-9">		
   		 		<select name="feedback_subject" id="feedback_subject" class="stored">
					<option value="" title="Select feedback subject">Select feedback subject</option>
					<option value="Safety" >Safety</option>
					<option value="Disruption" >Disruption</option>
					<option value="Information" >Information</option>
					<option value="Assisted Travel" >Assisted Travel</option>
					<option value="Online ticket purchasing" >Online ticket purchasing</option>
					<option value="London Bridge works" >London Bridge works</option>
					<option value="Our stations" >Our stations</option>
					<option value="Our trains" >Our trains</option>
					<option value="Previous correspondence" >Previous correspondence</option>
              </select>
			</div>
    	</div>
    	<div class="row">
       		<div class="col-md-3">
    			<label>Feedback type:</label>
    		</div>
        	<div class="col-md-9">		
    			<select name="feedback_type"  id="feedback_type" class="stored">
					<option value="" title="Select feedback type">Select feedback type</option>
					<option value="Enquiry"  >Enquiry</option>
					<option value="Feedback"  >Feedback</option>
					<option value="Complaint"  >Complaint</option>
					<option value="Praise"  >Praise</option>
				</select>
        	</div>
        </div>                             
                                        
    	<div class="row">
       		<div class="col-md-3">
    			<label>Message:</label>
    		</div>
        	<div class="col-md-9">		
   		 		<textarea name="your_comments" id="your_comments" rows="10" cols="30"></textarea>
			</div>
    	</div>
 		<div class="row">
				Submit your claim to Southeastern. 
       			Check your details on their site, then hit 'Send Message'
       	</div>
    	<div class="row">	
    		<input type="submit" class="demo-button" formaction="https://www.southeasternrailway.co.uk/mobile/contact-us/feedback-form" value="Go to Customer Comments form" />

    	</div>   	
    	
    	<div class="row">
    		These fields aren't required on the Southeastern website, however if you want to, you can fill them out - they'll be stored too!
    	</div>    	
    	

     	<div class="row">
       		<div class="col-md-3">
       			<label>Departure station:</label>
    		</div>
        	<div class="col-md-9">		
    			<select name="journey_departure_station" id="journey_departure_station" class="stored">
					<option value=""></option>
					<option  value="Abbey Wood [ABW]">Abbey Wood</option>
					<option value="Adisham [ADM]">Adisham</option>
					<option value="Albany Park [AYP]">Albany Park</option>
					<option value="Ashford International [AFK]">Ashford International</option>
					<option value="Aylesford [AYL]">Aylesford</option>
					<option value="Aylesham [AYH]">Aylesham</option>
					<option value="Barming [BMG]">Barming</option>
					<option value="Barnehurst [BNH]">Barnehurst</option>
					<option value="Bat & Ball [BBL]">Bat & Ball</option>
					<option value="Battle [BAT]">Battle</option>
					<option value="Bearsted [BSD]">Bearsted</option>
					<option value="Beckenham Hill [BEC]">Beckenham Hill</option>
					<option value="Beckenham Junction [BKJ]">Beckenham Junction</option>
					<option value="Bekesbourne [BKS]">Bekesbourne</option>
					<option value="Bellingham [BGM]">Bellingham</option>
					<option value="Beltring [BEG]">Beltring</option>
					<option value="Belvedere [BVD]">Belvedere</option>
					<option value="Bexley [BXY]">Bexley</option>
					<option value="Bexleyheath [BXH]">Bexleyheath</option>
					<option value="Bickley [BKL]">Bickley</option>
					<option value="Birchington-on-Sea [BCH]">Birchington-on-Sea</option>
					<option value="Blackheath [BKH]">Blackheath</option>
					<option value="Borough Green & Wrotham [BRG]">Borough Green & Wrotham</option>
					<option value="Brixton [BRX]">Brixton</option>
					<option value="Broadstairs [BSR]">Broadstairs</option>
					<option value="Bromley North [BMN]">Bromley North</option>
					<option value="Bromley South [BMS]">Bromley South</option>
					<option value="Canterbury East [CBE]">Canterbury East</option>
					<option value="Canterbury West [CBW]">Canterbury West</option>
					<option value="Catford [CTF]">Catford</option>
					<option value="Catford Bridge [CFB]">Catford Bridge</option>
					<option value="Charing [CHG]">Charing</option>
					<option value="Charlton [CTN]">Charlton</option>
					<option value="Chartham [CRT]">Chartham</option>
					<option value="Chatham [CTM]">Chatham</option>
					<option value="Chelsfield [CLD]">Chelsfield</option>
					<option value="Chestfield & Swalecliffe [CSW]">Chestfield & Swalecliffe</option>
					<option value="Chilham [CIL]">Chilham</option>
					<option value="Chislehurst [CIT]">Chislehurst</option>
					<option value="City Thameslink [CTK]">City Thameslink</option>
					<option value="Clock House [CLK]">Clock House</option>
					<option value="Crayford [CRY]">Crayford</option>
					<option value="Crofton Park [CFT]">Crofton Park</option>
					<option value="Crowhurst [CWU]">Crowhurst</option>
					<option value="Cuxton [CUX]">Cuxton</option>
					<option value="Dartford [DFD]">Dartford</option>
					<option value="Deal [DEA]">Deal</option>
					<option value="Denmark Hill [DMK]">Denmark Hill</option>
					<option value="Deptford [DEP]">Deptford</option>
					<option value="Dover Priory [DVP]">Dover Priory</option>
					<option value="Dumpton Park [DMP]">Dumpton Park</option>
					<option value="Dunton Green [DNG]">Dunton Green</option>
					<option value="East Farleigh [EFL]">East Farleigh</option>
					<option value="East Malling [EML]">East Malling</option>
					<option value="Ebbsfleet International [EBD]">Ebbsfleet International</option>
					<option value="Eden Park [EDN]">Eden Park</option>
					<option value="Elephant & Castle [EPH]">Elephant & Castle</option>
					<option value="Elmers End [ELE]">Elmers End</option>
					<option value="Elmstead Woods [ESD]">Elmstead Woods</option>
					<option value="Eltham [ELW]">Eltham</option>
					<option value="Erith [ERH]">Erith</option>
					<option value="Etchingham [ETC]">Etchingham</option>
					<option value="Eynsford [EYN]">Eynsford</option>
					<option value="Falconwood [FCN]">Falconwood</option>
					<option value="Farningham Road [FNR]">Farningham Road</option>
					<option value="Farringdon [ZFD]">Farringdon</option>
					<option value="Faversham [FAV]">Faversham</option>
					<option value="Folkestone Central [FKC]">Folkestone Central</option>
					<option value="Folkestone West [FKW]">Folkestone West</option>
					<option value="Frant [FRT]">Frant</option>
					<option value="Gillingham (Kent) [GLM]">Gillingham (Kent)</option>
					<option value="Gravesend [GRV]">Gravesend</option>
					<option value="Greenhithe [GNH]">Greenhithe</option>
					<option value="Greenwich [GNW]">Greenwich</option>
					<option value="Grove Park [GRP]">Grove Park</option>
					<option value="Halling [HAI]">Halling</option>
					<option value="Harrietsham [HRM]">Harrietsham</option>
					<option value="Hastings [HGS]">Hastings</option>
					<option value="Hayes [HYS]">Hayes</option>
					<option value="Headcorn [HCN]">Headcorn</option>
					<option value="Herne Bay [HNB]">Herne Bay</option>
					<option value="Herne Hill [HNH]">Herne Hill</option>
					<option value="High Brooms [HIB]">High Brooms</option>
					<option value="Higham [HGM]">Higham</option>
					<option value="Hildenborough [HLB]">Hildenborough</option>
					<option value="Hither Green [HGR]">Hither Green</option>
					<option value="Hollingbourne [HBN]">Hollingbourne</option>
					<option value="Kearsney [KSN]">Kearsney</option>
					<option value="Kemsing [KMS]">Kemsing</option>
					<option value="Kemsley [KML]">Kemsley</option>
					<option value="Kent House [KTH]">Kent House</option>
					<option value="Kidbrooke [KDB]">Kidbrooke</option>
					<option value="Knockholt [KCK]">Knockholt</option>
					<option value="Ladywell [LAD]">Ladywell</option>
					<option value="Lee [LEE]">Lee</option>
					<option value="Lenham [LEN]">Lenham</option>
					<option value="Lewisham [LEW]">Lewisham</option>
					<option value="London Blackfriars [BFR]">London Blackfriars</option>
					<option value="London Bridge [LBG]">London Bridge</option>
					<option value="London Cannon Street [CST]">London Cannon Street</option>
					<option value="London Charing Cross [CHX]">London Charing Cross</option>
					<option value="London St Pancras International [STP]">London St Pancras International</option>
					<option value="London Victoria [VIC]">London Victoria</option>
					<option value="London Waterloo East [WAE]">London Waterloo East</option>
					<option value="Longfield [LGF]">Longfield</option>
					<option value="Loughborough Junction [LGJ]">Loughborough Junction</option>
					<option value="Lower Sydenham [LSY]">Lower Sydenham</option>
					<option value="Maidstone Barracks [MDB]">Maidstone Barracks</option>
					<option value="Maidstone East [MDE]">Maidstone East</option>
					<option value="Maidstone West [MDW]">Maidstone West</option>
					<option value="Marden [MRN]">Marden</option>
					<option value="Margate [MAR]">Margate</option>
					<option value="Martin Mill [MTM]">Martin Mill</option>
					<option value="Maze Hill [MZH]">Maze Hill</option>
					<option value="Meopham [MEP]">Meopham</option>
					<option value="Minster [MSR]">Minster</option>
					<option value="Mottingham [MTG]">Mottingham</option>
					<option value="New Beckenham [NBC]">New Beckenham</option>
					<option value="New Cross [NWX]">New Cross</option>
					<option value="New Eltham [NEH]">New Eltham</option>
					<option value="New Hythe [NHE]">New Hythe</option>
					<option value="Newington [NGT]">Newington</option>
					<option value="Northfleet [NFL]">Northfleet</option>
					<option value="Nunhead [NHD]">Nunhead</option>
					<option value="Orpington [ORP]">Orpington</option>
					<option value="Otford [OTF]">Otford</option>
					<option value="Paddock Wood [PDW]">Paddock Wood</option>
					<option value="Peckham Rye [PMR]">Peckham Rye</option>
					<option value="Penge East [PNE]">Penge East</option>
					<option value="Petts Wood [PET]">Petts Wood</option>
					<option value="Pluckley [PLC]">Pluckley</option>
					<option value="Plumstead [PLU]">Plumstead</option>
					<option value="Queenborough [QBR]">Queenborough</option>
					<option value="Rainham [RAI]">Rainham</option>
					<option value="Ramsgate [RAM]">Ramsgate</option>
					<option value="Ravensbourne [RVB]">Ravensbourne</option>
					<option value="Robertsbridge [RBR]">Robertsbridge</option>
					<option value="Rochester [RTR]">Rochester</option>
					<option value="Rye [RYE]">Rye</option>
					<option value="Sandling [SDG]">Sandling</option>
					<option value="Sandwich [SDW]">Sandwich</option>
					<option value="Selling [SEG]">Selling</option>
					<option value="Sevenoaks [SEV]">Sevenoaks</option>
					<option value="Sheerness on Sea [SSS]">Sheerness on Sea</option>
					<option value="Shepherds Well [SPH]">Shepherds Well</option>
					<option value="Shoreham [SEH]">Shoreham</option>
					<option value="Shortlands [SRT]">Shortlands</option>
					<option value="Sidcup [SID]">Sidcup</option>
					<option value="Sittingbourne [SIT]">Sittingbourne</option>
					<option value="Slade Green [SGR]">Slade Green</option>
					<option value="Snodland [SDA]">Snodland</option>
					<option value="Snowdown [SWO]">Snowdown</option>
					<option value="Sole Street [SOR]">Sole Street</option>
					<option value="St Johns [SAJ]">St Johns</option>
					<option value="St Leonards Warrior Square [SLQ]">St Leonards Warrior Square</option>
					<option value="St Mary Cray [SMY]">St Mary Cray</option>
					<option value="Staplehurst [SPU]">Staplehurst</option>
					<option value="Stone Crossing [SCG]">Stone Crossing</option>
					<option value="Stonegate [SOG]">Stonegate</option>
					<option value="Stratford International [SFA]">Stratford International</option>
					<option value="Strood [SOO]">Strood</option>
					<option value="Sturry [STU]">Sturry</option>
					<option value="Sundridge Park [SUP]">Sundridge Park</option>
					<option value="Swale [SWL]">Swale</option>
					<option value="Swanley [SAY]">Swanley</option>
					<option value="Swanscombe [SWM]">Swanscombe</option>
					<option value="Sydenham Hill [SYH]">Sydenham Hill</option>
					<option value="Teynham [TEY]">Teynham</option>
					<option value="Tonbridge [TON]">Tonbridge</option>
					<option value="Tunbridge Wells [TBW]">Tunbridge Wells</option>
					<option value="Wadhurst [WAD]">Wadhurst</option>
					<option value="Walmer [WAM]">Walmer</option>
					<option value="Wateringbury [WTR]">Wateringbury</option>
					<option value="Welling [WLI]">Welling</option>
					<option value="West Dulwich [WDU]">West Dulwich</option>
					<option value="West Malling [WMA]">West Malling</option>
					<option value="West St Leonards [WLD]">West St Leonards</option>
					<option value="West Wickham [WWI]">West Wickham</option>
					<option value="Westcombe Park [WCB]">Westcombe Park</option>
					<option value="Westenhanger [WHA]">Westenhanger</option>
					<option value="Westgate on Sea [WGA]">Westgate on Sea</option>
					<option value="Whitstable [WHI]">Whitstable</option>
					<option value="Woolwich Arsenal [WWA]">Woolwich Arsenal</option>
					<option value="Woolwich Dockyard [WWD]">Woolwich Dockyard</option>
					<option value="Wye [WYE]">Wye</option>
					<option value="Yalding [YAL]">Yalding</option>
					<option value="Ore [ORE]">Ore</option> 
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
    				<option value=""></option>
					<option  value="Abbey Wood [ABW]">Abbey Wood</option>
					<option value="Adisham [ADM]">Adisham</option>
					<option value="Albany Park [AYP]">Albany Park</option>
					<option value="Ashford International [AFK]">Ashford International</option>
					<option value="Aylesford [AYL]">Aylesford</option>
					<option value="Aylesham [AYH]">Aylesham</option>
					<option value="Barming [BMG]">Barming</option>
					<option value="Barnehurst [BNH]">Barnehurst</option>
					<option value="Bat & Ball [BBL]">Bat & Ball</option>
					<option value="Battle [BAT]">Battle</option>
					<option value="Bearsted [BSD]">Bearsted</option>
					<option value="Beckenham Hill [BEC]">Beckenham Hill</option>
					<option value="Beckenham Junction [BKJ]">Beckenham Junction</option>
					<option value="Bekesbourne [BKS]">Bekesbourne</option>
					<option value="Bellingham [BGM]">Bellingham</option>
					<option value="Beltring [BEG]">Beltring</option>
					<option value="Belvedere [BVD]">Belvedere</option>
					<option value="Bexley [BXY]">Bexley</option>
					<option value="Bexleyheath [BXH]">Bexleyheath</option>
					<option value="Bickley [BKL]">Bickley</option>
					<option value="Birchington-on-Sea [BCH]">Birchington-on-Sea</option>
					<option value="Blackheath [BKH]">Blackheath</option>
					<option value="Borough Green & Wrotham [BRG]">Borough Green & Wrotham</option>
					<option value="Brixton [BRX]">Brixton</option>
					<option value="Broadstairs [BSR]">Broadstairs</option>
					<option value="Bromley North [BMN]">Bromley North</option>
					<option value="Bromley South [BMS]">Bromley South</option>
					<option value="Canterbury East [CBE]">Canterbury East</option>
					<option value="Canterbury West [CBW]">Canterbury West</option>
					<option value="Catford [CTF]">Catford</option>
					<option value="Catford Bridge [CFB]">Catford Bridge</option>
					<option value="Charing [CHG]">Charing</option>
					<option value="Charlton [CTN]">Charlton</option>
					<option value="Chartham [CRT]">Chartham</option>
					<option value="Chatham [CTM]">Chatham</option>
					<option value="Chelsfield [CLD]">Chelsfield</option>
					<option value="Chestfield & Swalecliffe [CSW]">Chestfield & Swalecliffe</option>
					<option value="Chilham [CIL]">Chilham</option>
					<option value="Chislehurst [CIT]">Chislehurst</option>
					<option value="City Thameslink [CTK]">City Thameslink</option>
					<option value="Clock House [CLK]">Clock House</option>
					<option value="Crayford [CRY]">Crayford</option>
					<option value="Crofton Park [CFT]">Crofton Park</option>
					<option value="Crowhurst [CWU]">Crowhurst</option>
					<option value="Cuxton [CUX]">Cuxton</option>
					<option value="Dartford [DFD]">Dartford</option>
					<option value="Deal [DEA]">Deal</option>
					<option value="Denmark Hill [DMK]">Denmark Hill</option>
					<option value="Deptford [DEP]">Deptford</option>
					<option value="Dover Priory [DVP]">Dover Priory</option>
					<option value="Dumpton Park [DMP]">Dumpton Park</option>
					<option value="Dunton Green [DNG]">Dunton Green</option>
					<option value="East Farleigh [EFL]">East Farleigh</option>
					<option value="East Malling [EML]">East Malling</option>
					<option value="Ebbsfleet International [EBD]">Ebbsfleet International</option>
					<option value="Eden Park [EDN]">Eden Park</option>
					<option value="Elephant & Castle [EPH]">Elephant & Castle</option>
					<option value="Elmers End [ELE]">Elmers End</option>
					<option value="Elmstead Woods [ESD]">Elmstead Woods</option>
					<option value="Eltham [ELW]">Eltham</option>
					<option value="Erith [ERH]">Erith</option>
					<option value="Etchingham [ETC]">Etchingham</option>
					<option value="Eynsford [EYN]">Eynsford</option>
					<option value="Falconwood [FCN]">Falconwood</option>
					<option value="Farningham Road [FNR]">Farningham Road</option>
					<option value="Farringdon [ZFD]">Farringdon</option>
					<option value="Faversham [FAV]">Faversham</option>
					<option value="Folkestone Central [FKC]">Folkestone Central</option>
					<option value="Folkestone West [FKW]">Folkestone West</option>
					<option value="Frant [FRT]">Frant</option>
					<option value="Gillingham (Kent) [GLM]">Gillingham (Kent)</option>
					<option value="Gravesend [GRV]">Gravesend</option>
					<option value="Greenhithe [GNH]">Greenhithe</option>
					<option value="Greenwich [GNW]">Greenwich</option>
					<option value="Grove Park [GRP]">Grove Park</option>
					<option value="Halling [HAI]">Halling</option>
					<option value="Harrietsham [HRM]">Harrietsham</option>
					<option value="Hastings [HGS]">Hastings</option>
					<option value="Hayes [HYS]">Hayes</option>
					<option value="Headcorn [HCN]">Headcorn</option>
					<option value="Herne Bay [HNB]">Herne Bay</option>
					<option value="Herne Hill [HNH]">Herne Hill</option>
					<option value="High Brooms [HIB]">High Brooms</option>
					<option value="Higham [HGM]">Higham</option>
					<option value="Hildenborough [HLB]">Hildenborough</option>
					<option value="Hither Green [HGR]">Hither Green</option>
					<option value="Hollingbourne [HBN]">Hollingbourne</option>
					<option value="Kearsney [KSN]">Kearsney</option>
					<option value="Kemsing [KMS]">Kemsing</option>
					<option value="Kemsley [KML]">Kemsley</option>
					<option value="Kent House [KTH]">Kent House</option>
					<option value="Kidbrooke [KDB]">Kidbrooke</option>
					<option value="Knockholt [KCK]">Knockholt</option>
					<option value="Ladywell [LAD]">Ladywell</option>
					<option value="Lee [LEE]">Lee</option>
					<option value="Lenham [LEN]">Lenham</option>
					<option value="Lewisham [LEW]">Lewisham</option>
					<option value="London Blackfriars [BFR]">London Blackfriars</option>
					<option value="London Bridge [LBG]">London Bridge</option>
					<option value="London Cannon Street [CST]">London Cannon Street</option>
					<option value="London Charing Cross [CHX]">London Charing Cross</option>
					<option value="London St Pancras International [STP]">London St Pancras International</option>
					<option value="London Victoria [VIC]">London Victoria</option>
					<option value="London Waterloo East [WAE]">London Waterloo East</option>
					<option value="Longfield [LGF]">Longfield</option>
					<option value="Loughborough Junction [LGJ]">Loughborough Junction</option>
					<option value="Lower Sydenham [LSY]">Lower Sydenham</option>
					<option value="Maidstone Barracks [MDB]">Maidstone Barracks</option>
					<option value="Maidstone East [MDE]">Maidstone East</option>
					<option value="Maidstone West [MDW]">Maidstone West</option>
					<option value="Marden [MRN]">Marden</option>
					<option value="Margate [MAR]">Margate</option>
					<option value="Martin Mill [MTM]">Martin Mill</option>
					<option value="Maze Hill [MZH]">Maze Hill</option>
					<option value="Meopham [MEP]">Meopham</option>
					<option value="Minster [MSR]">Minster</option>
					<option value="Mottingham [MTG]">Mottingham</option>
					<option value="New Beckenham [NBC]">New Beckenham</option>
					<option value="New Cross [NWX]">New Cross</option>
					<option value="New Eltham [NEH]">New Eltham</option>
					<option value="New Hythe [NHE]">New Hythe</option>
					<option value="Newington [NGT]">Newington</option>
					<option value="Northfleet [NFL]">Northfleet</option>
					<option value="Nunhead [NHD]">Nunhead</option>
					<option value="Orpington [ORP]">Orpington</option>
					<option value="Otford [OTF]">Otford</option>
					<option value="Paddock Wood [PDW]">Paddock Wood</option>
					<option value="Peckham Rye [PMR]">Peckham Rye</option>
					<option value="Penge East [PNE]">Penge East</option>
					<option value="Petts Wood [PET]">Petts Wood</option>
					<option value="Pluckley [PLC]">Pluckley</option>
					<option value="Plumstead [PLU]">Plumstead</option>
					<option value="Queenborough [QBR]">Queenborough</option>
					<option value="Rainham [RAI]">Rainham</option>
					<option value="Ramsgate [RAM]">Ramsgate</option>
					<option value="Ravensbourne [RVB]">Ravensbourne</option>
					<option value="Robertsbridge [RBR]">Robertsbridge</option>
					<option value="Rochester [RTR]">Rochester</option>
					<option value="Rye [RYE]">Rye</option>
					<option value="Sandling [SDG]">Sandling</option>
					<option value="Sandwich [SDW]">Sandwich</option>
					<option value="Selling [SEG]">Selling</option>
					<option value="Sevenoaks [SEV]">Sevenoaks</option>
					<option value="Sheerness on Sea [SSS]">Sheerness on Sea</option>
					<option value="Shepherds Well [SPH]">Shepherds Well</option>
					<option value="Shoreham [SEH]">Shoreham</option>
					<option value="Shortlands [SRT]">Shortlands</option>
					<option value="Sidcup [SID]">Sidcup</option>
					<option value="Sittingbourne [SIT]">Sittingbourne</option>
					<option value="Slade Green [SGR]">Slade Green</option>
					<option value="Snodland [SDA]">Snodland</option>
					<option value="Snowdown [SWO]">Snowdown</option>
					<option value="Sole Street [SOR]">Sole Street</option>
					<option value="St Johns [SAJ]">St Johns</option>
					<option value="St Leonards Warrior Square [SLQ]">St Leonards Warrior Square</option>
					<option value="St Mary Cray [SMY]">St Mary Cray</option>
					<option value="Staplehurst [SPU]">Staplehurst</option>
					<option value="Stone Crossing [SCG]">Stone Crossing</option>
					<option value="Stonegate [SOG]">Stonegate</option>
					<option value="Stratford International [SFA]">Stratford International</option>
					<option value="Strood [SOO]">Strood</option>
					<option value="Sturry [STU]">Sturry</option>
					<option value="Sundridge Park [SUP]">Sundridge Park</option>
					<option value="Swale [SWL]">Swale</option>
					<option value="Swanley [SAY]">Swanley</option>
					<option value="Swanscombe [SWM]">Swanscombe</option>
					<option value="Sydenham Hill [SYH]">Sydenham Hill</option>
					<option value="Teynham [TEY]">Teynham</option>
					<option value="Tonbridge [TON]">Tonbridge</option>
					<option value="Tunbridge Wells [TBW]">Tunbridge Wells</option>
					<option value="Wadhurst [WAD]">Wadhurst</option>
					<option value="Walmer [WAM]">Walmer</option>
					<option value="Wateringbury [WTR]">Wateringbury</option>
					<option value="Welling [WLI]">Welling</option>
					<option value="West Dulwich [WDU]">West Dulwich</option>
					<option value="West Malling [WMA]">West Malling</option>
					<option value="West St Leonards [WLD]">West St Leonards</option>
					<option value="West Wickham [WWI]">West Wickham</option>
					<option value="Westcombe Park [WCB]">Westcombe Park</option>
					<option value="Westenhanger [WHA]">Westenhanger</option>
					<option value="Westgate on Sea [WGA]">Westgate on Sea</option>
					<option value="Whitstable [WHI]">Whitstable</option>
					<option value="Woolwich Arsenal [WWA]">Woolwich Arsenal</option>
					<option value="Woolwich Dockyard [WWD]">Woolwich Dockyard</option>
					<option value="Wye [WYE]">Wye</option>
					<option value="Yalding [YAL]">Yalding</option>
					<option value="Ore [ORE]">Ore</option> 
  				</select>
    		</div>
    	</div>   	
  	
  		<div class="row">
			<div class="col-md-3">
       			<label>Date of delay:</label> <a onclick="filltoday()">(Today)</a>  	    
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
    			<label>Ticket type:</label>
    		</div>
        	<div class="col-md-9">	
				<select name="ticket_type" id="ticket_type" class="stored">
                    <option value=""></option>
					<option value="Daily">Daily</option>
					<option value="Weekly">Weekly</option>
					<option value="Monthly">Monthly</option>
					<option value="Annual">Annual</option>
					<option value="Other">Other</option>
				</select>

			</div>
		</div>
    	<div class="row">
       		<div class="col-md-3">
    			<label>Photocard number:</label>
    		</div>
        	<div class="col-md-9">			

				<input type="text" name="photocard_number" id="photocard_number" class="stored" value=""/>
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
     		Email me a copy of my feedback<input type="checkbox" name="user_copy" value="user_copy" checked>
     	</div>
    	<div class="row">	
    		<input type="submit" class="demo-button" formaction="https://www.southeasternrailway.co.uk/mobile/contact-us/feedback-form" value="Go to Customer Comments form" />

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
        if (localStorage.title) {
        	var element=document.getElementById('title');
        	element.value=localStorage.title ;              
        }
        if (localStorage.surname) {
            $('#surname').val(localStorage.surname);
        }        
        if (localStorage.email) {
            $('#email').val(localStorage.email);
        }
        if (localStorage.feedback_subject) {
        	var element=document.getElementById('feedback_subject');
        	element.value=localStorage.feedback_subject ;              
        }        
        if (localStorage.feedback_type) {
        	var element=document.getElementById('feedback_type');
        	element.value=localStorage.feedback_type ;              
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

        if (localStorage.feedback_subject) {
        	var element=document.getElementById('feedback_subject');
        	element.value=localStorage.feedback_subject ;         
        }    
        if (localStorage.feedback_type) {
        	var element=document.getElementById('feedback_type');
        	element.value=localStorage.feedback_type ;         
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
