<html>
  <head>
    <style>
        body{
          margin:0;
          padding:0;
          font-family: helvetica;
        }

        h1 {
          padding: 60px 16px 60px;
          text-align: center;
          font-size: 50px;
          background: #f8f4f4;
          margin: 0px;
        }

        .header {
          margin: 0px 0px 0px;
          padding: 16px 0px 16px;
          background: #2596be;
          color: #f8f4f4;
          width: 100%;
          border-bottom: 2px solid black;
          border-top: 2px solid black;
        }

      .content {
        padding: 16px;
      }

      .sticky {
        position: fixed;
        top: 0;
        width: 100%
      }

      .sticky + .content {
        padding-top: 102px;
      }

      .table {
        border-collapse: collapse;
        text-align: center;
        height: 1500px;
        width: 90%;
        margin: auto;
      }

      .tableRow {
        border-top: 1px solid black;
        height: 200px;
      }

      .tableData {
        width: 20%;
      }

      .tableHeader {
        border-collapse: collapse;
        text-align: center;
        width: 90%;
        margin: auto;  
      }

      .tableHeaderData {
        width: 20%;
      }

      #tableRowOdd {
        background:#f8f4f4;
      }

      #nonBold {
        font-weight: 400;
      }

      #headerPrice {
        font-weight: 400;
        font-size: 16px;
        margin-top: 10px;
      }
    </style>
    <script>
      $( document ).ready(function() {
        window.onscroll = function() {myFunction()};

        var header = document.getElementById("myHeader");
        var sticky = header.offsetTop;

        function myFunction() {
          if (window.pageYOffset > sticky) {
            header.classList.add("sticky");
          } else {
            header.classList.remove("sticky");
          }
        }
      }
    </script>
  </head>
  <body>
    <div>
      <h1>Vergelijking M365 E3 en Alternatieven</h1>
    </div>
    <div class="header" id="myHeader">
      <h2>
        <table class="tableHeader">
          <tbody>
            <tr>
              <td class="tableHeaderData"></td>
              <td class="tableHeaderData">
                <div>M365 E3</div>
                <div id="headerPrice">€ 2.548.000,00 per jaar</div>
              </td>
              <td class="tableHeaderData">
                <div>M365 F3</div>
                <div id="headerPrice">€ 482.400,00 per jaar</div>
              </td>
              <td class="tableHeaderData">
                <div>Nedap</div>
                <div id="headerPrice">€ 943.488,00 per jaar</div>
              </td>
              <td class="tableHeaderData">
                <div>WPS Cloud</div>
                <div id="headerPrice">€ 359.940,00 per jaar</div>
              </td>
            </tr>
          </tbody>
        </table>
      </h2>
    </div>
    <div class="content">
      <table class="table">
        <tbody class="tableBody">
          <tr class="tableRow">
            <th scope="row">
              <div>
                Office Suite
              </div>
              <div id="nonBold">
                (Word Processor/Spreadsheet/Presentation/PDF Reader)
              </div>
            </th>
            <td class="tableData">
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td class="tableData">
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td class="tableData">
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td class="tableData">
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
          </tr>
          <tr class="tableRow" id="tableRowOdd">
            <th scope="row">
              <div>
                Geldeelde Cloudopslag
              </div>
            </th>
            <td>
              <img src="https://icons.iconarchive.com/icons/wefunction/woofunction/32/close-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
          </tr>
          <tr class="tableRow">
            <th scope="row">
              <div>
                Notitie Applicatie
              </div>
            </th>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
          </tr>
          <tr class="tableRow" id="tableRowOdd">
            <th scope="row">
              <div>
                Kalender Applicatie
              </div>
            </th>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              ???
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
          </tr>
          <tr class="tableRow">
            <th scope="row">
              <div>
                Webversie
              </div>
            </th>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
          </tr>
          <tr class="tableRow" id="tableRowOdd">
            <th scope="row">
              <div>
                Desktop Versie
              </div>
            </th>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/wefunction/woofunction/32/close-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
          </tr>
          <tr class="tableRow">
            <th scope="row">
              <div>
                Mobiele Versie
              </div>
            </th>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
          </tr>
          <tr class="tableRow" id="tableRowOdd">
            <th scope="row">
              <div>
                File Sharing
              </div>
            </th>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
          </tr>
          <tr class="tableRow">
            <th scope="row">
              <div>
                E-mail Applicatie
              </div>
              <div id="nonBold">
                (Met hoeveelheid opslag)
              </div>
            </th>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">                
              </div>
              <div>
                (50 GB)
            </td>
            <td>
              <div>
                <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">                
              </div>
              <div>
                (2 GB)
              </div>
            </td>
            <td>
              ?????
            </td>
            <td>
              <img src="https://icons.iconarchive.com/icons/icons8/windows-8/32/Very-Basic-Checkmark-icon.png">
            </td>
          </tr>
          <tr class="tableRow" id="tableRowOdd">
            <th scope="row">
              <div>
                Test
              </div>
            </th>
            <td>
              vinkje
            </td>
            <td>
              vinkje
            </td>
            <td>
              vinkje
            </td>
            <td>
              vinkje
            </td>
          </tr>
          <tr class="tableRow">
            <th scope="row">
              <div>
                Test
              </div>
            </th>
            <td>
              vinkje
            </td>
            <td>
              vinkje
            </td>
            <td>
              vinkje
            </td>
            <td>
              vinkje
            </td>
          </tr>
          <tr class="tableRow" id="tableRowOdd">
            <th scope="row">
              <div>
                Test
              </div>
            </th>
            <td>
              vinkje
            </td>
            <td>
              vinkje
            </td>
            <td>
              vinkje
            </td>
            <td>
              vinkje
            </td>
          </tr>
  
