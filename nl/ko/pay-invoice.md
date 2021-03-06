---

copyright:

  years: 1994, 2019

lastupdated: "2019-02-25"

keywords: credit card, payment information, payment method changes

subcollection: customer-portal

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:note: .note}
{:screen: .screen}
{:new_window: target="_blank"}


# 결제하기
{: #cp_makepayment}

송장에서 결제 정보까지 모든 {{site.data.keyword.Bluemix}} 인프라 청구 세부사항은 고객 포털에 안전하게 저장됩니다. 결제 방법이 변경되거나 신용카드가 취소 또는 만료되는 경우 결제 정보를 업데이트하여 연체료가 청구되지 않도록 하십시오.
{:shortdesc}

## 송장 보기
{: #cp_viewinvoice}

송장 창에서 각 개별 송장은 송장 번호, 날짜, 송장 유형 및 여러 통화 잔액으로 요약됩니다. 송장의 유형은 다음과 같습니다.

<dl>
<dt>새로 작성</dt>
<dd>일련의 반복 송장에서 첫 번째 송장입니다.</dd>
<dt>매월 자동 청구</dt>
<dd>1개월을 초과하여 계정에서 활성화된 반복 비용에 대한 송장입니다.</dd>
<dt>일회성 비용</dt>
<dd>다양한 지출에 대한 일회성 비용입니다(초과가 포함될 수 있음).</dd>
<dt>크레딧</dt>
<dd>계정 잔액에 대한 {{site.data.keyword.BluSoftlayer_notm}}의 크레딧입니다.</dd>
<dt>환불</dt>
<dd>일회성 또는 반복 비용에 대한 비용의 환입입니다.</dd>
</dl>

다음 정보를 포함한 계정에 대한 청구 요약을 볼 수도 있습니다.
  * 현재 및 결제 후 예상 잔액
  * 결제 방법
  * 마지막 및 다음 매월 자동 청구 송장 날짜

1. 메뉴에서 **계정** > **청구** > **송장**을 클릭하십시오.
2. 고객 포털에서 송장을 보거나 송장을 다운로드할 수 있습니다.

고객 포털에서 송장을 보는 경우 청구 항목의 항목별 목록이 선택된 송장에 대해 표시됩니다. 청구 항목의 행에서 임의의 위치를 클릭하여 청구에 대한 추가 항목별 세부사항을 보십시오. 송장을 다운로드한 경우 브라우저 설정에 따라 송장을 볼 수 있습니다. 다운로드한 송장은 각 청구 항목에 대한 항목별 요약 및 항목별 세부 청구를 모두 제공합니다.

미국 이외의 지역에 있는 경우에는 [송장](http://www.ibm.com/support/customer/invoices){: new_window} ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")이라는 도구를 사용하여 송장을 확인하십시오. 각 국가에 대한 특정 단계는 [https://www.ibm.com/support/customer/zz/en/selectcountrylang_invoices.html](https://www.ibm.com/support/customer/zz/en/selectcountrylang_invoices.html){: new_window} ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")에 나열되어 있습니다. 문제가 있는 경우 1-866-325-0045로 연락하여 송장에 대한 액세스를 요청하십시오.
{: note}

## 청구 방법 추가
{: #cp_billpay}

각 SoftLayer 계정은 매월 송장 금액에 대해 자동으로 청구되는 파일의 신용카드가 필요합니다. 이 정보는 연체료가 청구되지 않도록 항상 최신 상태로 유지되어야 합니다. 결제 정보가 항상 정확하도록 언제든지 업데이트할 수 있습니다. 파일의 신용카드 정보가 올바르지만 대체 결제 양식을 현재 잔액에 적용하려는 경우 [청구 항목 관리](/docs/customer-portal?topic=customer-portal-manage-billing#manage-billing)를 참조하십시오. 고객 포털에서 계정에 대한 결제 방법을 추가하려면 다음 단계를 수행하십시오.

1. 메뉴에서 **계정** > **청구** > **결제 방법**을 클릭하십시오.
2. **청구 주소** 섹션의 각 필드에 카드의 필수 청구 세부사항을 입력하십시오.
> **참고:** **카드 정보 사용** 선택란을 클릭하여 {{site.data.keyword.BluSoftlayer_notm}} 인프라가 계정에 대한 파일에 보유한 회사 정보로 필드를 자동으로 완료하십시오.
3. **결제 정보** 섹션의 각 필드에 신용카드 정보를 입력하십시오.
4. **신용카드 추가**를 클릭하여 월별 결제 방법으로 신용카드를 추가하십시오.
5. 선택적으로, 유럽의 지원 팀이 유지보수 및 지원 문제를 처리하도록 하려면 **EU 지원**을 선택하십시오.  이 옵션에 대한 자세한 정보는 [유럽 지원 옵션 설정](/docs/customer-portal?topic=customer-portal-cp_seteusupported#cp_seteusupported)을 참조하십시오.

결제 방법을 추가한 후 카드의 유효성을 보장하기 위해 SoftLayer 계정 담당자가 요청을 처리합니다. 유효성 검증된 카드는 24시간 내에 계정에 사용할 수 있습니다. 결제 방법의 상태가 변경되면 결제 방법을 추가할 때 제공된 연락처로 이메일이 전송됩니다.

## 일회성 결제
{: #cp-one-payment}

PayPal 계정 또는 주요 신용카드를 사용하여 일회성 결제를 할 수 있고 전체 또는 부분 잔액을 결제할 수 있습니다. 일회성 결제 세부사항은 향후 사용을 위해 기록되지 않고 계정에 대한 현재 월별 결제 방법을 수정하지 않습니다.

1. 고객 포털에서 일회성 결제 페이지로 이동하십시오.
 * 메뉴에서: **계정** > **결제**를 클릭하십시오.
 * 송장 페이지에서: **잔액 결제**를 클릭하십시오.
2. **결제 금액** 필드에 결제 금액을 입력하십시오.
3. PayPal을 사용하여 결제하는 경우 **PayPal**을 클릭하고 PayPal의 프롬프트를 따라 결제를 완료하십시오. 추가 조치가 필요하지 않습니다. 신용카드로 결제하는 경우 해당 필드에 **카드번호, 만기 날짜 및 보안 코드**를 입력하십시오.
4. **신용카드 청구 주소** 섹션의 해당 필드에 청구 정보를 입력하십시오.
5. 선택적으로, 유럽의 지원 팀이 유지보수 및 지원 문제를 처리하도록 하려면 **EU 지원**을 선택하십시오.  이 옵션에 대한 자세한 정보는 [유럽 지원 옵션 설정](/docs/customer-portal?topic=customer-portal-cp_seteusupported#cp_seteusupported)을 참조하십시오.
6. **신용카드로 결제**를 클릭하여 결제를 시작하십시오.

결제를 시작하면 결제가 처리됩니다. 결제 관련 문제가 발생하는 경우 문제가 해결될 때까지 {{site.data.keyword.BluSoftlayer_notm}} 인프라 또는 PayPal의 프롬프트를 따르십시오. 결제가 처리됩니다. 금액이 적용되며 현재 잔액이 업데이트됩니다.
