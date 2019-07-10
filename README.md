# Personal

<!DOCTYPE html>
<html>
    <head>
        <title>Laravel</title>
        <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.bundle.min.js" integrity="sha384-xrRywqdh3PHs8keKZN+8zzc5TX0GRTLCcmivcbNJWm2rs5C8PRhcEn3czEjhAO9o" crossorigin="anonymous"></script>
        <link href="{{ url('style.css')}}" rel="stylesheet" type="text/css">
        
        <link href="https://fonts.googleapis.com/css?family=Lato:100" rel="stylesheet" type="text/css">
        <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0">
    </head>
    <body>
        <div class="container">
            <div class="row">
                <div class="col-lg-8 pr-1 pl-1">
                    <div class="image-bg-test">
                    <img src="https://colorlib.com/preview/theme/newsbit/images/slider-1-1200x900.jpg" class="img-fluid">
                    </div>
                    <div class="text">
                        <span>Test</span>
                    </div>
                </div>

                <!-- only add pr-1 and pr-2 when on large screens -->
                <div class="col-lg-4 pr-1 pl-1">

                    <img src="https://colorlib.com/preview/theme/newsbit/images/slider-2-450x600.jpg" class="img-fluid">

                    <img src="https://colorlib.com/preview/theme/newsbit/images/slider-3-450x600.jpg" class="img-fluid mt-1">
                    

                    
                </div>
            </div>


   html, body {
                height: 100%;
            }

            .image-bg-test{
                position: relative;
            }
            .text{
                position: absolute;
                bottom: 0;
                
            }
