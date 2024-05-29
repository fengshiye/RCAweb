---
title: "Resp Cell Atlas - Database"
layout: textlay
excerpt: " The Databases in Resp Cell Atlas, GZNL-RDC. "
sitemap: true
permalink: /database/
---
<html lang="en">
<head>
<!--set sort order in table header begin-->
<meta http-equiv="Content-type" content="text/html; charset=utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=no">
  <!-- <title>Ribozyme applications</title> -->
  <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.12.1/css/jquery.dataTables.min.css">
  <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/buttons/2.2.3/css/buttons.dataTables.min.css">

  <script type="text/javascript" src="https://code.jquery.com/jquery-3.5.1.js"></script>
  <script type="text/javascript" src="https://cdn.datatables.net/1.12.1/js/jquery.dataTables.min.js"></script>
  <!--set sort order in table header finish-->
  <!-- <style>
    .header_box {
    border: none;
    background: #efefef;
    font-size:24px
  }
  h2{
    font-size:20px;
    font-weight: bold;
  }
/* Button Container Styles */
    .button-container {
      display: flex;
      justify-content: left;
      align-items: center;
      height: 50px;
      overflow:auto
    }
    /* Button Style */
    .button {
      display: block;
      padding: 10px;
      margin-right: 10px;
      text-align: center;
      background-color: #efefef;
      color: #005826;
      text-decoration: none;
      font-size: 16px;
      border: 1px solid #005826;
      border-radius: 5px;
    }
    /* Mouse Hover Style */
    .button:hover {
      background-color: #999;
      cursor: pointer;
    }
    /* 样式表格 */
    table {
        border: 2px solid #f8f8ff;
        border: 2px solid #767676;
		    border: 2px solid #767676;
		    border-radius: 5px;
		    background-color: #fff;
		    border-radius: 0;
        }
		  th {
        background-color: #719B71;
        background-color: #719B71;
        background-color: #005826;
        color: rgba(255,255,255,0.9);
		    cursor: pointer;
        }
		  td {
		    background-color: #ffffff;
		    background-color: #f9f9f9;
		    background-color: #f9f9f9;
		    }		
		  th, td {
		  padding: 10px 10px;
		}
    /* 隐藏所有 sheet */
    .sheet {
      display: none;
      overflow:auto
    }
    /* Style the search box */
  #searchBox {
    padding: 10px;
    font-size: 16px;
    border: 2px solid #ccc;
    border-radius: 4px;
    width: 300px;
  }
  /* Style the search box when it has focus */
  #searchBox:focus {
    outline: none;
    border-color: #2354C4;
  }
  /* Style the placeholder text */
  #searchBox::placeholder {
    font-size: 16px;
  }
  /* 搜索框和下载框水平布局 */
    .form-container {
      display: flex;
      align-items: center;
      overflow:auto
    }
    .form-container input {
      margin-right: 10px;
    }
    /* 下载框位置设置 */
    .form-container select {
      margin-left: auto;
      padding: 10px;
      font-size: 16px;
      border: 2px solid #ccc;
      border-radius: 4px;
      width: 300px;
    }
    .button.clicked {
    background-color: #999;
}

<!--   </style> -->
</head> 

