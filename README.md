I have created frontend with HTML/CSS/BOOTSTRAP
Responsive Frontend
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Furniture Website</title>
    <link rel="stylesheet" href="css/style.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="stylesheet" href="css/media.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Playfair+Display:ital,wght@0,400..900;1,400..900&display=swap" rel="stylesheet">
</head>

<body>
    <!-- navbar-section -->
    <nav class="navbar navbar-expand-lg ">
        <div class="container-fluid">
            <a class="navbar-brand fw-bold" href="#">Furniture</a>
            <button class="navbar-toggler ms-auto" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        height="24"
                        viewBox="0 -960 960 960"
                        width="24"
                    >
                        <path d="M120-240v-80h720v80H120Zm0-200v-80h720v80H120Zm0-200v-80h720v80H120Z"/>
                    </svg>
                </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Services</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Doctors</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Gallery</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <!-- banner -->
    <section>
        <div class="banner">
            <img src="image/MaskGroup.jpg" alt="Snow">
            <div class="banner_dcenter">
                <div class="banner_div">
                    <h4>New Arrival</h4>
                    <h1>Discover Our</h1>
                    <h1>New Collection</h1>
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus, luctus nec ullamcorper mattis.
                    </p>
                    <button class="btn rounded-pill">BUY NOW</button>
                </div>
            </div>
        </div>
    </section>
    <!-- banner--Footer support/authentic and free delivery -->
    <section>
        <div class="banner-footer ">
            <div class="container">
                <div class="row">
                    <div class="col-md-4 col-lg-4 col-sm">
                        <div class="container-delivery">
                            <div>
                                <!-- <img src="image/Group.svg" alt="" class=""> -->
                                <svg width="65" height="44" viewBox="0 0 84 51" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <path d="M3.038 20.3621H2.22852C0.997617 20.3621 0 21.36 0 22.5906C0 23.8212 0.997617 24.8191 2.22852 24.8191H3.038C4.26828 24.8191 5.26657 23.8212 5.26657 22.5906C5.26657 21.36 4.26859 20.3621 3.038 20.3621Z" fill="#111111"/>
                                        <path d="M21.5707 24.8191C22.8013 24.8191 23.7995 23.8212 23.7995 22.5906C23.7995 21.36 22.8013 20.3621 21.5707 20.3621H9.20313C7.97286 20.3621 6.97461 21.36 6.97461 22.5906C6.97461 23.8212 7.97286 24.8191 9.20313 24.8191H21.5707Z" fill="#111111"/>
                                        <path d="M10.5781 16.5465H11.3784C12.6096 16.5465 13.6069 15.5486 13.6069 14.3183C13.6069 13.0871 12.6096 12.0895 11.3784 12.0895H10.5781C9.34723 12.0895 8.34961 13.0874 8.34961 14.3183C8.34961 15.5486 9.34723 16.5465 10.5781 16.5465Z" fill="#111111"/>
                                        <path d="M24.0084 12.0895H17.5443C16.3131 12.0895 15.3154 13.0874 15.3154 14.3183C15.3154 15.5489 16.3131 16.5465 17.5443 16.5465H24.0084C25.2393 16.5465 26.2369 15.5486 26.2369 14.3183C26.2369 13.0871 25.2393 12.0895 24.0084 12.0895Z" fill="#111111"/>
                                        <path d="M11.3883 28.6357H10.5781C9.34723 28.6357 8.34961 29.6337 8.34961 30.8646C8.34961 32.0952 9.34723 33.0928 10.5781 33.0928H11.3883C12.6192 33.0928 13.6168 32.0949 13.6168 30.8646C13.6168 29.6337 12.6192 28.6357 11.3883 28.6357Z" fill="#111111"/>
                                        <path d="M24.0083 28.6357H17.5538C16.3229 28.6357 15.3252 29.6337 15.3252 30.8646C15.3252 32.0952 16.3229 33.0928 17.5538 33.0928H24.0083C25.2392 33.0928 26.2368 32.0949 26.2368 30.8646C26.2368 29.6337 25.2392 28.6357 24.0083 28.6357Z" fill="#111111"/>
                                        <path d="M83.3369 24.5136L72.6408 12.8147C72.219 12.3526 71.6215 12.0895 70.9957 12.0895H58.3498V2.61916C58.3498 1.38825 57.3522 0.390625 56.1212 0.390625H15.5083C14.2774 0.390625 13.2798 1.38857 13.2798 2.61916C13.2798 3.84975 14.2774 4.84769 15.5083 4.84769H53.8924V40.3352H34.6721C33.7094 37.1014 30.7114 34.7362 27.1697 34.7362C23.6279 34.7362 20.6293 37.1014 19.6676 40.3352H15.5083C14.2774 40.3352 13.2798 41.3328 13.2798 42.5634C13.2798 43.7946 14.2774 44.792 15.5083 44.792H19.6676C20.6293 48.0251 23.6279 50.3906 27.1697 50.3906C30.7114 50.3906 33.7094 48.0251 34.6721 44.792H56.1209H61.4037C62.3664 48.0251 65.365 50.3906 68.9061 50.3906C72.4485 50.3906 75.4465 48.0251 76.4088 44.792H81.6919C82.9228 44.792 83.9204 43.7943 83.9204 42.5634V26.0172C83.9211 25.4613 83.7122 24.9245 83.3369 24.5136ZM27.1697 45.9342C25.3114 45.9342 23.7995 44.4223 23.7995 42.5637C23.7995 40.7054 25.3114 39.1933 27.1697 39.1933C29.028 39.1933 30.5398 40.7058 30.5398 42.5637C30.5401 44.4223 29.028 45.9342 27.1697 45.9342ZM68.9064 45.9342C67.0481 45.9342 65.5363 44.4223 65.5363 42.5637C65.5363 40.7054 67.0485 39.1933 68.9064 39.1933C70.7653 39.1933 72.2772 40.7058 72.2772 42.5637C72.2775 44.4223 70.7653 45.9342 68.9064 45.9342ZM76.4094 40.3355C75.4471 37.1017 72.4491 34.7365 68.9067 34.7365C65.3653 34.7365 62.367 37.1017 61.4043 40.3355H58.3501V16.5469H70.0143L76.6354 23.789H64.012C62.7817 23.789 61.7841 24.7869 61.7841 26.0175C61.7841 27.2487 62.7817 28.2461 64.012 28.2461H79.464V40.3352H76.4094V40.3355Z" fill="#111111"/>
                                    </svg>
                            </div>
                            <div class="child-delivery">
                                <h5>Free&nbsp;Delivery</h5>
                                <p>Lorem ipsum dolor sit amet.</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 col-lg-4 col-sm">
                        <div class="container-support">
                            <div>
                                <!-- <img src="image/Group2.svg" alt="" class=""> -->
                                <svg width="65" height="44" viewBox="0 0 60 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <path d="M17.2233 32.6246H27.413C28.2923 32.6246 29.005 31.9119 29.005 31.0331C29.005 30.1538 28.2921 29.4406 27.413 29.4406H21.0663L27.0219 23.4854C28.3005 22.2067 29.005 20.5067 29.005 18.6981C29.005 16.8898 28.3005 15.1898 27.0219 13.9111C25.7434 12.6323 24.0432 11.9282 22.2349 11.9282C20.4263 11.9282 18.7263 12.6325 17.4479 13.9111C16.826 14.5325 16.826 15.5408 17.4479 16.1626C18.0697 16.784 19.0775 16.784 19.6994 16.1622C20.3764 15.4849 21.2772 15.1121 22.2349 15.1121C23.1927 15.1121 24.0934 15.4849 24.7706 16.1626C25.4481 16.8394 25.8209 17.74 25.8209 18.6981C25.8209 19.656 25.4481 20.5566 24.7706 21.2339L16.0972 29.9074C15.6418 30.3624 15.5058 31.0474 15.7519 31.6424C15.9987 32.237 16.5792 32.6246 17.2233 32.6246Z" fill="#111111"/>
                                        <path d="M42.7248 29.4413H41.372V26.2436C41.372 25.3647 40.6593 24.6516 39.78 24.6516C38.9007 24.6516 38.1883 25.3647 38.1883 26.2436V29.4413H34.3759L41.2323 14.1727C41.5924 13.3708 41.2341 12.4284 40.432 12.0683C39.6299 11.7082 38.6877 12.0663 38.3277 12.8682L30.4635 30.3812C30.2423 30.8737 30.2857 31.4449 30.579 31.8985C30.8726 32.3517 31.3755 32.625 31.9156 32.625H38.188V35.8232C38.188 36.7021 38.9005 37.4154 39.7798 37.4154C40.6593 37.4154 41.3717 36.7021 41.3717 35.8232V32.625H42.7246C43.6039 32.625 44.3168 31.9124 44.3168 31.0335C44.317 30.1542 43.6039 29.4413 42.7248 29.4413Z" fill="#333333"/>
                                        <path d="M59.7354 23.8765C59.4511 23.384 58.9253 23.0803 58.3568 23.0803H54.5938C54.2146 17.0898 51.7023 11.5095 47.4195 7.22723C42.7596 2.56738 36.5641 0.0012207 29.9743 0.0012207C29.095 0.0012207 28.3823 0.713875 28.3823 1.59295C28.3823 2.47247 29.0952 3.18489 29.9743 3.18489C41.2871 3.18489 50.5855 11.9727 51.4028 23.0805H47.751C47.182 23.0805 46.6567 23.3843 46.3724 23.8767C46.0877 24.3694 46.0877 24.9762 46.3724 25.4689L51.675 34.6537C51.9597 35.1464 52.4851 35.4495 53.0536 35.4495C53.6225 35.4495 54.1481 35.1464 54.4323 34.6537L59.7351 25.4689C60.0194 24.976 60.0194 24.3691 59.7354 23.8765ZM53.0536 30.6732L50.5083 26.2642H55.5995L53.0536 30.6732Z" fill="#111111"/>
                                        <path d="M25.007 3.18437C25.4256 3.18437 25.8363 3.01366 26.1326 2.71739C26.4287 2.42134 26.5992 2.01062 26.5992 1.5922C26.5992 1.17241 26.4289 0.762617 26.1326 0.466565C25.8366 0.169379 25.4256 0 25.007 0C24.5874 0 24.1776 0.169379 23.8809 0.466565C23.5848 0.762617 23.415 1.17332 23.415 1.5922C23.415 2.01062 23.5848 2.42134 23.8809 2.71739C24.1776 3.01366 24.5874 3.18437 25.007 3.18437Z" fill="#111111"/>
                                        <path d="M20.2313 3.18437C20.6498 3.18437 21.0607 3.01366 21.3567 2.71739C21.6539 2.42134 21.8233 2.01062 21.8233 1.5922C21.8233 1.17241 21.6539 0.762617 21.3567 0.466565C21.0607 0.169379 20.6498 0 20.2313 0C19.8127 0 19.402 0.169379 19.1057 0.466565C18.8085 0.762617 18.6392 1.17241 18.6392 1.5922C18.6392 2.01062 18.8085 2.42134 19.1057 2.71739C19.4018 3.01366 19.8127 3.18437 20.2313 3.18437Z" fill="#111111"/>
                                        <path d="M29.9745 46.1589C24.2347 46.1589 18.839 43.9238 14.7803 39.8656C11.0994 36.1847 8.91854 31.4031 8.54485 26.2633H12.1976C12.198 26.2633 12.1985 26.2633 12.199 26.2633C13.0783 26.2633 13.7909 25.5507 13.7909 24.6714C13.7909 24.3563 13.6992 24.062 13.5409 23.815L8.2731 14.6908C7.98908 14.1983 7.46326 13.895 6.89455 13.895C6.32583 13.895 5.80024 14.1983 5.516 14.6908L0.213184 23.8756C-0.0710614 24.3683 -0.0710614 24.9751 0.213184 25.4678C0.49743 25.9605 1.02302 26.2636 1.59173 26.2636H5.35458C5.73417 32.2547 8.2463 37.8343 12.5288 42.1168C17.1887 46.7771 23.3842 49.3431 29.9743 49.3431C30.8536 49.3431 31.566 48.6304 31.566 47.7509C31.5662 46.872 30.8538 46.1589 29.9745 46.1589ZM6.89477 18.6707L9.44027 23.0794H4.34928L6.89477 18.6707Z" fill="#111111"/>
                                        <path d="M34.9416 46.1584C34.5229 46.1584 34.1122 46.3292 33.8159 46.6248C33.5199 46.921 33.3496 47.3317 33.3496 47.7504C33.3496 48.17 33.5199 48.58 33.8159 48.8762C34.112 49.173 34.5229 49.3426 34.9416 49.3426C35.3611 49.3426 35.7709 49.173 36.0679 48.8762C36.3639 48.58 36.5333 48.1695 36.5333 47.7504C36.5333 47.3317 36.3639 46.921 36.0679 46.6248C35.7709 46.3292 35.3611 46.1584 34.9416 46.1584Z" fill="#111111"/>
                                        <path d="M39.7174 46.1584C39.2979 46.1584 38.8879 46.3292 38.5918 46.6248C38.2949 46.921 38.1255 47.3317 38.1255 47.7504C38.1255 48.1695 38.2951 48.58 38.5918 48.8762C38.8879 49.173 39.2979 49.3426 39.7174 49.3426C40.1361 49.3426 40.547 49.173 40.8428 48.8762C41.1389 48.58 41.3096 48.1695 41.3096 47.7504C41.3096 47.3317 41.1391 46.921 40.8428 46.6248C40.547 46.3292 40.1359 46.1584 39.7174 46.1584Z" fill="#111111"/>
                                    </svg>
                            </div>
                            <div class="child-support">
                                <h5>Support&nbsp;24/7</h5>
                                <p>Lorem ipsum dolor sit amet.</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 col-lg-4 col-sm">
                        <div class="container-authentic">
                            <div>
                                <!-- <img src="image/shield-1.png" alt="" class=""> -->
                                <svg width="65" height="44" viewBox="0 0 55 55" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                                        <rect width="55" height="55" fill="url(#pattern0_40_0)"/>
                                        <defs>
                                            <pattern
                                                id="pattern0_40_0"
                                                patternContentUnits="objectBoundingBox"
                                                width="1"
                                                height="1"
                                            >
                                                <use xlink:href="#image0_40_0" transform="scale(0.0181818)"/>
                                            </pattern>
                                            <image
                                                id="image0_40_0"
                                                width="55"
                                                height="55"
                                                xlink:href="data:image/png;base64,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"
                                            />
                                        </defs>
                                    </svg>
                            </div>
                            <div class="child-authentic">
                                <h5>100%&nbsp;Authentic</h5>
                                <p>Lorem ipsum dolor sit amet.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- inspiration-collection -->
    <div class="insp">
        <div class="container">
            <div class="row">
                <h4>Inspiration Collection</h4>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
        </div>
    </div>
    <div class="img_set">
        <div class="container">
            <div class="row">
                <div class="col-md-4 col-lg-4">
                    <img src="image/Mask Group1.png" alt="" class="">
                </div>
                <div class="col-md-4 col-lg-4">
                    <div class="middle-pic">
                        <img src="image/Mask Group2.png" alt="" class="">
                    </div>
                </div>
                <div class="col-md-4 col-lg-4">
                    <img src="image/Mask Group3.png" alt="" class="">
                </div>
            </div>
        </div>
    </div>
    </div>
    <!-- beauty your space -->
    <div class="beauty-space">
        <div class="container">
            <div class="row">
                <div class="col-sm-6 col-md-6 col-lg-6 col-xl-6 d-flex">
                    <div class="main-beauty">
                        <div class="con-beauty">
                            <h4>Beautify Your Space</h4>
                            <p>Do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.</p>
                            <button class="btn rounded-pill">Learn more</button>
                        </div>
                    </div>
                </div>
                <div class="col-sm-6 col-md-6 col-lg-6 col-xl-6">
                    <div class="parent-beauty">
                        <div class="girl-img">
                            <img src="image/pic1.png" alt="">
                        </div>
                        <div class="circle"></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- browser the range -->
    <div class="browser">
        <div class="container">
            <div class="row">
                <h4>Browse The Range</h4>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
        </div>
    </div>
    <!-- broswer images -->
    <div class="browser-parent">
        <div class="container">
            <div class="row">
                <div class="col-sm-12 col-md-4 col-lg-4">
                    <div class="browse-pic">
                        <img src="image\Mask Group.png" alt="">
                    </div>
                    <div>
                        <h5 class="text-center">Dining</h5>
                    </div>
                </div>
                <div class="col-sm-12 col-md-4 col-lg-4">
                    <div class="browse-pic">
                        <img src="image\Image-living room.png" alt="">
                    </div>
                    <div>
                        <h5 class="text-center">Living</h5>
                    </div>
                </div>
                <div class="col-sm-12 col-md-4 col-lg-4">
                    <div class="browse-pic">
                        <img src="image\image 101.png" alt="">
                    </div>
                    <div>
                        <h5 class="text-center">Bedroom</h5>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- how-its work heading website -->
    <div class="work-head">
        <div class="container">
            <div class="row">
                <h4>How It Works</h4>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
        </div>
    </div>
    <!-- how-its-work website three photo -->
    <div class="work-main">
        <div class="container">
            <div class="row">
                <div class="col-sm-12 col-md-4 col-lg-4 col-xl-4">
                    <div class="con-work">
                        <img src="image\Purchase Securely.png" alt="">
                        <div class="title">
                            <h3>Purchase Securely</h3>
                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-12 col-md-4 col-lg-4 col-xl-4">
                    <div class="con-work">
                        <img src="image\Ships From Warehouse.png" alt="">
                        <div class="title">
                            <h3>Ships From Warehouse</h3>
                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-12 col-md-4 col-lg-4 col-xl-4">
                    <div class="con-work">
                        <img src="image\Style Your Room.png" alt="">
                        <div class="title">
                            <h3>Style Your Room</h3>
                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- footer-join-mailingtask -->
    <div class="parent-mailing">
        <div class="container">
            <div class="row">
                <div class="col-sm-12 col-md-12 col-lg-12">
                    <div class="child-mailing">
                        <div>
                            <h5>Join Our Mailing List</h5>
                            <p>Sign up to receive inspiration, product updates,</p>
                            <p>and special offers from our team.</p>
                        </div>
                        <div>
                            <form action="" class="signup">
                                <input type="text" placeholder="example@gmail.com">
                                <button type="submit">submit</button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="footer-furniture">
        <div class="container">
            <div class="row">
                <div class="col-md-4 col-lg-4 col-xl-4 col-sm-12">
                    <div class="footer-text">
                        <h5>Beauty Care</h5>
                        <p>Do eiusmod tempor incididunt ut labore et dolore magna aliqua.Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.</p>
                        <h5>Follow Us</h5>
                    </div>
                </div>
                <div class="col-md-8 col-lg-8 col-sm-12">
                    <div class="three-img-footer">
                        <div>
                            <h5>Instagram Shop</h5>
                        </div>
                        <div class="ig_imges">
                            <div class="row">
                                <div class="col-md-3 col-sm-3">
                                    <img src="image\IG-1.jpg" alt="">
                                </div>
                                <div class="col-md-3 col-sm-3">
                                    <img src="image\IG-2.jpg" alt="">
                                </div>
                                <div class="col-md-3 col-sm-3">
                                    <img src="image\IG-3.jpg" alt="">
                                </div>
                                <div class="col-md-3 col-sm-3">
                                    <img src="image\IG-4.jpg" alt="">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- bootstrap-js -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</body>

</html>
                   

                  
 
          
      


   
    
      
