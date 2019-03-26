# 신규 사용자를 사로잡는 훅을 디자인하라!

## Hook
멋진 상품이나 서비스를 만들었는데 사람들이 관심을 가지지 않나요? 멋진 신규 사용자 경험을 디자인했는데도 여전히 전환율이 높지 않나요? 짧은 시간에 신규 사용자들의 관심을 사로잡아 우리 고객으로 전환할 수 있게 만드는 방법인 훅 (Hook)에 대해 알아봅시다.

## Intro
무료 온라인 서비스를 제공하거나 체험판을 통해 신규 사용자를 유료 고객으로 전환하고자 하는 스타트업은 신규 사용자들이 직접 서비스를 이용해 보도록 유도해야 합니다. 신규 사용자는 체험 과정을 통해 아하 모먼트를 경험하고 우리 고객이 될 수 있습니다. 하지만 우리 홈페이지를 방문한 신규 사용자 중 대다수는 우리 서비스를 써 보기도 전에 이탈합니다. 직접 서비스를 체험해봐야 아하 모먼트를 느껴서 우리 고객이 될텐데, 힐끗 눈길만 주고 그냥 떠나버립니다. 왜 그럴까요? 

스타트업 입장에서야 우리 서비스가 어두운 방에 갇혀있는 신규 사용자에게, 밝은 빛을 비추는 문을 열어 주는 것이라 생각하겠지만 신규 사용자 입장에서는 밝은 세상에서 잘 살고 있다가, 미지의 문을 열고 깜깜한 방으로 들어가는 것이라고 생각할 겁니다. 시간을 들여서 개인 정보를 주고 회원 가입을 한 후에 서비스를 체험해 봐야한다는 것은 참으로 수고스러운 일입니다. 신규 사용자는 우리 서비스가 그런 수고를 들일만한 가치가 있는 것인지를 스스로 납득해야 합니다. 바로 스타트업과 신규 사용자 간의 팽팽한 기싸움이 벌어지는 순간이라고 할 수 있습니다.

어떻게 하면 신규 사용자에게 우리 상품이 그런 수고를 들일만한 가치가 있다는 것을 납득하도록 만들 수 있을까요?

## 신규 사용자를 사로잡는 훅
신규 사용자가 광고나 입소문을 통해서, 또는 검색을 통해 우리 홈페이지를 방문했다고 생각해 봅시다. 회원가입 버튼을 눌러서 회원 가입하도록 어떻게 유도할 수 있을까요? 신규 사용자에게 우리 서비스의 매력을 어필해서 "어머, 이건 써야돼!"라는 생각이 들게 만드는 신규 사용자 경험을 바로 훅이라고 합니다. 신규 사용자가 서비스를 직접 체험해서 아하 모먼트를 경험하기 전에 미리 맛보기를 하도록 만드는 것입니다.

### 사례 연구, Gmail
잘 디자인된 훅의 사례를 하나 살펴봅시다. 제가 이메일 주소가 하나 필요하다고 가정해 봅시다. 지인이 저에게 Gmail이라는 서비스를 추천해줘서 Gmail을 구글에서 검색해 보려고 합니다.

먼저 검색창에 Gmail을 입력하고 Gmail 홈페이지로 이동합니다. 처음 저를 맞이하는 건 바로 키 메시지입니다. 'Gmail을 사용하면 더 많은 일을 마칠 수 있다'라고 합니다. 그리고 바로 계정을 만들라고, 즉 회원 가입을 유도합니다. 오른쪽 스크롤 버튼을 누르면 자동 완성 기능을 통해 더 빨리 이메일을 작성할 수 있다는 2번째 키 메시지가 나타납니다. 한번 더 스크롤을 하면 답장도 더 빨리 할 수 있다고 알려줍니다. 3개 화면 모두 "Create an account"라는 파란색 버튼이 달려 있어 원한다면 바로 회원 가입을 하고 서비스를 체험해 볼 수 있습니다. 하지만 저는 보수적이기 때문에 이런 감언이설에 넘어가지 않겠습니다.

