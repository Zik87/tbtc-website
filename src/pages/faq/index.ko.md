---
template: 'faq-page'
path: /faq
title: FAQ
questions:
  - question: tBTC는 어떻게 페그를 유지하나요?
    answer: >
      -	tBTC는 페그를 유지하는 것이 아닙니다. 이것은 공급이 페깅되는 것 이지 가격이 페깅되는 것이 아닙니다. 그렇기 때문에 탈중앙화 된 페깅 같은 알고리듬 구조가 필요 없습니다.
  - question: tBTC 가격은 왜 BTC 가격과 정확히 일치하지 않나요?
    answer: >
      -	tBTC 가격은 BTC의 가격 페깅이 아닌 공급 페깅입니다. 이는 BTC/tBTC 가격이 정확히 일치하지 않을 수 있다는 뜻입니다. tBTC 가격이 BTC가격에 비해 조금 비싸게 또는 싸게 거래될 수 있습니다. 
  - question: tBTC는 왜 현재의 ETH 비율로 담보를 잡고 있나요?
    answer: >
      -	더 안전한 시스템을 위함입니다. 이것은 디파이에서도 새로 시작하는 네트워크로서 매우 중요합니다. ETH가 더 안전한 담보인 이유는 ETH가 디파이의 표준이기 때문이며, KEEP 팀은 현재의 150% ETH/BTC 비율을 런칭 이후에 빠르게 135%까지 낮출 계획입니다. 또한 새로운 담보비율을 40%까지 낮출수 있는 메커니즘을 시험중입니다.
  - question: tBTC 시스템에는 어떤 위험이 있을까요?
    answer: >
      -	이 기술은 새로운 것이기 때문에 어떤 부분에서 잘못될지 예측할 수는 없습니다. 커뮤니티에서 찾은 몇가지 상황이 있습니다. 싸이너들이 만약에 공모하여 당신의 BTC을 훔쳐가면, 사용자는 tBTC를 받게 될것입니다. 이것이 ETH를 묶어 놓는 이유입니다. 만약에 ETH 가격이 짧은시간내에 크게 하락하고 동시에 모든 싸이너들이 도망가고 페깅이 깨지면, 시스템은 신쎄틱으로 돌아간다. 더 많은 정보는 <a href="https://docs.keep.network/tbtc/index.pdf" target="_blank">tBTC technical spec</a>을 봐주시기 바랍니다.
  - question: 왜 고정된 랏 사이즈가 있는건가요? 왜 랜덤이 아닌가요?
    answer: >
      너무 많은 종류의 랏 사이즈는 유동성 풀들에게 문제가 될 수 있습니다. 몇 개의 표준화된 랏 사이즈는 상환가능성을 높여줍니다.
  - question: 제 디파이 앱을 tBTC 발행과 상환에 직접 연결하게 해주는 위젯이 있나요?
    answer: >
      아직 없습니다. tBTC 발행과 상환을 댑에 적용하기 위한 통합 작업이 필요합니다. 해당 코딩은 오픈소스<a href="https://github.com/keep-network/tbtc.js" target="_blank">(tbtc.js GitHub)</a>이며, 개발자달은 그들의 제품에 맞는 인터페이스를 구축할 수 있습니다. 비트코인 트랜스액션을 검증하기 위해서, 가장좋은 방법은 개발이 편리한 electrum 서버를 운용하는 것입니다.
  - question: tBTC는 검증절차를 거쳤나요?
    answer: >
      -	Consensys Diligence 가 현재 6주간 암호기법 및 코드 검증을 진행중입니다. 결과는 검사가 끝난 이후 발표될 것입니다. 
  - question: tBTC 사이닝과 ETH 스테이킹으로 MSB가 될 수도 있나요?
    answer: >
      -	모든 사용자는 스스로 tBTC를 사용하는 것이 자신이 살고 있는 나라에서 법적으로 문제가 있는지 확인 하거나 정부 기관의 승인을 받아야 하는지 확인해야 합니다.
  - question: tBTC를 얻기 위해 BTC 예치를 하는 것은 과세 대상인가요?
    answer: >
      -	이것이 세금 이슈가 있는지는 스스로 세무사와 확인을 해봐야합니다. 한가지 고려해야 할 부분은 예치의 UTXO와 관련된 NFT입니다. 이 NFT는 예치된 BTC에게 수수료를 주게 해주고 6개월이내에 같은 UTXO를 상환할 수 있는 기능을 제공합니다.
  - question: tBTC의 사이너 그룹이 어떻게 BTC를 대리보관 하지 않나요?
    answer: >
      tBTC의 사이너 그룹은 비트코인의 멀티시그를 대체하는 한계 ECDSA를 이용합니다. 모든 입금마다 새로은 사이너 그룹이 선출(random beacon에 의해 선택)되고, 입금자를 위한 이더리움 체인에 기록된 비트코이 PKH 주소를 생성합니다.
  - question: 사이너는 누구입니까? 아무나 될 수 있나요?
    answer: >
      론칭 직후에는 약 80명의 KEEP 구매자와 몇몇 신뢰 업체들이 tBTC를 사이닝합니다. 빠른시간내에 더 많은 개인과 참여자들에게 이더 스테이킹을 통해 사이너게 될 기회를 공지할 예정입니다. 
  - question: 어떤점이 다른 비트코인을 이더리움에 올리는 프로제트보다 나은가요?
    answer: >
      일부 사람들은 tBTC가 여러가지 이유로 낫다고 믿습니다. 일부 프로젝트들은 제대로 된 브릿지라고 할 수 없는 가격 페깅을 구축하였습니다. 다른 프로제트들은 페깅을 제공하지만 중앙화된 기관이 발행과 한원 절차에 마찰을 발생 시킵니다. 그러므로 검열 방지 시스템이라 볼 수 없습니다. 새로운 브릿지들은 탈중앙화 페깅이지만 보안 모델이 불안전합니다. 이들은 ⅔의 정직함 예측에 기반하고, 예치금을 담보하는 ETH 또는 그외 추가 담보가 없으며, 피어 검토 기반의 t-ESDSA가 아닌 "당신의 개인 암호화폐를 이용하라"라는 새로운 이야기를 하고있습니다.
  - question: 6개월 수수료 기간을 무슨 뜻 인가요? BTC는 6개월이 지나야지만 환원 요청이 가능한가요?
    answer: >
      아닙니다. 특정 UTXO를 이용한 비트코인 환원이 아니라면 6개월 환원은 필요없습니다. 이것이 바로 NFT 영수증, 즉 TDT가 필요한 이유입니다. 대부분의 소매급 디파이 이용자는 신경쓸 필요 없으며, 6개월 후에 환원할 필요도 업습니다.
  - question: 다른 체인에 비트코인 브릿지를 구축할 계획 있나요?
    answer: >
      아직 확실한 계획은 없습니다. 하지만 href="https://www.crosschain.group/" target="_blank">Cross-Chain Group</a>은 이미 Cosmos, Zcash, and Polkadot과 비신뢰 브릿지 설계에 대해 이야기 하였습니다.
  - question: tBTC 보유로 거버넌스 권리가 생기나요?
    answer: >
      아니오.
  - question: 왜 그냥 가격 페깅을 하지 않나요?
    answer: >
      tBTC 개발팀은 가격 페깅이 아닌 공급 페깅을 구축하고 있습니다. 이것은 어떤 인조적인 방법이 아닙니다. 비트코인 보유자들은 가격이 얼마인지 보다는 비트코인을 돌려받을 수 있는지에 관심이 있습니다.
  - question: 왜 tBTC에는 가격 제공 오라클이 필요한가요?
    answer: >
      tBTC는 공모가 불가능한 익명의 참여자들이 필요한 사이드체인입니다. 현재로서는, 사이너 그룹의 잘못된 행동을 막는 것이 필요합니다. 가격 제공 오라클은 이 그룹의 BTC/ETH 가격을 유지하기 위해 필요합니다.
---