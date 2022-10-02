# Zaklika20249.github.io
<!DOCTYPE html>
<html lang="en">


<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- Title for the page -->
    <title>Document</title>

    <!-- Link to my style sheet -->
    <link rel="stylesheet" href="index2.css">

    <!--The next three lines allow the Vega embed-->
    <script src="https://cdn.jsdelivr.net/npm/vega@5.17.0"></script>
    <script src="https://cdn.jsdelivr.net/npm/vega-lite@4.17.0"></script>
    <script src="https://cdn.jsdelivr.net/npm/vega-embed@6.12.2"></script>
</head>



<body>
    <!-- A div that contains a group of items for week 1. Can be useful for setting background colours etc.  -->
    <div class="myWeek1">
        <h1>Data Science for Economists.</h1>
        
        <h3>Covid-19</h3>
        <p>The first chart tracks Covid-19 cases by UK region.</p>
        <div class="chart" id="Chart1"></div>

        <h3>Productivity puzzle</h3>
        <p>My second chart looks at productivity in the UK</p>
        <div class="chart" id="Chart2"> </div>
    </div> 
</body>


<script>
    //Define charts:
    var myChart1 = "chart1_covidUKRegions.json";
    var myChart2 = "chart2_ukProductivity.json";

    // Embed charts:
    vegaEmbed('#Chart1', myChart1);
    vegaEmbed('#Chart2', myChart2);
</script>

</html>