3개의 키 메시지를 모두 본 다음, 화면 아래 쪽으로 내려가니 Gmail은 어떤 기기에서든 사용할 수 있다고 알려줍니다. 그리고 구글 플레이와 애플 앱스토어 다운로드 링크를 제공합니다. 이 링크를 통해 앱을 다운로드 받으면 회원가입을 하지 않고서는 더 이상 진행할 수 없는 앱내 NUX가 펼쳐질 겁니다.

아직 Gmail의 감언이설에 넘어가지 않은, 저 같은 신규 사용자를 현혹시키기 위해서는 더 많은 떡밥이 필요합니다. 그래서 바로 아래부터 Gmail만의 특장점 4가지를 더 보여줍니다. 여기에는 파란색 회원가입 버튼이 없지만 화면 오른쪽 상단에 파란색 'Create an account' 버튼이 계속 떠 있으니 괜찮습니다.

4가지 특장점을 보며 '흠, 괜찮은데...'라는 생각을 할 때 쯤, 바로 아래 화면에서 다시 한번 회원 가입을 유도합니다. 링크를 누르면 바로 Google 계정을 생성하는 화면이 시작됩니다.

어떤가요? 정말 간결한 플롯으로 구성되어 있지 않나요?

1번째 섹션에서는 'Gmail은 더 빠르고 쉽게 더 많은 일을 마칠 수 있게 도와줍니다.'라는 키 메시지를 전달합니다.
2번째 섹션에서는 'Gmail은 모든 기기에서 사용할 수 있어요.'라며 앱 다운로드 링크를 보여줍니다.
3번째 섹션에서는 '이런 편리한 기능들이 있어요. 어때요?'라며 추가적인 장점을 설명합니다.
4번째 섹션에서는 '지금 바로 시작하세요.'라고 말하며 회원가입을 유도합니다.

여러분들도 '한번쯤 써 봐야겠다'라는 생각이 드셨나요? Gmail의 훅을 보면 '메일 쓰는게 좀 편해지겠는데'라는 기대가 생기지 않으세요? 이렇게 서비스를 처음 접한 신규 사용자를 혹하게 만들어서 그 다음 단계인 체험의 단계로 넘어가게 만드는 신규 사용자 경험이 바로 훅입니다.

### 사례 연구, Tik Tok
짧은 동영상 서비스인 Tik Tok의 홈페이지를 살펴보겠습니다. 이 동영상을 보고 있으면 화면 중앙에 있는 Real Short Videos가 정확히 무슨 뜻인지는 몰라도 앱을 다운로드 받아서 써 봐야겠다라는 생각이 드시나요? 시선을 확 사로잡는 동영상으로 흥미를 유발시키네요.

### 이성적인 접근과 감성적인 접근
Gmail은 유틸리티 서비스이기 때문에 서비스가 제공하는 유용성, 즉 기능을 설명하는 이성적인 내용으로 훅을 구성했지만 틱톡과 같은 소셜 서비스나 게임은 주로 시선을 사로잡는 감성적인 이미지나 영상으로 훅을 구성합니다. 상품이나 서비스의 아하 모먼트를 전달하는데 가장 적합한 방법을 이용해야 합니다.

### 훅 & 체험 구조
대부분의 온라인 서비스의 신규 사용자 경험은 훅 & 체험 구조를 가집니다.

1. 훅: 신규 사용자를 사로잡아서 '한번 써 봐야지'라는 생각이 들게 만드는 UX
2. 체험: 신규 사용자가 실제 서비스를 이용하면서 아하 모먼트를 체험하게 만드는 UX

훅은 신규 사용자를 혹하게 만들어서 다음 단계인 체험으로 넘어가게 만드는 역할을 합니다. 지난 영상에서 다뤘던 WhatsApp의 NUX는 바로 체험 단계에 해당합니다. 많은 수의 신규 사용자가 홈페이지 방문 후에 체험 단계로 넘어가지 않고 떠나버리기 때문에 훅은 마치 휠체어가 잘 지나갈 수 있도록 계단에 경사로를 놓아주는 것과 같습니다.