<!-- <body onload="showSheet('sheet1')"> -->
<!-- 
<p class="header_box" >Detail information</p>

        
This section lists all the experimentally validated riboswitches. -->
<div style="text-align: right;">
<input type="text" id="searchBox" placeholder="Search by keyword..." onfocus="showAllSheets()" oninput="searchTables()"><br><br>
</div>
<div>
<table id="cfttable" class="table table-hover table-bordered">
    <colgroup>
          <col style="width: 10%;">
          <col style="width: 5%;">
          <col style="width: 40%;">
          <col style="width: 10%;">
          <col style="width: 5%;">
          <col style="width: 10%;">
          <col style="width: 10%;">
          <col style="width: 5%;">
        </colgroup>
        <thead>
        <tr>
            <th onclick="sortTable(0)">Name</th>
            <th onclick="sortTable(1)">Year</th>
            <th onclick="sortTable(2)">Title</th>
            <th onclick="sortTable(3)">Accession</th>
            <th onclick="sortTable(4)">Species</th>
            <th onclick="sortTable(5)">Organ</th>
            <th onclick="sortTable(6)">Seq-method</th>
            <th onclick="sortTable(7)">Link</th>
            <!-- <th onclick="sortTable(5)">Rfam-ID</th> -->
        </tr>
        </thead>
        <tbody>
        <tr>
            <!-- <td name="td0"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>AdoCbl</b></a></td> -->
            <td name="td0">Yoshida <i>et al.</i></td>
            <td name="td1">2021</td>
            <td name="td2">Local and systemic responses to SARS-CoV-2 infection in children and adults</td>
            <td name="td3">-</td>
            <td name="td4">Human</td>
            <td name="td5">Nose, Trachea, Bronchi</td>
            <td name="td6">scRNA-seq</td>
            <td name="td7"><a href="https://covid19cellatlas.org" target="_blank"><b>Link</b></a></td>
            <!-- <td name="td5">RF01482 RF00174</td> -->
        </tr>

        <tr>
            <td name="td0">Madissoon <i>et al.</i></td>
            <td name="td1">2023</td>
            <td name="td2">A spatially resolved atlas of the human lung characterizes a gland-associated immune niche</td>
            <td name="td3">S-SUBS17</td>
            <td name="td4">Human</td>
            <td name="td5">Lung, Bronchi</td>
            <td name="td6">scRNA-seq</td>
            <td name="td7"><a href="https://www.ebi.ac.uk/biostudies/dsp/studies/S-SUBS17" target="_blank"><b>Link</b></a></td>
            <!-- <td name="td5">None</td> -->
        </tr>

        <tr>
            <td name="td0">Liao <i>et al.</i></td>
            <td name="td1">2020</td>
            <td name="td2">Single-cell landscape of bronchoalveolar immune cells in patients with COVID-19</td>
            <td name="td3"> GSE145926</td>
            <td name="td4">Human</td>
            <td name="td5">Lung</td>
            <td name="td6">scRNA-seq</td>
            <td name="td7"><a href="https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE145926" target="_blank"><b>Link</b></a></td>
            <!-- <td name="td5">None</td> -->
        </tr> 

        <tr>
            <td name="td0">Miller <i>et al.</i></td>
            <td name="td1">2020</td>
            <td name="td2">In Vitro and In Vivo Development of the Human Airway at Single-Cell Resolution</td>
            <td name="td3"> E-MTAB-8221</td>
            <td name="td4">Human</td>
            <td name="td5">Airway, Trachea</td>
            <td name="td6">scRNA-seq</td>
            <td name="td7"><a href="https://www.ebi.ac.uk/biostudies/arrayexpress/studies/E-MTAB-8221" target="_blank"><b>Link</b></a></td>
            <!-- <td name="td5">None</td> -->
        </tr> 

        <tr>
            <td name="td0">He <i>et al.</i></td>
            <td name="td1">2022</td>
            <td name="td2">A human fetal lung cell atlas uncovers proximal-distal gradients of differentiation and key regulators of epithelial fates</td>
            <td name="td3"> E-MTAB-11278</td>
            <td name="td4">Human</td>
            <td name="td5">Lung</td>
            <td name="td6">scRNA-seq</td>
            <td name="td7"><a href="https://www.ebi.ac.uk/biostudies/arrayexpress/studies/E-MTAB-11278?query=E-MTAB-11278" target="_blank"><b>Link</b></a></td>
            <!-- <td name="td5">None</td> -->
        </tr> 

         <tr>
            <td name="td0">Ziegler <i>et al.</i></td>
            <td name="td1">2021</td>
            <td name="td2">Impaired local intrinsic immunity to SARS-CoV-2 infection in severe COVID-19</td>
            <td name="td3"> SCP1289</td>
            <td name="td4">Human</td>
            <td name="td5">Nasopharynx</td>
            <td name="td6">scRNA-seq</td>
            <td name="td7"><a href="https://singlecell.broadinstitute.org/single_cell/study/SCP1289/" target="_blank"><b>Link</b></a></td>
            <!-- <td name="td5">None</td> -->
        </tr> 


      </tbody>
    </table>
