---
layout: post
title: ��תBootstrap-����
tags:
- ժ��Ľ����
- html
- css
- Bootstrap
description: Bootstrap html css
---
<div id="js-aticle-container" class="cwrap-autoheight aticle-container" style="width: 400px;">
    <div class="code-panel" id="J_PanelCode">
        <h2 class="code-head" id="J_CodeLang" data-lang="HTML">
            ���⣨һ��
        </h2>
        <div class="code-description" id="J_CodeDescr">
            <div class="code-desc co">
                <p>
                    <span style="font-size: 13px; line-height: 1.6em;">Bootstrap����ͨ��HTMLҳ��һ����������ⶼ��ʹ�ñ�ǩ&lt;h1&gt;��&lt;h6&gt;,ֻ����Bootstrap��������Ĭ�ϵ���ʽ��ʹ�������������������ʾ��Ч��һ�������嶨��Ĺ���������±���ʾ��</span>
                </p>
                <p>
                    <span style="font-size: 13px; line-height: 1.6em;"><a href="http://img.mukewang.com/53acce330001429807730337.jpg"><img alt="" src="http://img.mukewang.com/53acce330001429807730337.jpg" style="width: 350px;"></a></span>
                </p>
                <p>
                    ͨ���ȽϿ��Է��֣�Bootstrap������ʽ�����������������Ż����ã�
                </p>
                <p>
                    1������������<strong>margin-top</strong>��<strong>margin-bottom</strong>��ֵ�� &nbsp;<strong>h1~h3</strong>���ú��ֵ����<strong>20px</strong>��<strong>h4~h6</strong>���ú��ֵ����<strong>10px��</strong><br>
                    2�����б�����и߶���<strong>1.1</strong>��Ҳ����font-size��1.1����,�����ı���ɫ�����嶼�̳и�Ԫ�ص���ɫ�����塣<br>
                    3���̶���ͬ������������С��<strong>h1=36px��h2=30px��h3=24px��h4=18px��h5=14px</strong>��<strong>h6=12px��</strong>
                </p>
                <p>
                    ����ľ������÷ǳ��򵥣�������ƽʱ������һ���ģ�ʹ��&lt;h1&gt;~&lt;h6&gt;��ǩ���ֱ��ʾ����һ����������h ���������Խ�󣬱�ʾ����ԽС���ı�ҲԽС������һ���򵥵�Ч�����Ҳ����༭���е�10-16�еĴ��롣
                </p>
                <p>
                    ��Bootstrap��Ϊ���÷Ǳ���Ԫ�غͱ���ʹ����ͬ����ʽ�������ⶨ����<strong>.h1~.h6</strong>����������<strong>���Ҳ����༭���� &nbsp; 18-23�д�����ʾ��</strong>
                </p>
                <p>
                    <span style="font-size: 13px; line-height: 1.6em;">�Ա�����ʾ����Ч��ͼ������˵���ǵ�Ч����һģһ���ġ�</span>
                </p>
                <p>
                    &nbsp;
                </p>
            </div>
        </div>
    </div>
</div>
<div id="js-aticle-container" class="cwrap-autoheight aticle-container" style="width: 400px;">
    <div class="code-panel" id="J_PanelCode">
        <h2 class="code-head" id="J_CodeLang" data-lang="HTML">
            ���⣨����
        </h2>
        <div class="code-description" id="J_CodeDescr">
            <div class="code-desc co">
                <p>
                    <span style="line-height: 1.6em;">����֮�⣬������Web�������У�������������һ��������������һ��С�ĸ����⡣��Bootstrap����Ҳ�����������Ű�Ч����ʹ����</span><strong style="line-height: 1.6em;">&lt;small&gt;</strong><span style="line-height: 1.6em;">��ǩ�����������⡣���������������Լ���һЩ������ʽ��</span>
                </p>
                <p>
                    <strong>1��</strong>�и߶���<strong>1</strong>������<strong>font-weight</strong>������<strong>normal</strong>����˳���Ч�������Ӵ֣���ͬʱ��ɫ������Ϊ<strong>��ɫ��#999����</strong><br>
                    <strong>2��</strong>����<strong>&lt;small&gt;</strong>�ڵ��ı�������<strong>h1~h3</strong>�ڣ����С������Ϊ��ǰ�ֺŵ�<strong>65%��</strong>����<strong>h4~h6</strong>�ڵ��ֺŶ�����Ϊ��ǰ�ֺŵ�<strong>75%��</strong><br>
                    ��ϸ���������<strong>bootstrap.css</strong>�ļ��е�<strong>407��~��443</strong>�С�
                </p>
                <pre class="code">
						h1 small,
				        .h1 small,
				        h2 small,
				        .h2 small,
				        h3 small,
				        .h3 small,
				        h1 .small,
				        .h1 .small,
				        h2 .small,
				        .h2 .small,
				        h3 .small,
				        .h3 .small {
				          font-size: 65%;
				        }
				        h4,
				        .h4,
				        h5,
				        .h5,
				        h6,
				        .h6 {
				          margin-top: 10px;
				          margin-bottom: 10px;
				        }
				        h4 small,
				        .h4 small,
				        h5 small,
				        .h5 small,
				        h6 small,
				        .h6 small,
				        h4 .small,
				        .h4 .small,
				        h5 .small,
				        .h5 .small,
				        h6 .small,
				        .h6 .small {
				          font-size: 75%;
				        }
				        
				</pre>
                <p>
                    ���򵥿���ʹ�÷���������Ч����<strong>�������ʾ��</strong>
                    <h1>Bootstrap����һ<small>���Ǹ�����</small></h1>
					<h2>Bootstrap�����<small>���Ǹ�����</small></h2>
					<h3>Bootstrap������<small>���Ǹ�����</small></h3>
					<h4>Bootstrap������<small>���Ǹ�����</small></h4>
					<h5>Bootstrap������<small>���Ǹ�����</small></h5>
					<h6>Bootstrap������<small>���Ǹ�����</small></h6>
                </p>
            </div>
        </div>
    </div>
</div>
