# Privacy Policy

## 1. YTME - Youtube Theater Mode Expander: https://github.com/keisokoo/ytme

- All data are stored offline in your browser.
- No data are transmitted to anywhere, ever.

My browser extensions do not collect personal information, do not collect your browsing history, and do not track your browsing activity. They do not collect data of any sort, and they do not inject ads.

### Cookies
No access any cookies.

### Tab Access
YTME는 사용자의 편의성을 위해 현재 이용중인 브라우저 탭을 읽습니다.

YTME의 아이콘을 클릭했을 때,
youtube페이지가 아니라면 이동하게 하거나,
theater모드가 활성화 되었을때는 기능메뉴를 호출하도록 합니다.

적절한 페이지에 메시지를 보내기 위해 tab의 이용권한이 필요합니다.

YTME reads the current browser tabs in use for user convenience.

When you click on the YTME icon,
if it's not on a YouTube page, it will navigate there or,
if theater mode is activated, it will bring up the functionality menu.

Access to the tabs is required to send messages to the appropriate pages.


### Storage
YTME는 chrome의 storage를 사용합니다.

YTME 사용자 설정은 옵션페이지에서 확인할 수 있으며, 세부 기능을 끄거나, 특정 스타일을 적용하거나,
단축키를 사용할지 하지 않을지에 대한 값을 사용자가 지정할 수 있습니다.

YTME uses Chrome's storage.

User settings for YTME can be checked on the options page, and users can turn off specific features,
apply certain styles, or decide whether or not to use shortcuts.

### Website Access
YTME는 다음에 액세스 할 수 있습니다.
- www.youtube.com

YTME는 유튜브에 접근할때 컨텐츠 스크립트 및 스타일시트를 삽입합니다.
이를 위해 현재 URL이 유튜브일때만 동작할 필요가 있습니다.
YTME에 삽입된 코드는 현재 유튜브 영상이 극장모드인지 또는 메인화면에 있는지를 체크합니다.
그리고 이 프로그램에 사용되는 옵션값은 사용자의 브라우저 로컬저장소에 저장됩니다.
이 프로그램은 어떤 데이터도 수집하지 않습니다.
YTME has access to 

- www.youtube.com.

YTME inserts content scripts and stylesheets when accessing YouTube. For this, it needs to work only when the current URL is YouTube. The code inserted in YTME checks whether the current YouTube video is in theater mode or on the main page. And the option values used in this program are saved in the local storage of the user's browser. This program does not collect any data.

### Permissions
The extension [manifest](https://github.com/keisokoo/ytme/blob/master/public/manifest.json) has the following permissions listed

Website Access : for content_scripts 
* `*://www.youtube.com/*`
