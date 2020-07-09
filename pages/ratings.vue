<template>
    <div>
    <div class="page-overlay position-fixed w-100 h-100"></div>
    <div class="popup popup-promotional">
        <div class="card">
            <div class="card-body">
                <div class="row">
                    <div class="col-12 text-center">
                        <img src="images/icons/offers.svg" alt="">
                    </div>
                    <div class="col-12 mt-3">
                        <button class="btn btn-block btn-primary btn-ok-offers">OK, I Want To Receive Offers &
                            Promotions</button>
                        <button class="btn btn-block btn-outline-primary mt-3 btn-no-offers">No Thanks, I Would Like To
                            Miss Out</button>
                    </div>
                </div>

            </div>
        </div>
    </div>
    <div class="container-fluid mb-5">
        <div class="row device-frame">
            <img src="images/print-frame.svg" alt="">
        </div>
        <div class="row pl-2 pl-md-5 pr-md-5 pr-2">
            <div class="col-12">
                <div class="card page-frame card-thankyou">
                    <div class="mainWrap">
                        <div class="fadeContent transition">
                            <div class="card-header">
                                <div class="row">
                                    <div class="col-12 mt-2 text-center">
                                        <h2 class="pb-2">Sandwizza</h2>
                                        <p class="shop-add pb-1">Shop No. 15 , Lake Primerose, Lower ground
                                            Mumbai,Maharashtra-400076</p>
                                        <div class="row">
                                            <div class="col-6 border-right text-right">
                                                <p><img src="images/icons/calendar.svg" alt="" class="icon-main mr-1">
                                                    01-01-2021</p>
                                            </div>
                                            <div class="col-6 text-left">
                                                <p><img src="images/icons/clock.svg" alt="" class="icon-main mr-1">
                                                    21:02:01.0</p>
                                            </div>
                                        </div>
                                        <h3 class="mt-3 mb-2 thanks-msg  text-green"><i class="medium-font">Thank You
                                                For
                                                The Payment</i></h3>
                                    </div>
                                </div>
                            </div>
                            <div class="scrollDiv">
                                <div class="card-body">
                                    <div class="row">
                                        <div class="col-12 first-details rating-details" style="display: none;">
                                            <div class="rating-main">
                                                <div class="col-12 pl-4 pr-4 text-center">
                                                    <img src="images/rating/main.svg" alt="">
                                                </div>
                                            </div>
                                            <div
                                                class="rating-conatiner d-flex justify-content-center ml-5 mr-5 mt-2 mb-2">
                                                <div class="rating-item rating-item-first">
                                                    <img src="images/rating/star.svg" alt="" class="rating-img">
                                                </div>
                                                <div class="rating-item rating-item-second">
                                                    <img src="images/rating/star.svg" alt="" class="rating-img">
                                                </div>
                                                <div class="rating-item rating-item-third">
                                                    <img src="images/rating/star.svg" alt="" class="rating-img">
                                                </div>
                                                <div class="rating-item rating-item-fourth">
                                                    <img src="images/rating/star.svg" alt="" class="rating-img">
                                                </div>
                                                <div class="rating-item rating-item-fifth">
                                                    <img src="images/rating/star.svg" alt="" class="rating-img">
                                                </div>
                                            </div>
                                            <div class="col-12 text-center">
                                                <h4 class="medium-font">Your ratings matter to us...</h4>
                                            </div>
                                        </div>
                                        <div class="col-12 second-details services-details" style="display: none;">
                                            <div class="row">
                                                <div class="col-12 text-center">
                                                    <h4 class="medium-font mt-2 mb-3">...As You Keep Us Going</h4>
                                                </div>
                                            </div>
                                            <form id="services-form" class="custom-form pl-3 pr-3">
                                                <div class="row">
                                                    <div class="col-12">
                                                        <div class="form-group">
                                                            <textarea class="form-control" name="service-comments"
                                                                id="service-comments"
                                                                placeholder="We would love to hear from you as your words mean the world to us"
                                                                rows="5"></textarea>
                                                        </div>
                                                    </div>
                                                    <div class="col-12">
                                                        <div class="form-group">
                                                            <!-- <button type="submit" class="btn btn-primary btn-block" disabled>Submit</button> -->
                                                            <button type="button"
                                                                class="btn btn-primary btn-block btn-submit">Submit</button>
                                                        </div>
                                                    </div>
                                                    <div class="col-12">
                                                        <label class="custom-component-container anonymous-check">I
                                                            choose
                                                            to be
                                                            anonymous <input type="checkbox" name="anonymous"
                                                                value="anonymous"><span class="checkmark"></span>
                                                        </label>
                                                    </div>
                                                </div>
                                            </form>
                                        </div>
                                        <div class="col-12 third-details paymnet-details ">
                                            <div class="total-amt bg-green">
                                                <div class="row align-items-center">
                                                    <div class="col-6">
                                                        <p class="total-amt-paid">Total Amount Paid</p>
                                                        <p class="amt-paid" style="display: none;">Total Amount</p>
                                                    </div>
                                                    <div class="col-6 pl-0 text-right">
                                                        <h2><span class="amt-symbol">&#8377;</span>2000<span
                                                                class="amt-sub">.00</span></h2>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="amt-first-details">
                                                <div class="row align-items-center">
                                                    <div class="col-6">
                                                        <p class="text-light-gray">Card Number</p>
                                                    </div>
                                                    <div class="col-6 pl-0 text-right">
                                                        <p class="text-gray">1234XXXXXXXX1234</p>
                                                    </div>
                                                </div>
                                                <div class="row align-items-center">
                                                    <div class="col-6">
                                                        <p class="text-light-gray">Transaction Mode</p>
                                                    </div>
                                                    <div class="col-6 pl-0 text-right">
                                                        <p class="text-gray">Chip</p>
                                                    </div>
                                                </div>
                                                <div class="row align-items-center">
                                                    <div class="col-6">
                                                        <p class="text-light-gray">Card Type</p>
                                                    </div>
                                                    <div class="col-6 pl-0 text-right">
                                                        <p class="text-gray"><img src="images/icons/visa.svg" alt=""
                                                                class="img-visa"></p>
                                                    </div>
                                                </div>
                                                <div class="row align-items-center">
                                                    <div class="col-6">
                                                        <p class="text-light-gray">Application Label</p>
                                                    </div>
                                                    <div class="col-6 pl-0 text-right">
                                                        <p class="text-gray">123123456456789798912</p>
                                                    </div>
                                                </div>
                                                <div class="row align-items-center">
                                                    <div class="col-6">
                                                        <p class="text-light-gray">Transaction Type</p>
                                                    </div>
                                                    <div class="col-6 text-right">
                                                        <p class="text-gray">Sale</p>
                                                    </div>
                                                </div>
                                                <div class="row align-items-center">
                                                    <div class="col-6">
                                                        <p class="text-light-gray">Status</p>
                                                    </div>
                                                    <div class="col-6 text-right">
                                                        <p class="text-gray">Approved</p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="amt-second-details">
                                                <div class="row align-items-center">
                                                    <div class="col-6">
                                                        <p class="text-light-gray">Invoice Number</p>
                                                    </div>
                                                    <div class="col-6 text-right">
                                                        <p class="text-gray">56449875</p>
                                                    </div>
                                                </div>
                                                <div class="row align-items-center">
                                                    <div class="col-6">
                                                        <p class="text-light-gray">MID</p>
                                                    </div>
                                                    <div class="col-6 text-right">
                                                        <p class="text-gray">123344631</p>
                                                    </div>
                                                </div>
                                                <div class="row align-items-center">
                                                    <div class="col-6">
                                                        <p class="text-light-gray">TID</p>
                                                    </div>
                                                    <div class="col-6 text-right">
                                                        <p class="text-gray">32564895</p>
                                                    </div>
                                                </div>
                                                <div class="row align-items-center">
                                                    <div class="col-6">
                                                        <p class="text-light-gray">RRN</p>
                                                    </div>
                                                    <div class="col-6 text-right">
                                                        <p class="text-gray">2356464978852</p>
                                                    </div>
                                                </div>
                                                <div class="row align-items-center">
                                                    <div class="col-6">
                                                        <p class="text-light-gray">Batch Number</p>
                                                    </div>
                                                    <div class="col-6 text-right">
                                                        <p class="text-gray">236548</p>
                                                    </div>
                                                </div>
                                                <div class="row align-items-center">
                                                    <div class="col-6">
                                                        <p class="text-light-gray">Card Holder Name</p>
                                                    </div>
                                                    <div class="col-6 text-right">
                                                        <p class="text-gray">Karan Mistry</p>
                                                    </div>
                                                </div>
                                                <div class="row align-items-center">
                                                    <div class="col-6">
                                                        <p class="text-light-gray">Transaction ID</p>
                                                    </div>
                                                    <div class="col-6 text-right">
                                                        <p class="text-gray">12312314565236589452</p>
                                                    </div>
                                                </div>
                                                <div class="row align-items-center">
                                                    <div class="col-6">
                                                        <p class="text-light-gray">Expiry Date</p>
                                                    </div>
                                                    <div class="col-6 text-right">
                                                        <p class="text-gray">**/**</p>
                                                    </div>
                                                </div>
                                            </div>

                                        </div>
                                    </div>
                                </div>
                                <div class="card-footer">
                                    <div class="row">
                                        <div class="col-12 mt-3 mb-3 text-center">
                                            <button class="btn btn-outline-secondary btn-share">Share Via <img
                                                    src="images/icons/share.svg" alt=""></button>
                                        </div>
                                    </div>
                                    <div class="footer-first">
                                        <div class="row">
                                            <div class="col-12 text-center footer-details">
                                                <div class="bg-green">
                                                    <p class="d-flex align-items-center justify-content-center">Powered
                                                        By
                                                        <img src="images/logo-white.svg" alt=""></p>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="row">
                                            <div class="col-12 mt-3 mb-3 text-center">
                                                <label class="custom-component-container">I would love to receive offers
                                                    and
                                                    promotions <input type="checkbox" name="getOffer"
                                                        value="offer_promotions" class="getOffer" checked><span
                                                        class="checkmark"></span>
                                                </label>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="footer-second" style="display: none;">
                                        <div class="row">
                                            <div class="col-12 mt-2 mb-2 text-center">
                                                <img src="images/thank-you.svg" alt="" class="img-thankyou">
                                            </div>
                                        </div>
                                        <div class="row">
                                            <div class="col-12 mt-3 mb-3 text-center">
                                                <label class="custom-component-container">I would love to receive offers
                                                    and
                                                    promotions <input type="checkbox" name="getOfferThankyou"
                                                        value="offer_promotions_thankyou" class="getOfferThankyou"
                                                        checked><span class="checkmark"></span>
                                                </label>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    </div>
</template>