# 더 나은 웹

## 웹은 혼자 돌아다니기엔 위험합니다.

웹은 제멋대로 입니다. 당신의 동의 없이 당신의 개인 정보를 수집하고 활동을 감시합니다. (특히 구글, 페이스북 같은 IT 공룡들이요!)

때로는 수집한 개인 정보들이 유출되기도 합니다.


-   [나는 상품 입니다](나는_상품_입니다.md)

-   [우리는 감시 당하고 있습니다](인터넷에서_개인_정보를_스스로_지키세요.md)

---

## 어떻게 웹에서 나의 사생활을 "최대한" 지킬수 있을까요?

### 정부와 기업 혹은 개인 에게서 개인 정보 보호하기

-   소셜 미디어를 되도록이면 자제하세요 (사용을 안하는게 제일 좋습니다)
    -   꼭 사용해야 한다면 항상 누군가가 보고있음을 명심하세요
        -   다른 사용자에게서 나의 정보를 지키세요 (단, 여전히 기업들은 당신의 정보를 보고있습니다)
            -   페이스북 설정으로 개인 정보를 보호하기 (업데이트 예정)
            -   인스타그램 설정으로 개인 정보를 보호하기 (업데이트 예정)
            -   트위터 설정으로 개인 정보를 보호하기 (업데이트 예정)
    -   꼭 필요한 개인 정보만을 입력하세요
        -   이름외에 더 적어야 하나요? 안써도 그만인 것들은 적지 마세요.
    -   페이스북이 판매하는 상품은 우리 입니다.
        -   페이스북이 스마트폰의 마이크를 통해 사용자의 대화를 엿듣고 있습니다.
            -   [Facebook Paid Contractors to Transcribe Users' Audio Chats](https://www.bloomberg.com/news/articles/2019-08-13/facebook-paid-hundreds-of-contractors-to-transcribe-users-audio)
            -   [Facebook Just Gave 1.3 Billion Messenger Users A Reason To Delete Their Accounts](https://www.forbes.com/sites/kateoflahertyuk/2019/08/14/did-facebook-just-give-13-billion-users-a-reason-to-delete-their-account)
            -   [Yes, You Should Delete Facebook](https://medium.com/s/story/yes-you-should-delete-facebook-heres-why-bc623a3b4625)
        -   페이스북이 Messenger, whatsapp, Instagram, Oculus 를 소유중인 사실을 알고 있나요?
-   [링크드인에서 나의 개인 정보를 보호하세요(영문)](https://betterweb.qwant.com/how-to-protect-your-privacy-on-linkedin/)
-   [Window PC, MAC OS, Android, iOS 의 설정을 통해 사생활을 보호하세요(영문)](https://spreadprivacy.com/device-privacy-protection/)

### 향상된 방법

-   Windows와 Mac OS를 사용하지 마세요! 제일 좋은 방법은 Linux 를 사용하는 것입니다
    -   Windows는 사용자의 데이터를 미친듯이 수집합니다. 수집된 데이터는 기업과 정부에 제공될 가능성이 있습니다.
    -   Mac OS는 개인 정보 보호 정책에서 Windows보다 나을 수 있지만, Safari, Siri 등을 통해 사용자의 데이터를 수집합니다.
    -   Fedora와 Ubuntu 는 가장 유명한 Linux 배포판중 하나입니다.
    -   [Qubes OS](https://www.qubes-os.org/)는 프리즘 폭로 사건의 폭로자 에드워드 스노든이 사용하고 있는걸로 알려진 Linux의 배포판입니다.
    -   [elementary OS](https://elementary.io/)는 Ubuntu 기반으로 만들어진 Linux 배포판의 한 종류로, Window와 Mac의 대안 OS로 각광받고 있습니다.
-   비밀번호를 사이트마다 다르게 설정하세요. 아무리 당신이 개인 정보를 철저하게 관리해도, 개인 정보를 가지고 있는 기업(서비스, 앱)에서 개인 정보가 유출된다면 아무런 소용이 없습니다.
    -   쉬운 관리를 위해 패스워드 관리 툴을 사용하세요
        -   LastPass
        -   1Password
        -   Dashlane
        -   Bitwarden
        -   Keeper
-   사생활 보호 친화적인 브라우저를 사용하세요 (IE, Chrome 을 사용하지 마세요)
    -   Desktop
        -   [Firefox](https://firefox.com/) (recommend)
            -   Tor Browser가 이 브라우저를 기반으로 만들어집니다.
            -   Firefox의 [about:config에서 개인 정보와 관련된 설정을 변경](https://www.privacytools.io/browsers/#about_config)하세요
                -   소개된 설정중 일부는 고민해 봐야됩니다.
                    -   network.http.referer.XOriginPolicy
                        -   우리는 이 설정을 1로 권장하고있습니다.
                    -   network.http.referer.XOriginTrimmingPolicy
                        -   우리는 이 설정을 0으로 권장하고있습니다.
                    -   browser.sessionstore.max_tabs_undo
                        -   우리는 이 설정을 10으로 권장하고있습니다.
                -   browser.search.region 을 US 로 변경하세요
        -   [Brave](https://brave.com/) (recommend)
            -   Tor network 사용모드가 내장되어 있습니다.
        -   [Tor Browser](https://www.torproject.org/) (Tor network 사용)
    -   Mobile
        -   [Duckduckgo](https://duckduckgo.com/app) (recommend)
        -   Brave (recommend)
        -   Firefox (recommend)
            -   Firefox focus (recommend)
        -   Bromite (Android)
        -   snowhaze (iOS)
        -   [Tor Browser](https://guardianproject.info/fdroid/) (Android) (Tor network 사용)
        -   [Onion Browser](https://onionbrowser.com/) (iOS) (Tor network 사용)
    -   브라우저 애드온
        -   uBlock Origin (recommend)
            -   uBlock Origin (광고차단, 추적기 차단) + Privacy Badger (쿠키 차단 및 관리) + HTTPS Everywhere (HTTP요청을 HTTPS로 변경) 조합은 훌륭합니다.
        -   HTTPS Everywhere (recommend)
        -   Privacy Badger (recommend)
        -   Decentraleyes (recommend)
        -   Cookie AutoDelete
        -   Snowflake
            -   검열되는 국가들의 인터넷 사용자를 위해 당신이 브라우저로 Snowflake Proxy가 되어주세요
    -   자세히 알아 보고 싶다면 [사생활 보호에 친화적인 브라우저는 무엇이 있을까요? (준비중)](./articles/test.md) 를 확인해보세요
-   사생활 보호 친화적인 검색엔진을 사용하세요
    -   [Startpage](https://www.startpage.com/)
        -   에드워드 스노든이 추천한 검색엔진 입니다
    -   [Duckduckgo](https://duckduckgo.com/)
        -   `주의` 검색 개선의 목적으로 검색어를 익명으로 수집합니다.
    -   [Qwant](https://www.qwant.com/)
    -   [searx](https://searx.me/)
-   [구글에서 벗어나세요](https://spreadprivacy.com/how-to-remove-google/)
    -   당신의 메일을 구글이 읽고 있습니다.
    -   당신의 사진을 구글이 보고 있습니다.
        -   당신의 사진에 있는 사람들을 구글은 알고 있습니다.
    -   당신의 연락처를 구글이 알고 있습니다.
    -   당신의 위치를 구글이 알고 있습니다.
    -   [필터버블을 경계](https://spreadprivacy.com/google-filter-bubble-study/)하세요.
    -   크롬의 시크릿탭은 사용자를 온전히 [지켜주지 않습니다](https://spreadprivacy.com/is-private-browsing-really-private/).
-   불가능에 가깝겠지만, 카카오톡을 사용하지 마세요, 사용하더라도 비밀 채팅을 이용하세요
    -   대안으로 사용할 수 있는 메신저는 다음과 같습니다.
        -   Signal
        -   Telegram

### 기술을 이용해서 개인 정보 보호하기

-   VPN을 사용하고, 더 나아가 Tor 를 사용하세요
-   DNS를 [1.1.1.1](https://1.1.1.1/)로 바꾸세요. 혹은 유료 DNS를 사용하세요 (8.8.8.8을 사용하지 마세요)

## 더 알아보기

-   [사생활 보호에 친화적인 브라우저는 무엇이 있을까요? (준비중)](./articles/browsers.md)
