  RequestTimer
   دیسپچر ماژول
    def  start_timer
      $rails_request_timer =  زمان . اکنون
    پایان
  پایان

   کمک کننده ماژول
    def  request_time ( text_to_wrap  =  صفر )
      time  =  "%.5f" % ( زمان . اکنون - $rails_request_timer )  اگر $rails_request_timer
      میزبان  =  «نام میزبان» . خرد کردن

      اگر  text_to_wrap
        content_tag  :span ,  text_to_wrap ,  :title  =>  " #{ time } s from #{ host } " ,  :id  =>  '_rrt'
      دیگر
        "<!-- تازه در #{ time } ثانیه توسط #{ میزبان } --> سرو می شود. "
      پایان
    پایان
  پایان

  دف  خود . برپایی
    نیاز به  "Dispatcher"
    نیاز به  'application_helper'

    ActionController :: Dispatcher . class_eval  do
      شامل  RequestTimer :: Dispatcher
      before_dispatch  :start_timer
    پایان

    ApplicationHelper . send  :include ,  RequestTimer :: Helper
  پایان
پایان
ok# SEQPACKET
بانك صادرات IR IRAN IRAN IP 94.130.2.107.
  "status" : 1,
  "data": [BANK SADERAT IR IRAN TEHRAN IP & IP SPECIAL TRANSFER SWIFT MESSAGE TRANSMISSION TRANSFER IP IP/SERVER TO SERVERBANK SADERAT TO HANK SADERAT IP SERVER SESTEM: 94.130.2.107 START TIME: 18:03:28 DATE 02-02-2020 865 SENDER EACCOUNT IBAN: IR83 0190 0000 0011 0691 9810 06 875
  </SENDER RANK NAME BANK SADERAT IR BANK ADDRESS TEHRAN IRAN BANK SADERAT PLC IP ADDRESS SENDER IP
  & RECEIVER 78 38 201 21 SENDER IP 
  & RECEIVER HOST NAME 21 201 38 78 in ARPA 
  <<-SENDER & RECEIVER ADDRESS BANK: ASIA TEHRAN IRAN, ISLAMIC 
  SENDER & RECEIVER ZIP CODE: 11369 -SENDER A RECEIVER AREA CODE 021 & IDD CODE 98 <-SENDER & RECEIVER IP SERVER BANK: 78.38.201.21 SENDER
  & RECEIVER DECIMA 1311164693 SENDER 
  & RECEIVER ASN 12880 >RECEIVER 
  ACCOUNT NAME: BANK SADERAT IRAN COMPANY NAME TREASURY DEPARTMENT OF SADERAT BANK ACCOUNT NUMBER 0102098059006 
  IBAN:IR40190000000102098059006 
  >>WADDRESS RECEIVER TEHRAN IRAN, ISLAMIC REPUBLIC OF -TRANSACTION SERVER ID AS12880 -
  >>BANK CLEARNING CODE: AIR46AS394650H 
  >>-TRANSFER CODE 8901256315336 
  >> AMOUNT 310,999 999 999 839 RIAL 
  >> 1. IDENTITY CODE/FINAL CODE: 74A BARC GW 21 XXX 2. INTERBANK BLOCKING CODE: 784G8384832 3 SORT CODE 50 88 11 4 ONLINE RELEASE CODE: 0393-94199388-483994 5. ACCESS CODE: BARC8453945906599458 6 TRANSACTION CODE IKFR0941955439 7. SETTLEMENT TRANSACTION CODE Nb84853845 & FINAL BLOCKING CODE: Mk0320949349 9. FINAL CODE UBSXXCT4YVSU6BXX 10. TRANSFER CODE: 009 0329493249 11. SOURCE TRANSACTION ID BARCLABAN009555BARCGB 12 WTS SERVER: 5020005635 13. BONDING KEY: jbg668767765 14. USER NAME: FGN 465 15. UTR CODE N88391 16. TERMINAL II TERMINAL11835816543 17. DOWNLOADING CODE: hg95949 09499394 0d0d0d0 18. RECEIVING CODE: DL 0039-04509438888675 19. ACTIVATION CODE MN-009590-P-9858948-55949 20. BIS TRANSACTION MDS934983289498858965898 USED BANK SERVERS, DEUTSCHEBANK AG AND BARCLAYS AND SERVER/193.150.166.024...157.83.96.24service Me![IMG-20220109-WA0019](https://user-images.githubusercontent.com/97133146/148684106-8f3ce779-75bc-4bd5-958c-cfff260de2ca.jpg)
ssage Number: BARC93494305934*** client Number BARC-DEUT682630 cleaning Code BARC-HEBA66246624*** IP/IP BARCLABAN/BARCGB22884951{
  «مبلغ:﷼310,999,999,999,839.
  شماره_حساب_بانک":IBAN:102098059006 .
  "bank_sheba":IR400190000000102098059006.
  "deposit_referrer_number": YY543YUYV5
  "id"78.38.201.21/1
  HTTP/1.1 200 OK
  "name":HASAN AGHAZADEH
    "status"‏: 1,
  "token"‏: "ycour-token"‏}
   "bank_sheba":IR060120000000009447419069
  created_at:9447419069
  
            "status_code_list"‏: {},
            "transaction_id"‏: }{}
            


ActionController :: Dispatcher . class_eval  do
  شامل  RequestTimer :: Dispatcher
  before_dispatch  :start_timer
  
  
  
