=== TossPay ===
Contributors: TossPay
Donate link: http://toss.im/pay/
Tags: toss, pay, toss pay, tosspay, woocommerce, payment, gateway, 토스, 토스페이, 토스 페이
Requires at least: 4.2.4
Tested up to: 4.2.4
Stable tag: 4.2.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Woo Commerce에 기반한 TossPay 결제 플러그인

== Description ==

Toss App을 통한 TossPay 결제 플러그인입니다.
Woo Commerce 기반으로 구축한 쇼핑몰에 설치 가능합니다.

= TossPay 홈페이지 =
https://toss.im/pay/

[youtube http://www.youtube.com/watch?v=84pAmXNYZw4]

= TossPay만의 특별함 =
* 고객님은 ActiveX 설치가 필요 없습니다.
* 고객님은 결제가 쉽습니다. Toss App을 통해 비밀번호 입력만으로도 결제가 가능합니다.
* 가맹점은 수수료가 훨씬 저렴하고 가입비도 없습니다.
* 가맹점은 오늘 판매하면 내일 바로 정산을 받을 수 있습니다.

= 지원 기능 =
* Toss 앱을 통한 결제 지원(계좌기반결제)
* 관리자 페이지에서 TossPay를 통한 자동 환불 기능
* TossPay 관리 사이트와의 연동
* TossPay 서버와의 연동을 통한 주문 상태 확인

> * TossPay 관리 사이트(https://toss.im/tosspay)를 통해 등록한 후 정상적으로 사용하실 수 있습니다.
> * Woo Commerce 플러그인을 설치한 쇼핑몰에서만 동작됩니다.

This plugin will work with the Toss App payment.
Toss App is based on a bank account transfer.

= Supported Features =

*   Payment with TossPay - Toss App.
*   Automatic Refund.
*   Work with the TossPay Admin page.
*   Callback from TossPay Server. It will change order status.

== Installation ==

= 설치방법 =
1. 다운받은 TossPay 플러그인을 `/wp-content/plugins/` 경로에 업로드합니다.
2. 워드프레스 관리자 화면의 '플러그인' 메뉴에서 TossPay를 활성화합니다.
3. 워드프레스 관리자 화면의 '우커머스 - 설정 - 결제' 메뉴에서 'TossPay'를 선택합니다.
4. 'TossPay를 활성화'에 체크를 합니다.
5. TossPay 관리 사이트에 등록하고 API Key를 발급받습니다.(반드시 TossPay 관리 사이트(https://toss.im/tosspay)에서 등록을 해야 합니다.
6. 발급받은 API Key를 입력하고 변경사항을 저장합니다.
7. TossPay를 사용할 준비가 완료 되었습니다.

== Screenshots ==

1. TossPay로 결제하기 / Payment with TossPay.
2. TossPay 관리자 화면 / Admin - Settings.
3. TossPay로 자동 환불하기 / Admin - Refunds.

== Changelog ==

= 0.1 =
* Initial Version.

= 0.2 =
* Remove add_order_note - Result json string.

= 0.2.1 =
* Update JSON type api compatibility.