</div>                
<script>
  var tables = [];
    var currentSheet = 'sheet1';
     $(document).ready(function() {
    $.noConflict();
    tables.push($('#cfttable').DataTable({
      dom: 'Bfrtip',
      buttons: [
        'copy', 'csv', 'excel', 'pdf', 'print'
      ]
    }));

    tables.push($('#rnadetable').DataTable({
      dom: 'Bfrtip',
      buttons: [
        'copy', 'csv', 'excel', 'pdf', 'print'
      ]
    }));

    tables.push($('#rnapretable').DataTable({
      dom: 'Bfrtip',
      buttons: [
        'copy', 'csv', 'excel', 'pdf', 'print'
      ]
    }));
    tables.push($('#smtable').DataTable({
      dom: 'Bfrtip',
      buttons: [
        'copy', 'csv', 'excel', 'pdf', 'print'
      ]
    }));
    tables.push($('#eletable').DataTable({
      dom: 'Bfrtip',
      buttons: [
        'copy', 'csv', 'excel', 'pdf', 'print'
      ]
    }));


    
    tables.push($('#amintable').DataTable({
      dom: 'Bfrtip',
      buttons: [
        'copy', 'csv', 'excel', 'pdf', 'print'
      ]
    }));
    tables.push($('#sugtable').DataTable({
      dom: 'Bfrtip',
      buttons: [
        'copy', 'csv', 'excel', 'pdf', 'print'
      ]
    }));
    tables.push($('#tboxtable').DataTable({
      dom: 'Bfrtip',
      buttons: [
        'copy', 'csv', 'excel', 'pdf', 'print'
      ]
    }));
    tables.push($('#othtable').DataTable({
      dom: 'Bfrtip',
      buttons: [
        'copy', 'csv', 'excel', 'pdf', 'print'
      ]
    }));
    
    
    // Hide the search box for DataTables
      $('#cfttable_filter').css('display', 'none');
      $('#rnadetable_filter').css('display', 'none');
      $('#rnapretable_filter').css('display', 'none');
       $('#smtable_filter').css('display', 'none');
      $('#eletable_filter').css('display', 'none');
      $('#amintable_filter').css('display', 'none');
      $('#sugtable_filter').css('display', 'none');
      $('#tboxtable_filter').css('display', 'none');
      $('#othtable_filter').css('display', 'none');
      
      // Show the initial sheet (sheet1) and hide others
    showSheet('sheet1');
    hideAllSheetsExcept('sheet1');
  });

  function sortTable(columnIndex) {
    // TODO: Add sorting logic based on the columnIndex
  }

  

function downloadExcel() {
  var selectElement = document.getElementById('downloadOptions');
  var selectedValue = selectElement.value;

  // Check if a valid option was selected
  if (selectedValue !== '') {
    // Create a temporary link element with the download URL
    var link = document.createElement('a');
    link.href = selectedValue;
    link.download = selectedValue.split('/').pop(); // Set the filename to the last part of the URL
    document.body.appendChild(link);

    // Trigger a click event on the link to start the download
    link.click();

    // Remove the link from the DOM
    document.body.removeChild(link);
  }
}
	
	
	function showSheet(sheetId) {
    // Hide the current sheet
    if (currentSheet) {
        var currentSheetElement = document.getElementById(currentSheet);
        currentSheetElement.style.display = 'none';
    }

    // Show the selected sheet
    var sheet = document.getElementById(sheetId);
    sheet.style.display = 'block';

    // Update the current sheet
    currentSheet = sheetId;

    // Get all buttons
    var buttons = document.querySelectorAll('.button');

    // Remove clicked class from all buttons
    buttons.forEach(function(btn) {
        btn.classList.remove('clicked');
    });

    // Add clicked class to the clicked button using event.target
    event.target.classList.add('clicked');
}

  function hideAllSheetsExcept(sheetId) {
    var sheets = document.getElementsByClassName('sheet');
    for (var i = 0; i < sheets.length; i++) {
      var sheet = sheets[i];
      if (sheet.id !== sheetId) {
        sheet.style.display = 'none';
      }
    }
    }

    function showAllSheets() {
      var sheets = document.getElementsByClassName('sheet');
      for (var i = 0; i < sheets.length; i++) {
        sheets[i].style.display = 'block';
      }
    }

    function searchTables() {
      var keyword = $('#searchBox').val().toLowerCase();

      tables.forEach(function(table) {
        table.search(keyword).draw();
      });
      // Filter the sheets based on search results
    filterSheets();
  }

  function filterSheets() {
    var keyword = $('#searchBox').val().toLowerCase();
    var sheets = document.getElementsByClassName('sheet');

    for (var i = 0; i < sheets.length; i++) {
      var sheet = sheets[i];
      var table = tables[i];

      var displaySheet = false;

      table.rows().eq(0).each(function(index) {
        var row = table.row(index);
        var rowData = row.data().join(' ').toLowerCase();
        var display = rowData.includes(keyword) ? '' : 'none';
        row.nodes().to$().css('display', display);

        if (display !== 'none') {
          displaySheet = true;
        }
      });

      if (displaySheet) {
        $('#' + sheet.id).show();
      } else {
        $('#' + sheet.id).hide();
      }
    }
  }  
  </script>      