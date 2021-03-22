# HoneyPlate 

* 맛집 검색 및 예약 사이트

* 2021.02.25 ~ 2021.03.11

  

## Team Busy Bees 

* 강송이

* 강유정

* 김자경 (팀장)

* 박소연

* 이수연

  

## 사용 기술 

* Front End

  - JSP
  - CSS
  - JavaScript
  - Jquery

* Back End

  - Java
  - WAS(Web Application Server) Apache Tomcat 8.5
  - Oracle 11g XE

* IDE / Editor

  - Eclipse
  - SQL Developer
  - Visual Studio Code

* SDK

  * Firebase

* Library 

  * GSON
  * jQuery
  * Bootstrap
  * jQCloud
  * Cripto-js

* API

  * I'mport

  * Google Maps

    

  ## 팀원별 구현 코드

  ### 강유정

  * 예약

    * FrontEnd 

      * [reservationRequest.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/reservation/reservationRequest.jsp)

    * BackEnd 

      * Model

         * [Reservation.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/reservation/model/vo/Reservation.java)

         * [MyReservation.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/reservation/model/vo/MyReservation.java)

         * [ReservationService.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/reservation/model/service/ReservationService.java)

         * [ReservationDAO.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/reservation/model/dao/ReservationDAO.java)

      + Controller
         + [ReservationListViewCustomerServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/reservation/controller/ReservationListViewCustomerServlet.java)

         + [ReservationListViewOwnerServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/reservation/controller/ReservationListViewOwnerServlet.java)

         + [ReservationListViewDetailsForOwnerServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/reservation/controller/ReservationListViewDetailsForOwnerServlet.java)

         + [ReservationRequestServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/reservation/controller/ReservationRequestServlet.java)

         + [ReservationStatusRequestServlat.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/reservation/controller/ReservationStatusRequestServlat.java)

  * 회원 관리 (로그인, 회원가입, 마이페이지)

    * FrontEnd

      * [myPageOwner.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/member/myPageOwner.jsp)

      * [myPageCustomer.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/member/myPageCustomer.jsp)

      * [checkEmailPopup.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/member/checkEmailPopup.jsp)

      * [memberEnroll.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/member/memberEnroll.jsp)

        

    * BackEnd

      * Model

        * [Member.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/model/vo/Member.java)

        * [MemberService.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/model/service/MemberService.java)

        * [MemberDAO.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/model/dao/MemberDAO.java)

      * Controller

        * [MemberMyPageOwnerServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberMyPageOwnerServlet.java)

        * [MemberMyPageCustomerServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberMyPageCustomerServlet.java)

        * [MemberMyPageBookmarkListServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberMyPageBookmarkListServlet.java)

        * [MyPageBookmarkRemoveServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberMyPageBookmarkRemoveServlet.java)

        * [MemberMyPageReviewServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberMyPageReviewServlet.java)

        * [MemberMyReviewDeleteServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberMyReviewDeleteServlet.java)

        * [MemberUpdateInformationServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberUpdateInformationServlet.java)

        * [MemberUpdatePasswordServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberUpdatePasswordServlet.java)

        * [MemberGetBoardNoServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberGetBoardNoServlet.java)

        * [MemberEnrollServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberEnrollServlet.java)

        * [MemberDuplicationIdCheckServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberDuplicationIdCheckServlet.java)

        * [MemberDuplicationEmailCheckServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberDuplicationEmailCheckServlet.java)

        * [MemberEnrollCheckEmailPopupServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberEnrollCheckEmailPopupServlet.java)

        * [MemberLoginServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberLoginServlet.java)

        * [MemberLogoutServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberLogoutServlet.java)

  * 북마크 

    * BackEnd

      * Model 

        * [Bookmark.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/store/model/vo/Bookmark.java)

        * [MyBookmark.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/store/model/vo/MyBookmark.java)

        * [BookmarkService.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/store/model/service/BookmarkService.java)

        * [BookmarkDAO.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/store/model/dao/BookmarkDAO.java)

      * Controller

        * [StoreBookmarkAddServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/store/controller/StoreBookmarkAddServlet.java)

        * [StoreBookmarkRemoveServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/store/controller/StoreBookmarkRemoveServlet.java)

  * 가게 정보 수정

    * FrontEnd

      * [storeviewUpdate.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/store/storeviewUpdate.jsp)

    * BackEnd

      * Controller

        * [storeviewUpdateServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/store/controller/StoreviewUpdateServlet.java)

  * common

    * FrontEnd

      * [error.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/common/error.jsp)

    * BackEnd

      * [JDBCTemplate.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/common/JDBCTemplate.java)

      * [MemberRoleFilter.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/common/filter/MemberRoleFilter.java)

      * [LoginFilter.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/common/filter/LoginFilter.java)

      																																							

  ### 강송이

  * 메인 화면

    * FrontEnd

      * [main.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/search/main.jsp)

    * BackEnd

      * Model

        * [Hashtag.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/search/model/vo/Hashtag.java)

        * [HashtagRankList.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/search/model/vo/HashtagRankList.java)

        * [NewList.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/search/model/vo/NewList.java)

        * [RatingList.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/search/model/vo/RatingList.java)

        * [ReservationRankList.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/search/model/vo/ReservationRankList.java)

        * [ReviewList.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/search/model/vo/ReviewList.java)

        * [ViewList.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/search/model/vo/ViewList.java)

      * Controller

        * [MainListServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/search/controller/MainListServlet.java)

        

  * 검색 

    * FrontEnd

      * [searchResult.jsp ](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/search/searchResult.jsp)

    * BackEnd

      * Model

        * [SearchTable.java ](https://github.com/kyj0101/HoneyPlate/blob/master/src/search/model/vo/SearchTable.java)

        * [SearchService.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/search/model/service/SearchService.java)

        * [SearchDao.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/search/model/dao/SearchDao.java)

          

      * Controller

        * [SearchResultviewServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/search/controller/SearchResultviewServlet.java)

  ### 김자경 

  + landingHeader

    + FrontEnd

      + [main.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/search/main.jsp)

  + 사업자 예약 처리

    + FrontEnd

      + [myPageOwner.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/member/myPageOwner.jsp)

    + BackEnd

      + Controller

        + [ReservationStatusNoshowServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/reservation/controller/ReservationStatusNoshowServlet.java)

        + [ReservationStatusRequestRefusalServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/reservation/controller/ReservationStatusRequestRefusalServlet.java)

        + [ReservationStatusVisitedServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/reservation/controller/ReservationStatusVisitedServlet.java)

  + 결제

    + FrontEnd

      + [myPageCustomer.jsp ](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/member/myPageCustomer.jsp)

    + BackEnd

      + Model

        + [Payment.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/payment/model/vo/Payment.java)

        + [PaymentService.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/payment/model/service/PaymentService.java)

        + [PaymentDAO.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/payment/model/dao/PaymentDAO.java)

      + Controller

        + [PaymentDataInsertServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/payment/controller/PaymentDataInsertServlet.java)

  + common

    + FrontEnd

      + [header.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/common/header.jsp)

      + [footer.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/common/footer.jsp)

  ### 박소연 

  + 가게 페이지 

    + FrontEnd

      + [storeview.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/store/storeview.jsp)

    + BackEnd

      + Model

        + [Store.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/store/model/vo/Store.java)

        + [StoreService.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/store/model/service/StoreService.java)

        + [StoreDAO.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/store/model/dao/StoreDAO.java)

      + Controller

        + [StoreInfoServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/store/controller/StoreInfoServlet.java)


  + 리뷰 작성 

    + FrontEnd

      + [review.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/store/review.jsp)

    + BackEnd

      + Model

        + [Review.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/store/model/vo/Review.java)

      + Controller

        + [ReviewInsertServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/store/controller/ReviewInsertServlet.java)

        + [ReviewDeletServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/store/controller/ReviewDeletServlet.java)

  + common

    + BackEnd

      + [MvcFileRenamePolicy.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/common/MvcFileRenamePolicy.java)

        

  ### 이수연 
  + 회원가입
    + FrontEnd
      + [memberEnroll.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/member/memberEnroll.jsp)  

  + 로그인

    + FrontEnd

      + [login.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/member/login.jsp)

  + 아이디 찾기

    + FrontEnd

      + [find_id.jsp](https://github.com/kyj0101/HoneyPlate/blob/master/WebContent/WEB-INF/view/member/find_id.jsp)

    + BackEnd

      + Controller

        + [MemberFindIdServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberFindIdServlet.java)

  + 회원탈퇴

    + BackEnd

      + Controller

        + [MemberDeleteOwnerServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberDeleteOwnerServlet.java)

        + [MemberDeleteCustomerServlet.java](https://github.com/kyj0101/HoneyPlate/blob/master/src/member/controller/MemberDeleteCustomerServlet.java)



---------------------------

아래 노션 링크를 클릭하시면 더 자세한 정보를 보실 수 있습니다.

[노션](https://www.notion.so/08ee15bd7b9140eba8aad4a0f8ea8729)