#### 훅과 체험은 하나의 경험을 제공해야 한다.
여기서 주의할 점은 훅과 체험은 하나의 아하 모먼트를 전달하기 위해 하나의 사용자 경험으로 디자인되어야 한다는 것입니다. Gmail의 훅을 살펴보면 'Gmail은 더 빠르고 쉽게 더 많은 일을 마칠 수 있게 도와줍니다.'라는 키 메시지가 홈페이지 전체에 일관되게 흐르는 것을 볼 수 있습니다. 3번째 섹션에서 나열하는 기능들도 키 메시지를 강화하는 역할을 하는 기능들로만 구성되어 있습니다. 

Stay organized instantly
Never drop the ball
Take action right from the inbox
Avoid suspicisious emails

제가 생각하기에 Gmail의 아하 모먼트는 Gmail을 이용하다가 '더 빠르고 쉽게 더 많은 일을 마칠 수 있구나...'는 걸 깨닫는 순간일 겁니다. 만약 3번째 섹션에서 '경쟁 업체보다 더 많은 저장 공간을 드립니다.'라든가 '여러가지 extension으로 확장성이 뛰어납니다.' 또는 'Gmail 계정으로 다른 서비스에 소셜 로그인을 할 수 있어요' 등과 같은 기능들을 나열했다면 그건 키 메시지를 강화시키기 보다는 오히려 약화시켜서 훅의 역할을 망치는 결과를 가져왔을 겁니다.

또한 훅이 단순히 체험 단계로 넘어가게 만드는 역할에 그치지 않고 신규 사용자를 우리 고객으로 전환시키는 NUX의 부분이라는 점을 명심해야 합니다. 따라서 훅을 디자인할 때는 아하 모먼트를 간접적으로 체험할 수 있게 만들어야 하며 이를 통해 훅과 체험은 하나의 경험으로 이어지게 됩니다. Tik Tok 앱을 다운로드 받아서 실행해 보면 홈페이지에서 본 것과 같은 유형의 영상들이 쏟아집니다. 훅과 체험이 하나로 결함되어 완벽히 동일한 경험을 제공한다는 것을 확인할 수 있습니다.

