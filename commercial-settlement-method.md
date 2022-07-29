# 상거래 결제방식

## 부가가치통신망

부가가치통신망은 한국에게 만 있는 독특한 결제사업자이다. 영어로는 “value added network” 앞글자만으로 VAN사라고 부르기도 한다. 말 그대로 통신을 통해 가치를 만들어내는 사업자로서 가맹점의 카드결제정보를 카드회사에 제공하고 이에 대한 보상으로 수수료수익중 일부를 지급받는 사업자이다.&#x20;

국내 약 24개정도의 사업자가 있으며 대표적으로는 KICC, NICE, KSNET등이 있다. 부가가치통신사업자들은 신용카드가맹점을 유치하고 결제단말기를 설치하여 관리하는 업무를 담당하는데 결제단말기가 서비스하는 결제수단은 IC, MSR로 주로 신용카드의 결제만을 위한 결제단말기를 공급하고있다.&#x20;

따라서 마이페이먼트의 APP TO APP결제의 정보를 제공할 수 없는 과거형 사업자라고 할 수 있다.

![\[부가가치통신망의 결제 구조와 주요 사업자\]](.gitbook/assets/부가가치통신망\_20220624.png)

## 결제대행사

결제대행사는 온라인의 전자상거래의 결제를 대행하여주는 결제사업자이다. 영어로는 “payment gateway” 앞글자만으로 PG사라고 부르기도 한다. 말 그대로 결제할 수 있는 문을 열어주는 결제사업자로서 카드회사가 가맹을 맺기 어려운 통신 사업자를 대상으로 결제대행을 통해 결제서비스를 제공하는 사업자이다.&#x20;

국내 약 100여개 정도의 사업자가 있으며 대표적으로는 이니시스, LG유플러스, 올엣 등이 있다. 결제대행사는 온라인의 통신사업자에게 전자결제대행으로 결제서비스를 제공하는게 주업무 였지만 스마트폰이 보급 되면서 형성된 O2O시장의 오프라인에서도 다양하고 특화된 결제서비스를 제공하고 하면서 성장하고있는 중이다.&#x20;

현재의 신용카드결제시장에서 PG이 결제서비스는 대부분이 신용카드의 결제대행을 주 업무로 하고있으나, 신용카드가 아닌 플랫폼사들의 간편결제를 결제대행의 업무로 변화하고 있다.

![\[결제대행의현재 신용카드결제시장에서의 결제 구조와 주요 사업자\]](.gitbook/assets/결제대행서비스흐름도\_20220624.png)

## 플랫폼사의 APP TO APP결제

이처럼 VAN과 PG결제는 신용카드의 결제를 주 업무로 하여 오프라인에서는 CAT(신용응용단말기 : 신용 카드 가맹점에서 신용 카드 발급 회사의 주 컴퓨터에 온라인으로 접속하여 신용 카드 이용 한도액의 확인이나 카드의 사고·무효 여부 조회등에 사용하는 단말 장치. 신용 조회와 같은 기능을 갖는 단말기)과 온라인에서는 ISP(인터넷 안전결제 Internet Secure Payment : 카드 승인 시 사용하는 안전결제 서비스 인 시스템 프로그래밍 Image Signal Processing Independent Study Project)로 신용카드를 통한 결제를 위한 결제방식인것에 비해 플랫폼에서 제공하는 APP TO APP결제는 신용카드를 배제한 VANLESS방식의 결제수단이다.&#x20;

융합플랫폼이라 할 수 있는 스마트폰에서 플랫폼사가 제공하는 법적 화폐(포인트)를 이체하는 결제방식이며 대표적으로는 카카오페이, 네이버페이, 알리페이 등이 있다. 이를 플랫폼사들의 APP TO APP결제는 별도의 카드없이 사용중인 스마트폰을 이용하여 간편하게 결제할 수 있도록한다. 하여 간편결제라고 불리우기도 한다.&#x20;

