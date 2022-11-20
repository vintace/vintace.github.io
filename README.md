<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tables</title>
    <link rel="stylesheet" href="tables.css">
    <style>
        *{
            margin: 0;
        }
        h2{
            text-align: center;
            clear: both;
            padding: 10px;
        }
        .angel{
            margin: 5px;
            float: left;
            padding: 0px;
        }
        .bella, .rikka, .elaina{
            float: left;
            padding-left: 10px;
            padding-bottom: 5px;
        }
        /* table collapse */
         .angel1{
            border: 1px solid black;
         }
        /* table round */
        .bella2{
            border: 1px solid black;
            border-radius: 10px;
        }
        /* table border style */
        .rikka3{
            border-style: dotted;
        }
        /* table border style */
        .elaina4{
            border: 2px solid red;
            border-collapse: collapse;
        }
        </style>
</head>
<body>
    <h2 style="text-align: center;">Table border</h2>
        <!-- table collapse -->
        <div class="angel">
            <table class="angel1">
                <thead>    
                    <tr>                              <!-- table row -->
                        <th rowspan="2">No</th>       <!-- rowspan -->
                        <th colspan="2">Data</th>     <!-- colspan -->
                        <th rowspan="2">etc</th>      <!-- table head -->
                    </tr>
                    
                    <tr>                              <!-- table row -->
                        <th>Name</th>                 <!-- table head -->
                    <th>Data</th>                 <!-- table head -->
                </tr>        
            </thead>
            <tbody>
                <tr>
                    <td>1</td>                        <!-- table data -->
                    <td>Angel</td>                    <!-- table data -->
                    <td>Rqkiw1o39</td>                <!-- table data -->
                    <td>404!</td>               <!-- table data -->
                </tr>
            </tbody>
        </table> 
    </div>
    <!-- table round -->
    <div class="bella">
        <table class="bella2">
            <thead>    
                <tr>                             <!-- table row -->
                <th rowspan="2" class="tb3">No</th>      <!-- rowspan -->
                <th colspan="2" class="tb3">Data</th>    <!-- colspan -->
                <th rowspan="2" class="tb3">etc</th>     <!-- table head -->
            </tr>
            <tr>                             <!-- table row -->
                    <th class="bella2">Name</th>                <!-- table head -->
                    <th class="bella2">Data</th>                <!-- table head -->
                </tr>        
            </thead>
            <tbody>
                <tr>
                    <td class="bella2">1</td>                  <!-- table data -->
                    <td class="bella2">Bella</td>              <!-- table data -->
                    <td class="bella2">Rqkiw1o39</td>          <!-- table data -->
                    <td class="bella2">404!</td>         <!-- table data -->
                </tr>
            </tbody>
        </table> 
    </div>
    <!-- table border style -->
    <div class="rikka">
        <table class="rikka3">
            <thead>    
            <tr>                              <!-- table row -->
                    <th rowspan="2" class="rikka3">No</th>       <!-- rowspan -->
                    <th colspan="2"class="rikka3">Data</th>     <!-- colspan -->
                    <th rowspan="2"class="rikka3">etc</th>      <!-- table head -->
                </tr>
                
                <tr>                              <!-- table row -->
                    <th class="rikka3">Name</th>                 <!-- table head -->
                    <th class="rikka3">Data</th>                 <!-- table head -->
                </tr>        
            </thead>
            <tbody>
                <tr>
                    <td class="rikka3">1</td>                        <!-- table data -->
                    <td class="rikka3">Rikka</td>                    <!-- table data -->
                    <td class="rikka3">Rqkiw1o39</td>                <!-- table data -->
                    <td class="rikka3">404!</td>               <!-- table data -->
                </tr>
            </tbody>
        </table> 
    </div>
    <!-- table color -->
    <div class="elaina">
    <table class="elaina4">
    <thead>    
        <tr>                              <!-- table row -->
            <th rowspan="2"class="elaina4" >No</th>       <!-- rowspan -->
            <th colspan="2"class="elaina4">Data</th>     <!-- colspan -->
            <th rowspan="2"class="elaina4">etc</th>      <!-- table head -->
        </tr>
        
        <tr>                              <!-- table row -->
            <th class="elaina4">Name</th>                 <!-- table head -->
            <th class="elaina4">Data</th>                 <!-- table head -->
        </tr>        
    </thead>
<tbody>
    <tr>
        <td class="elaina4">1</td>                        <!-- table data -->
        <td class="elaina4">Elaina</td>                    <!-- table data -->
        <td class="elaina4">Rqkiw1o39</td>                <!-- table data -->
        <td class="elaina4">404!</td>               <!-- table data -->
    </tr>
</tbody>
</table>  
</div> 
<!-- table special -->
<h2 class="tbh">Table special</h2>
<div id="tb1">
        <table>
            <thead style="height: 200px;">
                <tr id="tb1">
                    <th rowspan="2" style="width: 20px;">No</td>
                        <th colspan="3">Indentitas</td>
                            <th rowspan="2">Foto</td>
                            </tr>
            <tr>
                <th>Nama</th>
                <th>Tgl Lahir</th>
                <th>Asal sekolah</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Chisato</td>
                <td>21-05-1999</td>
                <td>SMKN1 Kyoto</td>
                <td><img src="./img/std1.jpg" alt="" width="200px"></td>
            </tr>
            <tr>
                <td>2</td>
                <td>takina</td>
                <td>04-04-1994</td>
                <td>SMAN Osaka</td>
                <td><img src="./img/std2.jpg" alt="" width="200px"></td>
            </tr>
            <tr>
                <td>3</td>
                <td>emma</td>
                <td>04-04-1994</td>
                <td>SMKN2 Tokyo</td>
                <td><img src="./img/std3.png" alt="" width="200px"></td>
            </tr>
            <tr>
                <td>4</td>
                <td>takanashi</td>
                <td>04-04-1994</td>
                <td>SMK Aichi</td>
                <td><img src="./img/std4.jpg" alt="" height="200px"></td>
            </tr>
        </tbody>
    </table>
</div>
</body>
</html>
