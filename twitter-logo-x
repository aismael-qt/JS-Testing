
// Find all anchor elements with an href containing "twitter"
const twitterLinks = document.querySelectorAll('a[href*="twitter"]');

// Loop through each matching anchor element
twitterLinks.forEach(link => {
	// Find the SVG element within the anchor element
	const svgElement = link.querySelector('svg');

	if (svgElement) {
		// Find the path elements within the SVG
		const pathElements = svgElement.querySelectorAll('path');

		// Set the fill attribute to black for each path element
		pathElements.forEach(path => {
			path.setAttribute('fill', 'black');
		});

		// Update the SVG attributes as needed
		svgElement.setAttribute('width', '16'); // Replace 'new-width' with the desired width
		svgElement.setAttribute('height', '16'); // Replace 'new-height' with the desired height

		// If you want to change the path data, you can access the path element within the SVG
		const pathElement = svgElement.querySelector('path');
		if (pathElement) {
			// Set the new path data
			pathElement.setAttribute('d', 'M14.095479,10.316482L22.286354,1h-1.940718l-7.115352,8.087682L7.551414,1H1l8.589488,12.231093L1,23h1.940717  l7.509372-8.542861L16.448587,23H23L14.095479,10.316482z M11.436522,13.338465l-0.871624-1.218704l-6.924311-9.68815h2.981339  l5.58978,7.82155l0.867949,1.218704l7.26506,10.166271h-2.981339L11.436522,13.338465z'); // Replace with your new path data
		}
	}
})
// Update Header Twitter Icon
// Select the second <li> element's <a> tag
let NewsecondLiA = document.querySelectorAll('ul.social-follow-icons li a div')[1];

// If the element exists
if (NewsecondLiA) {
	// Clear the existing content
	NewsecondLiA.style.marginLeft = '-8px';
	NewsecondLiA.style.marginRight = '0px';
	//secondLiA.innerHTML = '';

	// Append the new SVG to the <a> tag
	NewsecondLiA.innerHTML = '<svg style="width: 16px;height: 16px; margin-top: 4px" width="16" height="16" viewBox="0 0 1200 1227" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M714.163 519.284L1160.89 0H1055.03L667.137 450.887L357.328 0H0L468.492 681.821L0 1226.37H105.866L515.491 750.218L842.672 1226.37H1200L714.137 519.284H714.163ZM569.165 687.828L521.697 619.934L144.011 79.6944H306.615L611.412 515.685L658.88 583.579L1055.08 1150.3H892.476L569.165 687.854V687.828Z" fill="#c9cdcc"/></svg>';
}
