<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>PHP Ajax Load More Pagination</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <div id="main">
    <div id="header">
      <h1>PHP & Ajax COVID-19 Rest API</h1>
    </div>

    <div id="table-data">
        <!-- World Covid-19 Summary -->
      <h3>World Covid-19 Summary</h3>
      <table class="bdTable" id="loadData" border="1" width="" cellspacing="0" cellpadding="10px">
        <tbody class="world-wise">

        </tbody>
      </table>
        <!-- Bangladesh Covid-19 Summary -->
      <h3>Bangladesh Covid-19 Summary</h3>
      <table class="bdTable" id="loadData" border="1" width="" cellspacing="0" cellpadding="10px">
        <tbody class="bd-wise">

        </tbody>
      </table>
        <!-- Country Wise Covid-19 Summary -->
        <h3>Country Wise Covid-19 Summary</h3>
      <table id="loadData" border="1" width="" cellspacing="0" cellpadding="10px">
        <thead>
            <tr>
                <th>S. No.</th>
                <th>Country</th>
                <th>New Confirmed</th>
                <th>New Deaths</th>
                <th>New Recovered</th>
                <th>Total Confirmed</th>
                <th>Total Deaths</th>
                <th>Total Recovered</th>
                <th>Date</th>

            </tr>
        </thead>
        <tbody class="country-wise">

        </tbody>
      </table>
      
    </div>

  </div>

<script type="text/javascript" src="js/jquery.js"></script>
<script>

  $(document).ready(function(){
    function loadTable() {
      $.ajax({
        url : "https://api.covid19api.com/summary",
        type : "GET",
        dataType : "JSON", 
        success : function(data){
            // console.log(data);
            // Country Wise Covid-19 Summary
            var sr = 1;
            $.each(data.Countries, function(key, value) {
                // console.log(key + " : " + value);
                $(".country-wise").append(
                    "<tr>" + 
                        "<td>" + sr + "</td>" +
                        "<td>" + value.Country + "</td>" +
                        "<td>" + value.NewConfirmed + "</td>" +
                        "<td>" + value.NewDeaths + "</td>" +
                        "<td>" + value.NewRecovered + "</td>" +
                        "<td>" + value.TotalConfirmed + "</td>" +
                        "<td>" + value.TotalDeaths + "</td>" +
                        "<td>" + value.TotalRecovered + "</td>" +
                        "<td>" + value.Date + "</td>"
                    
                    + "</tr>" 
                );
                sr++;
            })
            // Bangladesh Covid-19 Summary
            $.each(data.Countries[13], function(key, value) {
                // console.log(key + " : " + value);
                $(".bd-wise").append(
                    "<tr>" +
                        "<td>" + key + "</td>" +
                        "<td>" + value + "</td>"
                    + "</tr>"
                );
            });
            // World Covid-19 Summary
            $.each(data.Global, function(key, value) {
                // console.log(key + " : " + value);
                $(".world-wise").append(
                    "<tr>" +
                        "<td>" + key + "</td>" +
                        "<td>" + value + "</td>"
                    + "</tr>"
                );
            });
        }
      })
    }
    loadTable();
  
  })

</script>

</body>
</html>