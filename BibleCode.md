# Bible

<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bible</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <script src="jquery-1.11.3.min.js"></script>
  <script src="bootstrap.min.js"></script>
  <link rel="stylesheet" type="text/css" href="css/bootstrap.css">
  <link rel="stylesheet" type="text/css" href="">
  <script src = "js/jquery-1.11.3.min.js"></script>
    <script src = "js/bootstrap.js"></script>
    <script src = "js/query.js"></script>
    <script src = "js/vquery.js"></script>
</head>
<link rel="stylesheet" type="text/css" href="bootstrap.css">

<body>

<div class="container-fluid">
  <div class = "row">
  <div class = "col-md-4">
    <h2>Bible - Web Application Development</h2>
  <ul class="nav nav-tabs">
    <li class="active"><a href="#home">Old Books</a></li>
    <li><a href="#menu1">New Books</a></li>
  </ul>

  <div class="tab-content">
    <div id="home" class="tab-pane fade in active">
      <table class = "table table-bordered">
      <div class="tab-pane fade in active" id="Old_Testament"><tr><h4>Books</h4></tr></div>
        <td>
            <div style="height: 400px; width: 4/12; overflow: scroll">
          <table class = "table table-striped table table-hover">
            <tr>
              <td>Genesis  
                <td><button  type="button" class="btn btn-success" id = "genesis">Read</button></td>

                <td><button id = "b" type="button" class="btn btn-info" data-toggle = "modal" data-target=".genesis">Info</button>
                    <div class="modal fade genesis" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true">
                        <div class="modal-dialog modal-md">
                            <div class="modal-content">
                                <p><h1>Genesis</h1>
                                    Writer:  <br>
                                   Date writen: <br>
                                   Where was writen:  <br> 


                                </p>
                            </div>
                        </div>
                    </div>


                </td>
                <td><button id = "genvideo" type="button" class="btn btn-primary">Watch</button></td>
              </td>
            </tr>
            <tr>
              <td>Exodus
                <td><button id = "exodus" type="button" class="btn btn-success">Read</button></td>
                <td><button id = "b" type="button" class="btn btn-info" data-toggle = "modal" data-target=".exodus">Info</button>
                    <div class="modal fade exodus" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true">
                        <div class="modal-dialog modal-md">
                            <div class="modal-content">
                                <p><h1>Exodus</h1>
                                   Writer:  <br>
                                   Date writen: <br>
                                   Where was writen:  <br> 


                                </p>
                            </div>
                        </div>
                    </div>
                </td>
                <td><button id = "exovideo" type="button" class="btn btn-primary">Watch</button></td>
              </td>
            </tr>
            <tr>
                <td>Leviticus  
                    <td><button id = "leviticus" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info" data-toggle = "modal" data-target=".leviticus">Info</button>
                    <div class="modal fade leviticus" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true">
                        <div class="modal-dialog modal-md">
                            <div class="modal-content">
                                <p><h1>Leviticus</h1>
                                    Writer:  <br>
                                   Date writen: <br>
                                   Where was writen:  <br> 


                                </p>
                            </div>
                        </div>
                    </div>
                    </td>
                    <td><button id = "exovideo" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>
            <tr>
                <td>Numbers 
                    <td><button id = "numbers" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info" data-toggle = "modal" data-target=".numbers">Info</button>
                    <div class="modal fade numbers" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true">
                        <div class="modal-dialog modal-md">
                            <div class="modal-content">
                                <p><h1>Numbers</h1>
                                    Writer:  <br>
                                   Date writen: <br>
                                   Where was writen:  <br> 


                                </p>
                            </div>
                        </div>
                    </div>
                    </td>
                    <td><button id = "numvideo" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td>Deuteronomy  
                    <td><button id = "deuteronomy" type="button" class="btn btn-success" >Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info" data-toggle = "modal" data-target=".deuteronomy">Info</button>
                    <div class="modal fade deuteronomy" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true">
                        <div class="modal-dialog modal-md">
                            <div class="modal-content">
                                <p><h1>Deuteronomy</h1>
                                    Writer:  <br>
                                   Date writen: <br>
                                   Where was writen:  <br> 


                                </p>
                            </div>
                        </div>
                    </div>
                    </td>
                    <td><button id = "deuvideo" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>
            <tr>
                <td>Joshua  
                    <td><button id = "joshua" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td>Judges  
                    <td><button id = "judges" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td >Ruth  
                    <td><button id = "ruth" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td>I Sammuel 
                    <td><button id = "1sammuel" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td>II Sammuel  
                    <td><button id = "2sammuel" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td>I Kings 
                    <td><button id = "1kings" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td>II Kings  
                    <td><button id = "2kings" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td>I Chronicles  
                    <td><button id = "1chronicles" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td>II Chronicles  
                    <td><button id = "2chronicles" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td>Ezra  
                    <td><button id = "ezra" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td>Nehemiah
                    <td><button id = "nehemiah" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td>Eshter
                    <td><button id = "esther" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td>Job
                    <td><button id = "job" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td>Psalms
                    <td><button id = "psalms" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "proverbs">Proverbs
                    <td><button id = "proverbs" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "ecclesiastes">Ecclesiastes
                    <td><button id = "ecclesiastes" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "songofsolomons">Song of Solomon
                    <td><button id = "songofsolomons" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "isaiah">Isaiah
                    <td><button id = "isaiah" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "jeremiah">Jeremiah
                    <td><button id = "jeremiah" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "lamentation">Lamentation
                    <td><button id = "lamentation" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "ezekiel">Ezekiel
                    <td><button id = "ezekiel" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

             <tr>
                <td id = "daniel">Daniel
                    <td><button id = "daniel" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "hosea">Hosea
                    <td><button id = "hosea" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "joel">Joel
                    <td><button id = "joel" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "amos">Amos
                    <td><button id = "amos" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "obadiah">Obadiah
                    <td><button id = "obadiah" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "jonah">Jonah
                    <td><button id = "jonah" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "micah">Micah
                    <td><button id = "micah" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "nahum">Nahum
                    <td><button id = "nahum" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "habakkuk">Habakkuk
                    <td><button id = "habakkuk" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>  

            <tr>
                <td id = "zephaniah">Zephaniah
                    <td><button id = "zephaniah" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "haggai">Haggai
                    <td><button id = "haggai" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "zechariah">Zechariah
                    <td><button id = "zecharaiah" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "malachi">Malachi
                    <td><button id = "malachi" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

        </div>
          </table>

        </td> 

    </table>
    </div>
    <div id="menu1" class="tab-pane fade">
      <table class = "table table-bordered">
      <div class="tab-pane fade in active" id="New_Testament"><tr><h4>Books</h4></tr></div>
        <td>
            <div style="height: 400px; width: 4/12; overflow: scroll">
          <table class = "table table-striped table table-hover">
           <tr>
                <td id = "mathew">Mathew  
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>
            <tr>
                <td id = "mark">Mark
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>
            <tr>
                <td id = "luke">Luke  
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>
            <tr>
                <td id = "acts">Acts
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "romans">Romans  
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>
            <tr>
                <td id = "1corinthians">I Corinthians  
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "2corinthians">II Corinthians  
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "galatians">Galatians  
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "ephesians">Ephesians 
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "philippians">Philippians  
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "colossians">Colossians 
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "1thessalonians">I Thessalonians  
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "2thessalonians">II Thessalonians  
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "1timothy">I Timothy  
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "2timothy">II Timothy  
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "titus">Titus
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "philemon">Philemon
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "hebrews">Hebrews
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "james">James
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "1peter">I Peter
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "2peter">II Peter
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "1john">I John
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "2john">II John
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "3john">III John
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "jude">Jude
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>

            <tr>
                <td id = "revelation">Revelation
                    <td><button id = "b" type="button" class="btn btn-success">Read</button></td>
                    <td><button id = "b" type="button" class="btn btn-info">Info</button></td>
                    <td><button id = "b" type="button" class="btn btn-primary">Watch</button></td>
                </td>
            </tr>
          </table>
      </div>
        </td> 

    </table>
    </div>
  </div>
    </div>
    <div class = "col-md-8">
            <div id = "readGenesis" hidden  style = "width:850px;height:650px;overflow: scroll;margin-left:15px;margin-top:40px">
                <h2>Genesis</h2>
                <p>
                        <b>1:1</b>In the beginning God created the heaven and the earth. <br>
                        <b>1:2</b>And the earth was without form, and void; and darkness was upon the face of the deep. And the Spirit of God moved upon the face of the waters. <br>
                        <b>1:3</b>And God said, Let there be light: and there was light. <br>
                        <b>1:4</b>And God saw the light, that it was good: and God divided the light from the darkness. <br>
                        <b>1:5</b>And God called the light Day, and the darkness he called Night. And the evening and the morning were the first day. <br>
                        <b>1:6</b>And God said, Let there be a firmament in the midst of the waters, and let it divide the waters from the waters. <br>
                        <b>1:7</b>And God made the firmament, and divided the waters which were under the firmament from the waters which were above the firmament: and it was so. <br>
                        <b>1:8</b>And God called the firmament Heaven. And the evening and the morning were the second day. <br>
                        <b>1:9</b>And God said, Let the waters under the heaven be gathered together unto one place, and let the dry land appear: and it was so. <br>
                        <b>1:1</b>'And God called the dry land Earth; and the gathering together of the waters called he Seas: and God saw that it was good. <br>
                        <b>1:1</b>'And God said, Let the earth bring forth grass, the herb yielding seed, and the fruit tree yielding fruit after his kind, whose seed is in itself, upon the earth: and it was so. <br>
                        <b>1:12</b>'And the earth brought forth grass, and herb yielding seed after his kind, and the tree yielding fruit, whose seed was in itself, after his kind: and God saw that it was good. <br>
                        <b>1:13</b>'And the evening and the morning were the third day. <br>
                        <b>1:14</b>'And God said, Let there be lights in the firmament of the heaven to divide the day from the night; and let them be for signs, and for seasons, and for days, and years: <br>
                        <b>1:15</b>'And let them be for lights in the firmament of the heaven to give light upon the earth: and it was so. <br>
                        <b>1:16</b>'And God made two great lights; the greater light to rule the day, and the lesser light to rule the night: he made the stars also. <br>
                        <b>1:17</b>'And God set them in the firmament of the heaven to give light upon the earth, <br>
                        <b>1:18</b>'And to rule over the day and over the night, and to divide the light from the darkness: and God saw that it was good. <br>
                        <b>1:19</b>'And the evening and the morning were the fourth day. <br>
                        <b>1:20</b>'And God said, Let the waters bring forth abundantly the moving creature that hath life, and fowl that may fly above the earth in the open firmament of heaven <br>
                        <b>1:21</b>'And God created great whales, and every living creature that moveth, which the waters brought forth abundantly, after their kind, and every winged fowl after his kind: and God saw that it was good <br>
                        <b>1:22</b>'And God blessed them, saying, Be fruitful, and multiply, and fill the waters in the seas, and let fowl multiply in the earth <br>
                        <b>1:23</b>'And the evening and the morning were the fifth day <br>
                        <b>1:24</b>'And God said, Let the earth bring forth the living creature after his kind, cattle, and creeping thing, and beast of the earth after his kind: and it was so <br>
                        <b>1:25</b>'And God made the beast of the earth after his kind, and cattle after their kind, and every thing that creepeth upon the earth after his kind: and God saw that it was good <br>
                        <b>1:26</b>'And God said, Let us make man in our image, after our likeness: and let them have dominion over the fish of the sea, and over the fowl of the air, and over the cattle, and over all the earth, and over every creeping thing that creepeth upon the earth <br>
                        <b>1:27</b>'So God created man in his own image, in the image of God created he him; male and female created he them <br>
                        <b>1:28</b>'And God blessed them, and God said unto them, Be fruitful, and multiply, and replenish the earth, and subdue it: and have dominion over the fish of the sea, and over the fowl of the air, and over every living thing that moveth upon the earth <br>
                        <b>1:29</b>'And God said, Behold, I have given you every herb bearing seed, which is upon the face of all the earth, and every tree, in the which is the fruit of a tree yielding seed; to you it shall be for meat <br>
                        <b>1:30</b>'And to every beast of the earth, and to every fowl of the air, and to every thing that creepeth upon the earth, wherein there is life, I have given every green herb for meat: and it was so <br>
                        <b>1:31</b>'And God saw every thing that he had made, and, behold, it was very good. And the evening and the morning were the sixth day. <br>
                </p>
            </div>
            <div id = "watchGen" hidden>
                    <video width ="700" height = "500" controls style = "margin-left:50px;margin-top:80px" >
                        <source src="videos/sample.mp4" type = "video/mp4"><h3>Sample Video</h3>
                    </video> 
            </div>

            <div id = "readExodus" hidden style = "width:850px;height:650px;overflow: scroll;margin-left:15px;margin-top:40px">
                <h2>Exodus</h2>
                <p>
                    <b>1:1</b> 'Now these are the names of the children of Israel, which came into Egypt; every man and his household came with Jacob. <br>
                    <b>1:2</b> 'Reuben, Simeon, Levi, and Judah, <br>
                    <b>1:3</b> 'Issachar, Zebulun, and Benjamin, <br>
                    <b>1:4</b> 'Dan, and Naphtali, Gad, and Asher. <br>
                    <b>1:5</b> 'And all the souls that came out of the loins of Jacob were seventy souls: for Joseph was in Egypt already. <br>
                    <b>1:6</b> 'And Joseph died, and all his brethren, and all that generation. <br>
                    <b>1:7</b> 'And the children of Israel were fruitful, and increased abundantly, and multiplied, and waxed exceeding mighty; and the land was filled with them. <br>
                    <b>1:8</b>'Now there arose up a new king over Egypt, which knew not Joseph. <br>
                    <b>1:9</b>'And he said unto his people, Behold, the people of the children of Israel are more and mightier than we: <br>
                    <b>1:10</b> 'Come on, let us deal wisely with them; lest they multiply, and it come to pass, that, when there falleth out any war, they join also unto our enemies, and fight against us, and so get them up out of the land. <br>
                    <b>1:11</b> 'Therefore they did set over them taskmasters to afflict them with their burdens. And they built for Pharaoh treasure cities, Pithom and Raamses. <br>
                    <b>1:12</b> 'But the more they afflicted them, the more they multiplied and grew. And they were grieved because of the children of Israel. <br>
                    <b>1:13</b> 'And the Egyptians made the children of Israel to serve with rigour: <br>
                    <b>1:14</b> 'And they made their lives bitter with hard bondage, in mortar, and in brick, and in all manner of service in the field: all their service, wherein they made them serve, was with rigour. <br>
                    <b>1:15</b> 'And the king of Egypt spake to the Hebrew midwives, of which the name of the one was Shiphrah, and the name of the other Puah: <br>
                    <b>1:16</b> 'And he said, When ye do the office of a midwife to the Hebrew women, and see them upon the stools; if it be a son, then ye shall kill him: but if it be a daughter, then she shall live. <br>
                    <b>1:17</b> 'But the midwives feared God, and did not as the king of Egypt commanded them, but saved the men children alive. <br>
                    <b>1:18</b> 'And the king of Egypt called for the midwives, and said unto them, Why have ye done this thing, and have saved the men children alive? <br>
                    <b>1:19</b> 'And the midwives said unto Pharaoh, Because the Hebrew women are not as the Egyptian women; for they are lively, and are delivered ere the midwives come in unto them. <br>
                    <b>1:20</b> 'Therefore God dealt well with the midwives: and the people multiplied, and waxed very mighty. <br>
                    <b>1:21</b> 'And it came to pass, because the midwives feared God, that he made them houses. <br>
                    <b>1:22</b> 'And Pharaoh charged all his people, saying, Every son that is born ye shall cast into the river, and every daughter ye shall save alive. <br>
                    <b>2:1</b>'And there went a man of the house of Levi, and took to wife a daughter of Levi. <br>
                    <b>2:2</b>'And the woman conceived, and bare a son: and when she saw him that he was a goodly child, she hid him three months. <br>
                    <b>2:3</b>'And when she could not longer hide him, she took for him an ark of bulrushes, and daubed it with slime and with pitch, and put the child therein; and she laid it in the flags by the river''s brink. <br>
                    <b>2:4</b>'And his sister stood afar off, to wit what would be done to him. <br>
                    <b>2:5</b>'And the daughter of Pharaoh came down to wash herself at the river; and her maidens walked along by the river''s side; and when she saw the ark among the flags, she sent her maid to fetch it. <br>
                    <b>2:6</b>'And when she had opened it, she saw the child: and, behold, the babe wept. And she had compassion on him, and said, This is one of the Hebrews'' children. <br>
                    <b>2:7</b>'Then said his sister to Pharaoh''s daughter, Shall I go and call to thee a nurse of the Hebrew women, that she may nurse the child for thee? <br>
                    <b>2:8</b>'And Pharaoh''s daughter said to her, Go. And the maid went and called the child''s mother. <br>
                    <b>2:9</b>'And Pharaoh''s daughter said unto her, Take this child away, and nurse it for me, and I will give thee thy wages. And the woman took the child, and nursed it. <br>
                    <b>2:10</b> 'And the child grew, and she brought him unto Pharaoh''s daughter, and he became her son. And she called his name Moses: and she said, Because I drew him out of the water. <br>
                    <b>2:11</b> 'And it came to pass in those days, when Moses was grown, that he went out unto his brethren, and looked on their burdens: and he spied an Egyptian smiting an Hebrew, one of his brethren. <br>
                    <b>2:12</b> 'And he looked this way and that way, and when he saw that there was no man, he slew the Egyptian, and hid him in the sand. <br>
                    <b>2:13</b> 'And when he went out the second day, behold, two men of the Hebrews strove together: and he said to him that did the wrong, Wherefore smitest thou thy fellow? <br>
                    <b>2:14</b> 'And he said, Who made thee a prince and a judge over us? intendest thou to kill me, as thou killedst the Egyptian? And Moses feared, and said, Surely this thing is known. <br>
                    <b>2:15</b> 'Now when Pharaoh heard this thing, he sought to slay Moses. But Moses fled from the face of Pharaoh, and dwelt in the land of Midian: and he sat down by a well. <br>
                    <b>2:16</b> 'Now the priest of Midian had seven daughters: and they came and drew water, and filled the troughs to water their father''s flock. <br>
                    <b>2:17</b> 'And the shepherds came and drove them away: but Moses stood up and helped them, and watered their flock. <br>
                    <b>2:18</b> 'And when they came to Reuel their father, he said, How is it that ye are come so soon to day? <br>
                    <b>2:19</b> 'And they said, An Egyptian delivered us out of the hand of the shepherds, and also drew water enough for us, and watered the flock. <br>
                    <b>2:20</b> 'And he said unto his daughters, And where is he? why is it that ye have left the man? call him, that he may eat bread. <br>
                    <b>2:21</b> 'And Moses was content to dwell with the man: and he gave Moses Zipporah his daughter. <br>
                    <b>2:22</b> 'And she bare him a son, and he called his name Gershom: for he said, I have been a stranger in a strange land. <br>
                    <b>2:23</b> 'And it came to pass in process of time, that the king of Egypt died: and the children of Israel sighed by reason of the bondage, and they cried, and their cry came up unto God by reason of the bondage. <br>
                    <b>2:24</b> 'And God heard their groaning, and God remembered his covenant with Abraham, with Isaac, and with Jacob. <br>
                    <b>2:25</b> 'And God looked upon the children of Israel, and God had respect unto them. <br>

                </p>
            </div>
             <div id = "watchexo" hidden>
                    <video width ="700" height = "500" controls style = "margin-left:50px;margin-top:80px" >
                        <source src="videos/sample.mp4" type = "video/mp4"><h3>Sample Video</h3>
                    </video> 
            </div>

            <div id = "readLeviticus" hidden style = "width:850px;height:650px;overflow: scroll;margin-left:15px;margin-top:40px">
                <h2>Leviticus</h2>
                <p>
                    <b>1:1,</b> 'And the LORD called unto Moses, and spake unto him out of the tabernacle of the congregation, saying, <br>
                    <b>1:2,</b> 'Speak unto the children of Israel, and say unto them, If any man of you bring an offering unto the LORD, ye shall bring your offering of the cattle, even of the herd, and of the flock. <br>
                    <b>1:3,</b> 'If his offering be a burnt sacrifice of the herd, let him offer a male without blemish: he shall offer it of his own voluntary will at the door of the tabernacle of the congregation before the LORD. <br>
                    <b>1:4,</b> 'And he shall put his hand upon the head of the burnt offering; and it shall be accepted for him to make atonement for him. <br>
                    <b>1:5,</b> 'And he shall kill the bullock before the LORD: and the priests, Aaron''s sons, shall bring the blood, and sprinkle the blood round about upon the altar that is by the door of the tabernacle of the congregation. <br>
                    <b>1:6,</b> 'And he shall flay the burnt offering, and cut it into his pieces. <br>
                    <b>1:7,</b> 'And the sons of Aaron the priest shall put fire upon the altar, and lay the wood in order upon the fire: <br>
                    <b>1:8,</b> 'And the priests, Aaron''s sons, shall lay the parts, the head, and the fat, in order upon the wood that is on the fire which is upon the altar: <br>
                    <b>1:9,</b> 'But his inwards and his legs shall he wash in water: and the priest shall burn all on the altar, to be a burnt sacrifice, an offering made by fire, of a sweet savour unto the LORD. <br>
                    <b>1:10</b> 'And if his offering be of the flocks, namely, of the sheep, or of the goats, for a burnt sacrifice; he shall bring it a male without blemish. <br>
                    <b>1:11</b> 'And he shall kill it on the side of the altar northward before the LORD: and the priests, Aaron''s sons, shall sprinkle his blood round about upon the altar. <br>
                    <b>1:12</b> 'And he shall cut it into his pieces, with his head and his fat: and the priest shall lay them in order on the wood that is on the fire which is upon the altar: <br>
                    <b>1:13</b> 'But he shall wash the inwards and the legs with water: and the priest shall bring it all, and burn it upon the altar: it is a burnt sacrifice, an offering made by fire, of a sweet savour unto the LORD. <br>
                    <b>1:14</b> 'And if the burnt sacrifice for his offering to the LORD be of fowls, then he shall bring his offering of turtledoves, or of young pigeons. <br>
                    <b>1:15</b> 'And the priest shall bring it unto the altar, and wring off his head, and burn it on the altar; and the blood thereof shall be wrung out at the side of the altar: <br>
                    <b>1:16</b> 'And he shall pluck away his crop with his feathers, and cast it beside the altar on the east part, by the place of the ashes: <br>
                    <b>1:17</b> 'And he shall cleave it with the wings thereof, but shall not divide it asunder: and the priest shall burn it upon the altar, upon the wood that is upon the fire: it is a burnt sacrifice, an offering made by fire, of a sweet savour unto the LORD. <br>
                    <b>2:1</b> 'And when any will offer a meat offering unto the LORD, his offering shall be of fine flour; and he shall pour oil upon it, and put frankincense thereon: <br>
                    <b>2:2</b> 'And he shall bring it to Aaron''s sons the priests: and he shall take thereout his handful of the flour thereof, and of the oil thereof, with all the frankincense thereof; and the priest shall burn the memorial of it upon the altar, to be an offering made by fire, of a sweet savour unto the LORD: <br>
                    <b>2:3</b> 'And the remnant of the meat offering shall be Aaron''s and his sons'': it is a thing most holy of the offerings of the LORD made by fire. <br>
                    <b>2:4</b> 'And if thou bring an oblation of a meat offering baken in the oven, it shall be unleavened cakes of fine flour mingled with oil, or unleavened wafers anointed with oil. <br>
                    <b>2:5</b> 'And if thy oblation be a meat offering baken in a pan, it shall be of fine flour unleavened, mingled with oil. <br>
                    <b>2:6</b> 'Thou shalt part it in pieces, and pour oil thereon: it is a meat offering. <br>
                    <b>2:7</b> 'And if thy oblation be a meat offering baken in the fryingpan, it shall be made of fine flour with oil. <br>
                    <b>2:8</b> 'And thou shalt bring the meat offering that is made of these things unto the LORD: and when it is presented unto the priest, he shall bring it unto the altar. <br>
                    <b>2:9</b> 'And the priest shall take from the meat offering a memorial thereof, and shall burn it upon the altar: it is an offering made by fire, of a sweet savour unto the LORD. <br>
                    <b>2:10</b> 'And that which is left of the meat offering shall be Aaron''s and his sons'': it is a thing most holy of the offerings of the LORD made by fire. <br>
                    <b>2:11</b> 'No meat offering, which ye shall bring unto the LORD, shall be made with leaven: for ye shall burn no leaven, nor any honey, in any offering of the LORD made by fire. <br>
                    <b>2:12</b> 'As for the oblation of the firstfruits, ye shall offer them unto the LORD: but they shall not be burnt on the altar for a sweet savour. <br>
                    <b>2:13</b> 'And every oblation of thy meat offering shalt thou season with salt; neither shalt thou suffer the salt of the covenant of thy God to be lacking from thy meat offering: with all thine offerings thou shalt offer salt. <br>
                    <b>2:14</b> 'And if thou offer a meat offering of thy firstfruits unto the LORD, thou shalt offer for the meat offering of thy firstfruits green ears of corn dried by the fire, even corn beaten out of full ears. <br>
                    <b>2:15</b> 'And thou shalt put oil upon it, and lay frankincense thereon: it is a meat offering. <br>
                    <b>2:16</b> 'And the priest shall burn the memorial of it, part of the beaten corn thereof, and part of the oil thereof, with all the frankincense thereof: it is an offering made by fire unto the LORD. <br>

                </p>
            </div>

            <div id = "readNumbers" hidden style = "width:850px;height:650px;overflow: scroll;margin-left:15px;margin-top:40px">
                <h2>Numbers</h2>
                <p>
                    <b>1:1</b> 'And the LORD spake unto Moses in the wilderness of Sinai, in the tabernacle of the congregation, on the first day of the second month, in the second year after they were come out of the land of Egypt, saying, <br>
                    <b>1:2</b> 'Take ye the sum of all the congregation of the children of Israel, after their families, by the house of their fathers, with the number of their names, every male by their polls; <br>
                    <b>1:3</b> 'From twenty years old and upward, all that are able to go forth to war in Israel: thou and Aaron shall number them by their armies. <br>
                    <b>1:4</b> 'And with you there shall be a man of every tribe; every one head of the house of his fathers. <br>
                    <b>1:5</b> 'And these are the names of the men that shall stand with you: of the tribe of Reuben; Elizur the son of Shedeur. <br>
                    <b>1:6</b> 'Of Simeon; Shelumiel the son of Zurishaddai. <br>
                    <b>1:7</b> 'Of Judah; Nahshon the son of Amminadab. <br>
                    <b>1:8</b> 'Of Issachar; Nethaneel the son of Zuar. <br>
                    <b>1:9</b> 'Of Zebulun; Eliab the son of Helon. <br>
                    <b>1:10</b> 'Of the children of Joseph: of Ephraim; Elishama the son of Ammihud: of Manasseh; Gamaliel the son of Pedahzur. <br>
                    <b>1:11</b> 'Of Benjamin; Abidan the son of Gideoni. <br>
                    <b>1:12</b> 'Of Dan; Ahiezer the son of Ammishaddai. <br>
                    <b>1:13</b> 'Of Asher; Pagiel the son of Ocran. <br>
                    <b>1:14</b> 'Of Gad; Eliasaph the son of Deuel. <br>
                    <b>1:15</b> 'Of Naphtali; Ahira the son of Enan. <br>
                    <b>1:16</b> 'These were the renowned of the congregation, princes of the tribes of their fathers, heads of thousands in Israel. <br>
                    <b>1:17</b> 'And Moses and Aaron took these men which are expressed by their names: <br>
                    <b>1:18</b> 'And they assembled all the congregation together on the first day of the second month, and they declared their pedigrees after their families, by the house of their fathers, according to the number of the names, from twenty years old and upward, by their polls. <br>
                    <b>1:19</b> 'As the LORD commanded Moses, so he numbered them in the wilderness of Sinai. <br>
                    <b>1:20</b> 'And the children of Reuben, Israel''s eldest son, by their generations, after their families, by the house of their fathers, according to the number of the names, by their polls, every male from twenty years old and upward, all that were able to go forth to war; <br>
                    <b>1:21</b> 'Those that were numbered of them, even of the tribe of Reuben, were forty and six thousand and five hundred. <br>
                    <b>1:22</b> 'Of the children of Simeon, by their generations, after their families, by the house of their fathers, those that were numbered of them, according to the number of the names, by their polls, every male from twenty years old and upward, all that were able to go forth to war; <br>
                    <b>1:23</b> 'Those that were numbered of them, even of the tribe of Simeon, were fifty and nine thousand and three hundred. <br>
                    <b>1:24</b> 'Of the children of Gad, by their generations, after their families, by the house of their fathers, according to the number of the names, from twenty years old and upward, all that were able to go forth to war; <br>
                    <b>1:25</b> 'Those that were numbered of them, even of the tribe of Gad, were forty and five thousand six hundred and fifty. <br>
                    <b>1:26</b> 'Of the children of Judah, by their generations, after their families, by the house of their fathers, according to the number of the names, from twenty years old and upward, all that were able to go forth to war; <br>
                    <b>1:27</b> 'Those that were numbered of them, even of the tribe of Judah, were threescore and fourteen thousand and six hundred. <br>
                    <b>1:28</b> 'Of the children of Issachar, by their generations, after their families, by the house of their fathers, according to the number of the names, from twenty years old and upward, all that were able to go forth to war; <br>
                    <b>1:29</b> 'Those that were numbered of them, even of the tribe of Issachar, were fifty and four thousand and four hundred. <br>
                    <b>1:30</b> 'Of the children of Zebulun, by their generations, after their families, by the house of their fathers, according to the number of the names, from twenty years old and upward, all that were able to go forth to war; <br>
                    <b>1:31</b> 'Those that were numbered of them, even of the tribe of Zebulun, were fifty and seven thousand and four hundred. <br>
                    <b>1:32</b> 'Of the children of Joseph, namely, of the children of Ephraim, by their generations, after their families, by the house of their fathers, according to the number of the names, from twenty years old and upward, all that were able to go forth to war; <br>
                    <b>1:33</b> 'Those that were numbered of them, even of the tribe of Ephraim, were forty thousand and five hundred. <br>
                    <b>1:34</b> 'Of the children of Manasseh, by their generations, after their families, by the house of their fathers, according to the number of the names, from twenty years old and upward, all that were able to go forth to war; <br>
                    <b>1:35</b> 'Those that were numbered of them, even of the tribe of Manasseh, were thirty and two thousand and two hundred. <br>
                    <b>1:36</b> 'Of the children of Benjamin, by their generations, after their families, by the house of their fathers, according to the number of the names, from twenty years old and upward, all that were able to go forth to war; <br>
                    <b>1:37</b> 'Those that were numbered of them, even of the tribe of Benjamin, were thirty and five thousand and four hundred <br>,
                    <b>1:38</b> 'Of the children of Dan, by their generations, after their families, by the house of their fathers, according to the number of the names, from twenty years old and upward, all that were able to go forth to war; <br>
                    <b>1:39</b> 'Those that were numbered of them, even of the tribe of Dan, were threescore and two thousand and seven hundred. <br>
                    <b>1:40</b> 'Of the children of Asher, by their generations, after their families, by the house of their fathers, according to the number of the names, from twenty years old and upward, all that were able to go forth to war; <br>
                    <b>1:41</b> 'Those that were numbered of them, even of the tribe of Asher, were forty and one thousand and five hundred. <br>
                    <b>1:42</b> 'Of the children of Naphtali, throughout their generations, after their families, by the house of their fathers, according to the number of the names, from twenty years old and upward, all that were able to go forth to war; <br>
                    <b>1:43</b> 'Those that were numbered of them, even of the tribe of Naphtali, were fifty and three thousand and four hundred. <br>
                    <b>1:44</b> 'These are those that were numbered, which Moses and Aaron numbered, and the princes of Israel, being twelve men: each one was for the house of his fathers. <br>
                    <b>1:45</b> 'So were all those that were numbered of the children of Israel, by the house of their fathers, from twenty years old and upward, all that were able to go forth to war in Israel; <br>
                    <b>1:46</b> 'Even all they that were numbered were six hundred thousand and three thousand and five hundred and fifty. <br>
                    <b>1:47</b> 'But the Levites after the tribe of their fathers were not numbered among them. <br>
                    <b>1:48</b> 'For the LORD had spoken unto Moses, saying, <br>
                    <b>1:49</b> 'Only thou shalt not number the tribe of Levi, neither take the sum of them among the children of Israel: <br>
                    <b>1:50</b> 'But thou shalt appoint the Levites over the tabernacle of testimony, and over all the vessels thereof, and over all things that belong to it: they shall bear the tabernacle, and all the vessels thereof; and they shall minister unto it, and shall encamp round about the tabernacle. <br>
                    <b>1:51</b> 'And when the tabernacle setteth forward, the Levites shall take it down: and when the tabernacle is to be pitched, the Levites shall set it up: and the stranger that cometh nigh shall be put to death. <br>
                    <b>1:52</b> 'And the children of Israel shall pitch their tents, every man by his own camp, and every man by his own standard, throughout their hosts. <br>
                    <b>1:53</b> 'But the Levites shall pitch round about the tabernacle of testimony, that there be no wrath upon the congregation of the children of Israel: and the Levites shall keep the charge of the tabernacle of testimony. <br>
                    <b>1:54</b> 'And the children of Israel did according to all that the LORD commanded Moses, so did they. <br>

                </p>
            </div>

            <div id = "readDeuteronomy" hidden style = "width:850px;height:650px;overflow: scroll;margin-left:15px;margin-top:40px">
                <h2>Deuteronomy</h2>
                 <p>
                    <b>1:1</b> 'These be the words which Moses spake unto all Israel on this side Jordan in the wilderness, in the plain over against the Red sea, between Paran, and Tophel, and Laban, and Hazeroth, and Dizahab. <br>
                    <b>1:2</b> '(There are eleven days'' journey from Horeb by the way of mount Seir unto Kadeshbarnea.) <br>
                    <b>1:3</b> 'And it came to pass in the fortieth year, in the eleventh month, on the first day of the month, that Moses spake unto the children of Israel, according unto all that the LORD had given him in commandment unto them; <br>
                    <b>1:4</b> 'After he had slain Sihon the king of the Amorites, which dwelt in Heshbon, and Og the king of Bashan, which dwelt at Astaroth in Edrei: <br>
                    <b>1:5</b> 'On this side Jordan, in the land of Moab, began Moses to declare this law, saying, <br>
                    <b>1:6</b> 'The LORD our God spake unto us in Horeb, saying, Ye have dwelt long enough in this mount: <br>
                    <b>1:7</b> 'Turn you, and take your journey, and go to the mount of the Amorites, and unto all the places nigh thereunto, in the plain, in the hills, and in the vale, and in the south, and by the sea side, to the land of the Canaanites, and unto Lebanon, unto the great river, the river Euphrates. <br>
                    <b>1:8</b> 'Behold, I have set the land before you: go in and possess the land which the LORD sware unto your fathers, Abraham, Isaac, and Jacob, to give unto them and to their seed after them. <br>
                    <b>1:9</b> 'And I spake unto you at that time, saying, I am not able to bear you myself alone: <br>
                    <b>1:10</b>, 'The LORD your God hath multiplied you, and, behold, ye are this day as the stars of heaven for multitude. <br>
                    <b>1:11</b> '(The LORD God of your fathers make you a thousand times so many more as ye are, and bless you, as he hath promised you!) <br>
                    <b>1:12</b> 'How can I myself alone bear your cumbrance, and your burden, and your strife? <br>
                    <b>1:13</b> 'Take you wise men, and understanding, and known among your tribes, and I will make them rulers over you. <br>
                    <b>1:14</b> 'And ye answered me, and said, The thing which thou hast spoken is good for us to do. <br>
                    <b>1:15</b> 'So I took the chief of your tribes, wise men, and known, and made them heads over you, captains over thousands, and captains over hundreds, and captains over fifties, and captains over tens, and officers among your tribes. <br>
                    <b>1:16</b> 'And I charged your judges at that time, saying, Hear the causes between your brethren, and judge righteously between every man and his brother, and the stranger that is with him. <br>
                    <b>1:17</b> 'Ye shall not respect persons in judgment; but ye shall hear the small as well as the great; ye shall not be afraid of the face of man; for the judgment is God''s: and the cause that is too hard for you, bring it unto me, and I will hear it. <br>
                    <b>1:18</b> 'And I commanded you at that time all the things which ye should do. <br>
                    <b>1:19</b> 'And when we departed from Horeb, we went through all that great and terrible wilderness, which ye saw by the way of the mountain of the Amorites, as the LORD our God commanded us; and we came to Kadeshbarnea. <br>
                    <b>1:20</b> 'And I said unto you, Ye are come unto the mountain of the Amorites, which the LORD our God doth give unto us. <br>
                    <b>1:21</b> 'Behold, the LORD thy God hath set the land before thee: go up and possess it, as the LORD God of thy fathers hath said unto thee; fear not, neither be discouraged. <br>
                    <b>1:22</b> 'And ye came near unto me every one of you, and said, We will send men before us, and they shall search us out the land, and bring us word again by what way we must go up, and into what cities we shall come. <br>
                    <b>1:23</b> 'And the saying pleased me well: and I took twelve men of you, one of a tribe: <br>
                    <b>1:24</b> 'And they turned and went up into the mountain, and came unto the valley of Eshcol, and searched it out.'),
                    <b>1:25</b> 'And they took of the fruit of the land in their hands, and brought it down unto us, and brought us word again, and said, It is a good land which the LORD our God doth give us. <br>
                    <b>1:26</b> 'Notwithstanding ye would not go up, but rebelled against the commandment of the LORD your God: <br>
                    <b>1:27</b> 'And ye murmured in your tents, and said, Because the LORD hated us, he hath brought us forth out of the land of Egypt, to deliver us into the hand of the Amorites, to destroy us. <br>
                    <b>1:28</b> 'Whither shall we go up? our brethren have discouraged our heart, saying, The people is greater and taller than we; the cities are great and walled up to heaven; and moreover we have seen the sons of the Anakims there. <br>
                    <b>1:29</b> 'Then I said unto you, Dread not, neither be afraid of them. <br>
                    <b>1:30</b> 'The LORD your God which goeth before you, he shall fight for you, according to all that he did for you in Egypt before your eyes; <br>
                    <b>1:31</b> 'And in the wilderness, where thou hast seen how that the LORD thy God bare thee, as a man doth bear his son, in all the way that ye went, until ye came into this place. <br>
                    <b>1:32</b> 'Yet in this thing ye did not believe the LORD your God, <br>
                    <b>1:33</b> 'Who went in the way before you, to search you out a place to pitch your tents in, in fire by night, to shew you by what way ye should go, and in a cloud by day. <br>
                    <b>1:34</b> 'And the LORD heard the voice of your words, and was wroth, and sware, saying, <br>
                    <b>1:35</b> 'Surely there shall not one of these men of this evil generation see that good land, which I sware to give unto your fathers, <br>
                    <b>1:36</b> 'Save Caleb the son of Jephunneh; he shall see it, and to him will I give the land that he hath trodden upon, and to his children, because he hath wholly followed the LORD. <br>
                    <b>1:37</b> 'Also the LORD was angry with me for your sakes, saying, Thou also shalt not go in thither. <br>
                    <b>1:38</b> 'But Joshua the son of Nun, which standeth before thee, he shall go in thither: encourage him: for he shall cause Israel to inherit it. <br>
                    <b>1:39</b> 'Moreover your little ones, which ye said should be a prey, and your children, which in that day had no knowledge between good and evil, they shall go in thither, and unto them will I give it, and they shall possess it. <br>
                    <b>1:40</b> 'But as for you, turn you, and take your journey into the wilderness by the way of the Red sea. <br>
                    <b>1:41</b> 'Then ye answered and said unto me, We have sinned against the LORD, we will go up and fight, according to all that the LORD our God commanded us. And when ye had girded on every man his weapons of war, ye were ready to go up into the hill. <br>
                    <b>1:42</b> 'And the LORD said unto me, Say unto them, Go not up, neither fight; for I am not among you; lest ye be smitten before your enemies. <br>
                    <b>1:43</b> 'So I spake unto you; and ye would not hear, but rebelled against the commandment of the LORD, and went presumptuously up into the hill. <br>
                    <b>1:44</b> 'And the Amorites, which dwelt in that mountain, came out against you, and chased you, as bees do, and destroyed you in Seir, even unto Hormah. <br>
                    <b>1:45</b> 'And ye returned and wept before the LORD; but the LORD would not hearken to your voice, nor give ear unto you. <br>
                    <b>1:46</b> 'So ye abode in Kadesh many days, according unto the days that ye abode there.'),

                </p>
            </div>

            <div id = "readJoshua" hidden style = "width:850px;height:650px;overflow: scroll;margin-left:15px;margin-top:40px">
                <h2>Joshua</h2>
                 <p>
                    <b>1:1</b>'Now after the death of Moses the servant of the LORD it came to pass, that the LORD spake unto Joshua the son of Nun, Moses'' minister, saying, <br>
                    <b>1:2</b>'Moses my servant is dead; now therefore arise, go over this Jordan, thou, and all this people, unto the land which I do give to them, even to the children of Israel. <br>
                    <b>1:3</b>'Every place that the sole of your foot shall tread upon, that have I given unto you, as I said unto Moses. <br>
                    <b>1:4</b>'From the wilderness and this Lebanon even unto the great river, the river Euphrates, all the land of the Hittites, and unto the great sea toward the going down of the sun, shall be your coast. <br>
                    <b>1:5</b>'There shall not any man be able to stand before thee all the days of thy life: as I was with Moses, so I will be with thee: I will not fail thee, nor forsake thee. <br>
                    <b>1:6</b>'Be strong and of a good courage: for unto this people shalt thou divide for an inheritance the land, which I sware unto their fathers to give them. <br>
                    <b>1:7</b>'Only be thou strong and very courageous, that thou mayest observe to do according to all the law, which Moses my servant commanded thee: turn not from it to the right hand or to the left, that thou mayest prosper whithersoever thou goest. <br>
                    <b>1:8</b>'This book of the law shall not depart out of thy mouth; but thou shalt meditate therein day and night, that thou mayest observe to do according to all that is written therein: for then thou shalt make thy way prosperous, and then thou shalt have good success. <br>
                    <b>1:9</b>'Have not I commanded thee? Be strong and of a good courage; be not afraid, neither be thou dismayed: for the LORD thy God is with thee whithersoever thou goest. <br>
                    <b>1:10</b> 'Then Joshua commanded the officers of the people, saying, <br>
                    <b>1:11</b> 'Pass through the host, and command the people, saying, Prepare you victuals; for within three days ye shall pass over this Jordan, to go in to possess the land, which the LORD your God giveth you to possess it. <br>
                    <b>1:12</b> 'And to the Reubenites, and to the Gadites, and to half the tribe of Manasseh, spake Joshua, saying, <br>
                    <b>1:13</b> 'Remember the word which Moses the servant of the LORD commanded you, saying, The LORD your God hath given you rest, and hath given you this land. <br>
                    <b>1:14</b> 'Your wives, your little ones, and your cattle, shall remain in the land which Moses gave you on this side Jordan; but ye shall pass before your brethren armed, all the mighty men of valour, and help them; <br>
                    <b>1:15</b> 'Until the LORD have given your brethren rest, as he hath given you, and they also have possessed the land which the LORD your God giveth them: then ye shall return unto the land of your possession, and enjoy it, which Moses the LORD''S servant gave you on this side Jordan toward the sunrising. <br>
                    <b>1:16</b> 'And they answered Joshua, saying, All that thou commandest us we will do, and whithersoever thou sendest us, we will go. <br>
                    <b>1:17</b> 'According as we hearkened unto Moses in all things, so will we hearken unto thee: only the LORD thy God be with thee, as he was with Moses. <br>
                    <b>1:18</b> 'Whosoever he be that doth rebel against thy commandment, and will not hearken unto thy words in all that thou commandest him, he shall be put to death: only be strong and of a good courage.'),

                </p>


            </div>

</div>
</div>


<script>
$(document).ready(function(){
    $(".nav-tabs a").click(function(){
        $(this).tab('show');
    });
});
</script>

</body>
</html>
