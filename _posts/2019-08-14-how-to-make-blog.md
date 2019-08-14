---
title: "Jekyll로 초간단! 블로그 만들기 (minimal mistakes)"
date: 2019-03-13 08:26:28 -0400
categories: jekyll
---

<div>
    <p> 
        <small>미뤄왔던 블로그를 만들었다!<br/>
            Jekyll로 만들면 10분도 안걸리는 것을...이렇게 질질 끌어오다니!<br/>
            이제부터라도 성실하게! 포스팅하자!
        </small><br/><br/><br/><br/>
        <h3>1. github 계정만들기 </h3><br/>
        <small>
            먼저, <a href="https://github.com">[Githup]</a> 계정을 만들어보자!<br/><br/>
        </small>
        <h3>2. 새로운 저장소 생성 (Create Repository)</h3><br/>
        <small>그런 후, 새로운 repository를 생성하자!</small><br/>
    </p>
    <img src="https://user-images.githubusercontent.com/49894861/62998171-9fb79280-bea5-11e9-8a2f-aa057382a848.png" alt="new repository"/>
    <p>
        <small>
            본인의 아이디와 똑같은 이름.github.io로 해야한다! <br/>
            사진 속에서는 아이디는 "2myemy"이라면 "2myemy.github.io" 로! <br/>
                <small>
                    이거슨 추후에 블로그 주소가 된다!<br/>
                    (사진 속 repository 이름이 _2myemy.github.io인 것은 무시하자! 언더바는 필요없다!)
                </small> <br/><br/>
        </small>
        <h3>3. Jekyll 테마 고르기</h3><br/>
        <small>
            이제 jekyll 테마를 골라보자! <br/><br/>
            <a href="http://jekyllthemes.org/">http://jekyllthemes.org/</a> <br/>
            이 곳에서 테마를 고를 수 있다.
            나는 minimal mistake로 하기로 했다.<br/>
            문서도 보기쉽게 정리되어 있고, 무엇보다 가장 큰 이유는 ....<br/>
            <a href="https://dreamgonfly.github.io/2018/01/27/jekyll-remote-theme.html">https://dreamgonfly.github.io/2018/01/27/jekyll-remote-theme.html</a><br/>
            이렇게 지킬로 블로그를 만드는 정말 초!간!단!한 방법을 포스팅해주셨기 때문!<br/>
            <small>(사실 이 포스팅을 보기 전엔 ruby설치하고 난리났었다...)</small><br/><br/><br/>
            이제 minimal-mistakes theme 저장소(repository)로 들어간다<br/>
            <a href="https://github.com/mmistakes/minimal-mistakes"> https://github.com/mmistakes/minimal-mistakes </a>
        </small>
    </p>
    <img src="https://user-images.githubusercontent.com/49894861/63000547-659dbf00-beac-11e9-8fb8-eaaf79ac2b65.png" />
    <p><small>다음과 같은 창이 뜰 것 이다!</small><br/><br/>
        <h3>4. _config.yml 파일 수정하기</h3><br/>
        <small>_config.yml 파일을 열어보자</small><br/>
    </p>
    <img src="https://user-images.githubusercontent.com/49894861/63000560-69314600-beac-11e9-9b6e-b0f08a751d59.png" />
    <p>
        <small>
            이 파일을 내 repository에 베껴올 것 이다. <br/>
            내 repository(저장소)에도 똑같은 이름의 파일을 생성해주고, minimal mistake 저장소에서 베껴온 _config.yml을 그대로 복붙해준다<br/><br/><br/>
            그런 후에 _config.yml파일에 이 문장을 추가해주자.<br/>
        </small>
    </p>
    <pre><small>remote_theme : mmistakes/minimal-mistakes </small></pre>
    <p><small>그리고 <pre>url : "https://YOURNAME.github.io"</pre> 로 바꾸어 준다</small><br/></p>
    <img src="https://user-images.githubusercontent.com/49894861/63001477-a8609680-beae-11e9-9591-63775dc52401.png" />
    <h3><br/><br/>5. index.html 파일 추가하기</h3><br/>
    <p><small>이제 minimal mistakes 저장소에서 index.html파일을 내 저장소에 그대로 복붙해온다</small></p>
    <img src="https://user-images.githubusercontent.com/49894861/63000565-6afb0980-beac-11e9-8ae7-8f523d94e5ae.png" />
    <p><small>그런 다음, https://YOURNAME.github.io로 들어가서 확인해보면 블로그가 생성되어 있을 것 이다!<br/>
        블로그에 포스팅하는 방법이나, 메뉴(navigation)를 만드는 방법은 다음 게시물에 포스팅 할 예정입니다! :)
    </small></p>

</div>
