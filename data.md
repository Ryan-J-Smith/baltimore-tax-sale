---
layout: page
title: Download Data
---

---
## Auction Results

These files were obtained by exporting custom reports on the [Baltimore Tax Certificate Auction Web Site](http://www.bidbaltimore.com).  For each year listed, there is an auction results file and an auction summary file.  

The **Results** files contain individual data entries for each property included in the auction.  Each entry also contains a number of attributes associated with the property such as the address, square footage, assessed value, lien amount, the winning bid amount, and a numerical identifier of the winning bidder.

The **Summary** files contain results aggregated by bidder at the end of the auction.  Specifically the number of bids each bidder listed, the number of certificates won, and the total value of liens purchased.

<table>
	<thead>
		<tr>
			<th>Year</th>
			<th>Auction Results</th>
			<th>Auction Summary</th>
		</tr>
	</thead>
	<tbody align="center">
		<tr>
			<td>2014</td>
			<td><a href="{{ site.baseurl }}assets/data/2014AuctionResults.csv">2014 Auction Results</a></td>
			<td><a href="{{ site.baseurl }}assets/data/2014AuctionSummary.csv">2014 Auction Summary</a></td>
		</tr>
		<tr>
			<td>2013</td>
			<td><a href="{{ site.baseurl }}assets/data/2013AuctionResults.csv">2013 Auction Results</a></td>
			<td><a href="{{ site.baseurl }}assets/data/2013AuctionSummary.csv">2013 Auction Summary</a></td>
		</tr>
		<tr>
			<td>2012</td>
			<td><a href="{{ site.baseurl }}assets/data/2013AuctionResults.csv">2012 Auction Results</a></td>
			<td><a href="{{ site.baseurl }}assets/data/2013AuctionSummary.csv">2012 Auction Summary</a></td>
		</tr>		
	</tbody>
</table>

---

## Assignment Sale Results

Following completion of the auction each year, there is a so-called *assignment sale*.  During this sale, certificates that were not bid on during the auction phase can be purchased at the face-value of the lien.  Investors still enter bids, however the bid amount is fixed at the lien value.  If there are multiple bids entered for a certificate during this phase, a winner is chosen randomly from among those bidding.

As with the auction data above, the **Results** files contain individual properties and associated attributes.  The **Summary** files contain the results aggregated by bidder.

Properties with certificates purchased earlier during the associated year's auction phase will not appear in the assignment results.

<table>
	<thead>
		<tr>
			<th>Year</th>
			<th>Assignment Results</th>
			<th>Assignment Summary</th>
		</tr>
	</thead>
	<tbody align="center">
		<tr>
			<td>2014</td>
			<td><a href="{{ site.baseurl }}/assets/data/2014AssignmentResults.csv">2014 Assignment Results</a></td>
			<td><a href="{{ site.baseurl }}/assets/data/2014AssignmentSummary.csv">2014 Assignment Summary</a></td>
		</tr>
		<tr>
			<td>2013</td>
			<td><a href="{{ site.baseurl }}/assets/data/2013AssignmentResults.csv">2013 Assignment Results</a></td>
			<td><a href="{{ site.baseurl }}/assets/data/2013AssignmentSummary.csv">2013 Assignment Summary</a></td>
		</tr>
		<tr>
		<tr>
			<td>2012</td>
			<td><a href="{{ site.baseurl }}/assets/data/2014AssignmentResults.csv">2012 Assignment Results</a></td>
			<td><a href="{{ site.baseurl }}/assets/data/2014AssignmentSummary.csv">2012 Assignment Summary</a></td>
		</tr>	
	</tbody>
</table>

---

## Other Data Sources

[Baltimore City Open GIS Data](http://gisdata.baltimorecity.gov/) - This site contains datasets related to the geography of Baltimore City such as neighborhood boundaries and parcel footprints.  The **Real Property** dataset hosted at this site includes vital information about the properties that isn't in the original auction data, such as the geographical coordinates of the property, the neighborhood the property belongs to, and the most recent sale value.