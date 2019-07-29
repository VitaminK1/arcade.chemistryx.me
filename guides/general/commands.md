---
layout: default
title: 명령어 목록
---

<section class="banner">
    <div class="container">
        <div class="content">
            <h1 class="title">{{ page.title }}</h1>
            <h2 class="subtitle">인게임에서 사용할 수 있는 명령어 목록입니다.</h2>
        </div>
        </div>
    </div>
</section>
<section class="content">
    <div class="container">
        <h2>명령어 목록</h2>
        <ul>
            <li><b>/join</b> - 빈 자리가 하나 이상인 경우 팀에 참여합니다.</li>
            <ul>
                <li><b>/join [팀 이름]</b> - 이 기능은 프리미엄 랭크 및 관리자에게 제공됩니다.</li>
            </ul>
            <li><b>/leave</b> - 관전자로 이동합니다.</li>
            <li><b>/myteam</b> - 현재 속한 팀이 어디인지 확인합니다.</li>
            <li><b>/toggle [설정]</b> - 이 명령어로 설정할 수 있는 기능들이 여러가지 있습니다:</li>
            <ul>
                <li>Tips - 채팅에 표시되는 팁을 설정합니다.</li>
                <li>Scoreboard - 화면 오른쪽에 표시되는 스코어보드를 설정합니다.</li>
                <li>DeathMessages - 채팅에 표시되는 자신의 죽음 메시지를 설정합니다. (자신 또는 모두)</li>
                <li>HighlightDeathMessages - 자신의 죽음 메시지를 강조합니다.</li>
                <li>Blood - 타격 시 출혈 효과를 보여줍니다.</li>
                <li>Sounds - 사용자 지정 소리 재생 여부를 설정합니다.</li>
                <li>JoinMessages - 현재 접속중인 서버에서 볼 수 있는 참여 메시지를 설정합니다. (없음 또는 모두)</li>
                <li>PrivateMessageSounds - 귓속말을 받을 때 나는 소리 여부를 설정합니다.</li>
                <li>PrivateMessages - 귓속말을 받을지 여부를 설정합니다. (없음 또는 모두)</li>
                <li>Observers - 경기가 시작되기 전과 끝날 때 다른 관전자들을 볼 수 있는지 여부를 설정합니다.</li>
            </ul>
            <li><b>/settings [페이지]</b> - 위 설정들의 목록을 출력합니다.</li>
            <li><b>/set [설정 이름] [값]</b> - 지정된 설정을 지정된 값으로 설정합니다.</li>
            <li><b>/setting [설정]</b> - 지정된 설정의 값을 확인합니다.</li>
            <li><b>/report [이름] [사유]</b> - 규칙을 위반한 플레이어를 관리자에게 알릴 때 사용합니다.</li>
            <li><b>/coin [이름]</b> - 다른 사람의 코인 개수를 확인합니다.</li>
            <ul>
                <li><b>/coin</b> - 자신의 코인 개수를 확인합니다.</li>
            </ul>
            <li><b>/g [메시지]</b> - 서버에 있는 모든 사람들에게 메시지를 보낼 때 사용합니다.</li>
            <ul>
                <li><b>/g</b> - 기본 채팅 채널을 전체 채팅으로 설정합니다.</li>
            </ul>
            <li><b>/t [메시지]</b> - 팀의 모든 사람에게 메시지를 보낼 때 사용합니다.</li>
            <ul>
                <li><b>/t</b> - 기본 채팅 채널을 팀 채팅으로 설정합니다.</li>
            </ul>
            <li><b>/msg [이름] [메시지]</b> - 다른 사람에게 귓속말을 보내는 데 사용합니다.</li>
            <li><b>/r [메시지]</b> - 마지막으로 귓속말을 보낸 사람에게 답장합니다.</li>
            <li><b>/match</b> - 현재 경기 정보를 표시합니다.</li>
            <li><b>/map</b> - 현재 맵의 정보를 표시합니다.</li>
            <ul>
                <li><b>/map [맵 이름]</b> - 특정 맵의 정보를 표시합니다.</li>
            </ul>
            <li><b>/nextmap</b> 혹은 <b>/nm</b> - 현재 경기 이후에 진행될 맵을 표시합니다.</li>
            <li><b>/rot [페이지]</b> - 현재 서버의 맵 로테이션을 표시합니다.</li>
            <li><b>/maps [페이지]</b> - 현재 서버에 로드된 맵의 목록을 표시합니다.</li>
        </ul>
    </div>
</section>