---
layout: default
title: "규칙"
last_update: 2019년 6월 6일
---

<section class="banner">
    <div class="container">
        <div class="content">
            <h1 class="title">규칙</h1>
            <h2 class="subtitle">마지막 업데이트: {{ page.last_update }}</h2>
        </div>
    </div>
</section>
<section class="info">
    <div class="alert alert-warning">
        <div class="container">
            <p>이 규칙은 아르카 네트워크 전체가 아닌 아케이드 내에서만 적용됩니다.</p>
        </div>
    </div>
</section>
<section class="content">
    <div class="container">
        <h2>가. 일반 규칙</h2>
        <div class="row">
            <div class="col-md-12">
                <ol>
                    <li>상대방을 존중하고 상식적으로 행동합니다.</li>
                    <li>같거나 비슷한 문자를 반복해서 입력하지 않습니다.</li>
                    <li>다음에 해당하는 링크를 게시하지 않습니다:</li>
                    <ol type="a">
                        <li>다른 사용자의 개인 정보가 포함된 사이트</li>
                        <li>광고가 포함된 사이트</li>
                        <li>음란물, 바이러스, 피싱 사이트, 혐오 단체 등을 포함하는 불쾌한 내용을 포함하는 사이트</li>
                    </ol>
                    <li>본 서비스에 대한 규칙 위반을 조장하거나 참여하지 않습니다.</li>
                    <li>관리자를 사칭하지 않습니다.</li>
                    <li>본 서비스의 이슈나 버그를 공개적으로 유포하거나 악용하지 않습니다. 버그를 발견한 경우 디스코드 <strong>{{ site.discord }}</strong>으로 제보해주십시오.</li>
                    <li>본 서비스의 관리자가 요청하는 모든 지시를 따릅니다. 만약 부당하다고 생각되는 경우 디스코드 <strong>{{ site.discord }}</strong>을 통해 항소할 수 있습니다.</li>
                </ol>
            </div>
        </div>
        <h2>나. 서버 상에서의 행위</h2>
        <div class="row">
            <div class="col-md-12">
                <ol>
                    <li>다른 플레이어에게 팀을 떠나거나 서버 접속 종료를 강요하는 채팅을 보내서는 안 됩니다.</li>
                    <li>다른 사람들에게 특정 플레이어를 신고하도록 조장해서는 안 됩니다.</li>
                    <li>공개 채팅에 아르카 네트워크 서비스의 일부가 아닌 서버를 입장하도록 권유하거나 링크를 걸어서는 안됩니다. (개인 채팅을 통한 공유는 가능합니다.)</li>
                    <span class="badge badge-warning">참고</span>
                    <small>모든 채팅 메시지는 기록됩니다.</small>
                    <br />
                    <span class="badge badge-warning">참고</span>
                    <small>스팸을 하지 않는 이상 본 서비스에 관련된 생방송이나 영상을 링크할 수 있습니다.</small>
                </ol>
            </div>
        </div>
        <h2>다. 일반 게임 진행</h2>
        <div class="row">
            <div class="col-md-12">
                <ol>
                    <li>플레이어는 맵에서 의도하지 않은 공간으로 이동하면 안 됩니다.</li>
                    <li>Blitz나 Ghost Squadron 경기에서 플레이어들은 의도적으로 전투를 회피하거나 접근이 어려운 특정한 위치에서 오랜 시간 동안 머무를 수 없습니다.</li>
                    <li>관전자는 경기에 영향을 주는 정보를 플레이어에게 전달하면 안 됩니다.</li>
                    <li>부적절한 스킨을 사용한 경우 스킨이 변경될 때까지 서버 이용이 제한됩니다.</li>
                </ol>
            </div>
        </div>
        <h2>라. 클라이언트 모드</h2>
        <div class="row">
            <div class="col-md-12">
                <ol>
                    <li>바닐라 Minecraft 사용자보다 불공정한 이점을 제공하는 클라이언트 수정은 게임을 진행하는 동안 허용되지 않습니다.</li>
                    <li>다음에 해당하는 모드는 게임을 진행하는 동안 명시적으로 허용됩니다.</li>
                    <ul>
                        <li>Optifine</li>
                        <li>ArmorStatusHUD / StatusEffectHUD</li>
                        <li>LabyMod (2.6 버전 이상)</li>
                        <li>Toggle Sneak / Sprint (LabyMod / HCF 버전)</li>
                    </ul>
                    <li>다음에 해당하는 모드는 게임을 진행하는 동안 명시적으로 금지됩니다.</li>
                    <ul>
                        <li>엑스레이</li>
                        <li>자동 공격 모드</li>
                        <li>에임봇</li>
                        <li>비행 모드</li>
                        <li>데미지 / 체력 표시기</li>
                        <li>인벤토리 분류기</li>
                        <li>자동 도구 선택기</li>
                        <li>스마트 무빙</li>
                        <li>Better Sprinting</li>
                        <li>플레이어의 이름 태그를 노출 혹은 확대시키는 모드</li>
                    </ul>
                    <li>리스트에 없는 다른 모드에 대해서는 사용하기 전에 확인을 위해 디스코드 <strong>{{ site.discord }}</strong>에 메시지를 보내주십시오.</li>
                    <span class="badge badge-warning">참고</span>
                    <small>명시적으로 허용되는 리스트에 있지 않는 이상 LabyMod를 통해 추가로 설치할 수 있는 모드는 허용되지 않습니다.</small>
                </ol>
            </div>
        </div>
        <h2>마. 팀 방해</h2>
        <div class="row">
            <div class="col-md-12">
                <ol>
                    <li>팀 방해는 금지되며 팀에게 해를 끼치는 무모하거나 의도적인 행동으로 정의됩니다.</li>
                    <li>다음에 해당하는 행위들은 명백한 팀 방해입니다:</li>
                    <ol type="a">
                        <li>팀 동료 또는 팀 핵심 시설(예: 상자, 방어물 또는 광석) 근처에 TNT를 배치 및 설정하는 행위</li>
                        <li>자신의 팀의 상자나 작업대를 파괴하는 행위</li>
                        <li>팀킬(사람 아래 블록을 제거하여 떨어지게 하거나 동료들을 세상 밖으로 밀어내는 행위)</li>
                        <li>명시적 허가 없이 다른 플레이어가 만든 TNT 대포를 사용 혹은 수정하는 행위</li>
                        <li>다른 팀원에게 지원 또는 협력하는 행위</li>
                        <li>승리 조건을 충족했음에도 불구하고 의도적으로 게임을 연장시키는 행위</li>
                    </ol>
                    <li>다음 행위는 무분별한 것으로 간주되며 강력하게 권장되지 않으며 어길 시 경고를 받을 수 있습니다.</li>
                    <ol type="a">
                        <li>자신의 기지에 TNT를 배치하거나 자신의 기지에 TNT 타워를 짓는 행위</li>
                        <li>동료 또는 목표물 근처에 보호되지 않은 TNT를 설치하는 행위</li>
                    </ol>
                    <li>그 행위가 고의가 아니었을지라도 자신의 팀이 경기에서 승리하는 것을 방해하는 모든 행위는 여전히 "팀 방해"로 간주되고 그에 따라 처벌을 받을 수 있습니다.</li>
                    <span class="badge badge-warning">참고</span>
                    <small>플레이어가 팀을 방해하는 행위는 <strong>절대로</strong> 허용되지 않습니다. 이는 다른 방해자에게 복수하는 행위도 포함됩니다.</small>
                </ol>
            </div>
        </div>
        <h2>사. 맵 특정 규칙</h2>
        <div class="row">
            <div class="col-md-12">
                <ol>
                    <li>모든 플레이어는 모든 맵 규칙을 숙지하는 것에 책임이 있습니다. 맵 규칙은 /map 명령어를 통해 찾을 수 있습니다.</li>
                    <li>/map에서의 규칙은 동일한 주제에 관한 경우 이 규정집보다 높은 우선순위를 가지고 있습니다.</li>
                </ol>
            </div>
        </div>
        <h2>아. 기타</h2>
        <div class="row">
            <div class="col-md-12">
                <ol>
                    <li>이 규칙들은 공지 후에 수정될 수 있습니다.</li>
                    <li>플레이어는 규칙 변경을 숙지하는 것에 대한 책임이 있습니다.</li>
                    <li>본 서비스 관리자는 사전 통지 없이 플레이어를 차단하거나 차단을 해제할 수 있는 권리를 가집니다.</li>
                </ol>
            </div>
        </div>
    </div>
</section>