결제매개체로는 NFC, MST, 비콘 등이 있지만 가장 보편화 되어있는게 QR스캔방식이다. QR스캔방식이 보편화 된 이유에는 스마트폰마다 카메라가 있으며 QR스캔방식은 별도의 특성을 가리지않는다는 장점이 있다.&#x20;

APP TO APP결제가 보편화되어 있는 중국의 경우에도 알리페이나 위쳇페이가 모두 QR스캔결제방식을 채택하고 있다.&#x20;

그러나 QR스캔방식은 QR코드의 위.변조로 인한 사건사고가 많이 일어나고 있으며 APP TO APP간편결제의 빠른 확산과 성공을 현재의 QR키트가 아닌 안드로이드기반의 결제단말기로의 1회성 QR코드발행 위해서는 안드로이드결제단말기와 블록체인의 보안기술을 도입해야 할 것이다.

![\[플랫폼사의 APP TO APP결제 결제흐름\]](.gitbook/assets/06.png)

## 블록체인기반의 가상자산 이체결제

플랫폼사가 제공하는 APP TO APP결제의 법적화폐(포인트)에는 가상자산도 해당될 수 있다. 가상자산을 가진 유저에게 법적화폐(포인트)로 전환하여 결제플랫폼을 제공한다면 APP TO APP결제로 구축되는 결제망은 가상자산의 상거래 생태계가 되는 것이다. 실제 블록체인기술 기반의 가상자산의 APP TO APP결제 서비스를 제공하고 있는 가상자산 플랫폼사업자들이 생겨나고 있다.&#x20;

대표적인 한국의 암호화폐거래소인 빗썸을 들 수 있다. 빗썸은 자체 거래소에서 P2P간 거래되는 거래금액을 빗썸캐쉬로 전환하게하여 가맹점에서 결제할 수 있는 서비스를 제공하고 있다. 즉 빗썸캐쉬는 카카오페이의 카카오머니와 같은 법적화폐(포인트)의 개념으로 이해된다.&#x20;

다만, 빗썸은 아직 제도권내에서 제도권내의 결제사업자로 인정하지 않고 결제가맹점을 확보하는데 어려움이 있다. 예를 들어 빗썸의 직영이 아닌 가맹점을 10곳 이상의 가맹하는게 불법인것이다. 이렇듯 블록체인의 뛰어난 기술에도 재도권의 법적제한으로 인해 블록체인의 상거래 결제망구축에는 많은 어려움이 존재하는게 현실이다.

따라서 대부분의 코인을 발행한 회사(재단)들은 상거래의 재화 결제를 개인간의 P2P방식으로 코인을 결제할 수 있도록 할 수밖에 없는 현실이다. 이는 크게 두가지의 문제가 발생한다.&#x20;

첫째로는 제화거래의 매출이 자동신고되는 현재의 상거래결제 시스템이 아니기 때문에 가맹점들이 자진신고를 해야 하지만 자진신고를 할 수 있는 시스템이 되어있지 않다. 따라서 세금신고 누락을 조장한다고 생각할 수 있기에 상거래결제에서 코인의 P2P 거래망이 구축되지 않고 있다.&#x20;

둘째로는 가맹점에서 시세가 변동하는 코인을 현금에 준하는 가치로 인정해야하며 코인을 거래소를 통해 현금화를 하는 과정에서도 코인 가격의 변동성으로 인해 가맹점에서 코인으로 결제를 받아준다는 것은 불가능 한 것이다.&#x20;

하지만 부정적이지만은 않다. 앞으로 에이원토스(AOT)코인(AOT)의 컨소시엄을 통해 위에서 나열한 VAN, PG, APP TO APP의 모든 결제를 제공 하는 결제시스템을 구축하여 현재의 상거래 결제사업자에게 제공하여 상거래의 APP TO APP결제망을 구축하고 있으며 에이원토스(AOT)(AOT)전자지갑에서 제공하는 가상자산의 법적화폐(포인트)전환의 플랫폼이 문제점을 모두 해결하였다.

![](.gitbook/assets/가상자산이체결제\_20220624.png)