Week-1, Day-6
===
   
   
Today, we did team project that Business communication Platform using bootstrap   
We use collapse and card today   
https://getbootstrap.com/docs/5.0/components/collapse/   
https://getbootstrap.com/docs/5.0/components/card/    

![image]![image](https://user-images.githubusercontent.com/57173871/125386008-87748900-e3d6-11eb-9a64-1f37c14d8ff5.png)

* * *
   

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Business Communication Platform</title>
    <!-- Please do not touch this stylesheet! -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
    rel="stylesheet"
    integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC"
    crossorigin="anonymous">
    <link rel="stylesheet" href="MainStyle.css">

</head>

<body>
    <!-- Please do not change the container! -->
    <div class="container-fluid vh-100">
        <!-- Please do not put anything inside of the row! -->
        <div class="row h-100">
            <!-- This is the left column. -->
          <div class="col-4 col-md-3 border bg-light text-white">
            <div class="Channels rounded-top"> 
                <!--&nbsp;Channels-->
                <p>
                    <button class="btn btn-primary text-dark bg-white border border-blue border-3" type="button" data-bs-toggle="collapse"
                        data-bs-target="#Chatrooms" aria-expanded="false" aria-controls="multiCollapseExample2">
                            Chatrooms</button>
                </p>

                <div class="row">
                    <div class="col">
                        <div class= "collapse multi-collapse" id="Chatrooms">
                            <div class="card card-body skybox">
                                <ul class ="list-group">
                                    <li class= "list-group-item">General</li>
                                    <li class= "list-group-item">Marketing</li>
                                    <li class="list-group-item">Operations</li>
                                    <li class= "list-group-item">Random</li>
                                    <li class="list-group-item">Standups</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                <br>

                <p>
                        <button class="btn btn-primary text-dark bg-white border border-blue border-3" type="button" data-bs-toggle="collapse"
                        data-bs-target="#People" aria-expanded="false" aria-controls="multiCollapseExample1 multiCollapseExample2">
                            People</button>
                </p>
            </div>

            <div class="DM bg-info rounded-top">
                <!--&nbsp;Direct Messages-->
                <div class="collapse" id="People">
                    <div class="card card-body skybox">
                        <ul class ="list-group">
                            <li class= "list-group-item">Liam</li>
                            <li class= "list-group-item">Lyn</li>
                            <li class="list-group-item">Melanie</li>
                            <li class="list-group-item">Gayeon</li>
                        </ul>
                    </div>
                </div>
            </div>
        

<!------------------------------- RIGHT SIDE FROM HERE!------------------------------------>

        </div>
          <!-- This is the right column. -->
          <div class="col-8 col-md-9 border border-primary bg-dark text-black">
              <div class="text-white">Business Communication Platform</div>

              <div class="card mb-1" >
                <div class="row g-4">
                  <div class="col-md-2">
                    <img src="https://avatars.githubusercontent.com/u/57173871?v=4"
                    class="img-fluid rounded-start rounded-circle border border-white border-5" style="width:150px;height:130px;" alt="..."
                    >
                  </div>
                  <div class="col-md-8">
                    <div class="card-body">
                      <h5 class="card-title">Liam</h5>
                      <p class="card-text">I want to scroll down the chat window, do you want to do it later?</p>
                      <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                    </div>
                  </div>
                </div>
              </div>

              <div class="card mb-1" >
                <div class="row g-4">
                  <div class="col-md-2">
                    <img src="https://avatars.githubusercontent.com/u/86810056?s=400&u=80b6b33a27aeb02ee2c7eb99b8d5bcd2f27e39ca&v=4"
                    class="img-fluid rounded-start rounded-circle border border-white border-5" style="width:150px;height:130px;" alt=""
                    >
                  </div>
                  <div class="col-md-8">
                    <div class="card-body">
                      <h5 class="card-title"></h5>
                      <p class="card-text">for that i believe it is we have to use the display flex</p>
                      <p class="card-text"><small class="text-muted">Last updated 2 mins ago</small></p>
                    </div>
                  </div>
                </div>
              </div>

              <div class="card mb-1" >
                <div class="row g-4">
                  <div class="col-md-2"> 
                    <img src="https://static.wikia.nocookie.net/helltaker/images/9/9f/Justice2Think.png"
                    class="img-fluid rounded-start rounded-circle border border-white border-5" style="width:150px;height:130px;" alt=""
                    >
                  </div>
                  <div class="col-md-8">
                    <div class="card-body">
                      <h5 class="card-title"></h5>
                      <p class="card-text">I can solve that problem</p>
                      <p class="card-text"><small class="text-muted">Last updated 1 mins ago</small></p>
                    </div>
                  </div>
                </div>
              </div>

              <div class="card mb-2" >
                <div class="row g-4">
                  <div class="col-md-2">
                    <img src="https://play-lh.googleusercontent.com/hjJxprwkClyF4b6YY6zIt2eXZpn7eh68y5EWdiBmBqVz8Z0KiuFIf5KMTWJG8j5Lzio"
                    class="img-fluid rounded-start rounded-circle border border-white border-5" style="width:150px;height:130px;" alt=""
                    >
                  </div>
                  <div class="col-md-8">
                    <div class="card-body">
                      <h5 class="card-title"></h5>
                      <p class="card-text">Good!</p>
                      <p class="card-text"><small class="text-muted">Last updated 36 sec ago</small></p>
                    </div>
                  </div>
                </div>
              </div>


              <div class="container">
                <div class="input-group col-6 align-items-end">
                    <textarea class="form-control align-items-end" aria-label="With textarea"
                    placeholder="Enter your message here"></textarea>
                    </textarea>
                </div>
            </div>

          </div>
        </div>
      </div>

    <!-- Please do not touch this script! -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</body>
</html>

```
