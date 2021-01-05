# World Happiness

<!DOCTYPE html>
<html>
<head>
    <title>Basic Embed</title>
    <script type="text/javascript"
	    src="https://public.tableau.com/javascripts/api/tableau-2.min.js"></script>
    <script type="text/javascript">
        function initViz() {
            var containerDiv = document.getElementById("vizContainer"),
                url = "https://public.tableau.com/views/WorldHappiness_16098070994300/WorldHappinessReportStory?:language=en&:display_count=y&publish=yes&:origin=viz_share_link",
                options = {
                    hideTabs: true,
                    onFirstInteractive: function () {
                        console.log("Run this code when the viz has finished loading.");
                    }
                };

            var viz = new tableau.Viz(containerDiv, url, options);
            // Create a viz object and embed it in the container div.
        }
    </script>
</head>
<body onload="initViz();">
    <div id="vizContainer" style="width:800px; height:700px;"></div>
</body>
</html>

You can view this Tableau story here: [World Happiness](https://public.tableau.com/views/WorldHappiness_16098070994300/WorldHappinessReportStory?:language=en&:display_count=y&publish=yes&:origin=viz_share_link)