#### 훅의 효과성 측정
<!--(퍼널 슬라이드 만들기)
(홈페이지 방문 > 홈페이지 살펴 보기 > 회원 가입 버튼 클릭 > 회원 가입 완료 > 이메일 수신 > 이메일 답신 (아하 모먼트, 가정)
-->

만약 훅에서 체험 단계로의 전환율을 높이기 위해 우리 서비스의 아하 모먼트가 아닌 낚시성 훅을 만들면 어떻게 될까요? 여러분이 낚여서 실망했던 수없이 많은 광고를 떠올려 봅시다. 신규 사용자가 훅을 보고 마음이 동해서 회원 가입을 한 후 서비스를 체험해 봤는데 만약 자신이 기대한 가치를 얻을 수 없다면 신규 사용자는 체험을 중단하고 이탈할 것입니다. 즉 신규 사용자가 '낚였네...'라는 생각이 들면 망하는 겁니다. 

훅에서 체험 단계로의 전환율을 높이기 위해 낚시성 훅을 디자인하면 훅 단계에서 체험 단계로 넘어가는 전환율은 높일 수 있지만 궁극적으로 전체 NUX 퍼널의 전환율은 높이기 힘들 겁니다. 많은 이들이 각 단계의 전환율에 집중하다가 전체 그림을 놓치는 실수를 범하곤 합니다. 체험 단계로의 전환율이 높아졌다고 해서 NUX 퍼널의 전환율이 높아진다는 것을 의미하지 않는다는 점을 명심하세요. 훅도 NUX의 일부이기 때문에 그 효과성은 NUX 퍼널의 전환율로 평가해야 합니다.  

## 이커머스
이커머스에서는 훅 다음에 체험이 오는 게 아니라 결제라는 훨씬 큰 허들, 아니 엄청난 벽이 서 있습니다. 신규 사용자 입장에서는 개인정보를 주는 정도가 아니라 자신이 애써 번 돈을 내야 하는거죠. 따라서 훅의 중요성이 더 클 수 밖에 없습니다.

### 실물 상품
실물 상품을 판매하는 이커머스의 경우에는 직접 상품을 받아서 사용해 봐야 아하 모먼트를 경험할 수 있습니다. 그렇다고 구매 전에 상품을 미리 줄 수는 없으니 결국 **아하 모먼트를 간접적으로 체험**할 수 있게 해줘야 구매가 일어납니다. 주로 상품 사진, 동영상, 사용 후기 등을 통해서 간접적인 경험을 제공합니다. 과거에는 예쁜 모델의 사진이 주를 이뤘다면 요즘은 일반인이나 MD들의 직접 체험 영상이나 얼굴을 제외한 컷 등을 많이 사용해서 제품 자체에 집중하게 합니다. 페이스북에서 체험 후기 형식의 동영상 광고가 많아진 것을 기억하실 겁니다. 여러분은 어떤 훅에 낚여서 구매를 하셨나요?

### 콘텐츠
콘텐츠의 경우에도 결제하기 전에 아하 모먼트!를 모두 다 경험하게 해 준다면 그 사업은 망하겠죠? 물론 오픈 소스나 크리에이티브 커먼즈에서는 기부라는 방식을 취하지만 일반적인 비즈니스의 형태는 아닙니다. 따라서 콘텐츠 또는 지식 서비스는, 결제 후에 아하 모먼트!를 경험하도록 해야 합니다. 그래서 영화 트레일러처럼 간접적으로나마 아하 모먼트를 체험할 수 있는 훅이 중요합니다. 헐리우드 영화의 트레일러는 전문 제작업체가 따로 만들만큼 영화의 흥행에 커다란 영향을 미칩니다.

온라인 음악 서비스가 대세가 되면서 사용자들은 첫 1분을 미리 듣기로 들어 보고 이 노래를 계속 들을지 말지 판단하게 되었습니다. 그러자 작곡가들은, 훅을 앞에 배치해서 미리 듣기 때 자신의 노래를 어필할 수 있도록 'Hook Song'이라는 새로운 작법을 만들어 냈습니다. 이것도 시장의 변화에 발 맞춰 대응한, NUX 디자인의 예입니다. 만화에서 일부만 보여 주고 결제를 유도하는 것도 마찬가지입니다. 성인 만화들의 배너 광고를 클릭해 보시면 무슨 말인지 이해할 수 있을 겁니다.

## 실습 과제
여러분이 운영하고 있는 서비스에서는 어떤 훅을 사용하고 있나요? Gmail의 훅처럼 간결한 플롯으로 이루어져 있나요? 아니면 Tik Tok처럼 신규 사용자를 사로잡는 감성적인 훅인가요? 현재 사용하는 훅이 신규 사용자들을 효과적으로 체험 단계로 유도하고 있나요? 지금 바로 확인해 보세요.

## Closing
이 영상이 도움이 되셨다면 좋아요와 구독 버튼을 눌러 주세요. 알람을 눌러두시면 제일 먼저 업데이트 소식을 받아 보실 수 있습니다.

그럼 다음 시간에 뵐게요.





<!--(광고) > (홈페이지 방문) > (회원 가입 버튼 클릭) > 상품 체험 (Trial)
(앱설치 유도 광고) > (앱스토어 페이지) > (다운로드 버튼 클릭) >

Gmail

(앱설치 유도 광고) > 앱스토어 > 다운로드 > 회원가입 > 메일 발송 > 메일 수신
-->



<!--회원 가입
체험 버전 신청

상대적으로 부담이 적게 만들어서 넘어가야 한다.
회원 가입 > 1달 무료 체험 (신용카드 없이) >  신용카드 번호만 받고 체험 > 무료 샘플 받기 > 제품 구매

상품이 매력적으로 보이게 하는 방법

팔리는 단어, 이미지를 만들어라.
혹해서 넘어가야 한다.

-->






