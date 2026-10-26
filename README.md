[ai-interview.html.html](https://github.com/user-attachments/files/33942803/ai-interview.html.html)
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta http-equiv="Content-Style-Type" content="text/css">
  <title></title>
  <meta name="Generator" content="Cocoa HTML Writer">
  <meta name="CocoaVersion" content="2487.5">
  <style type="text/css">
    p.p1 {margin: 0.0px 0.0px 0.0px 0.0px; font: 15.0px '.SF NS'; color: #000000; color: rgba(0, 0, 0, 0.9); -webkit-text-stroke: rgba(0, 0, 0, 0.9); background-color: #ffffff}
    p.p2 {margin: 0.0px 0.0px 0.0px 0.0px; font: 15.0px '.SF NS'; color: #000000; color: rgba(0, 0, 0, 0.9); -webkit-text-stroke: rgba(0, 0, 0, 0.9); background-color: #ffffff; min-height: 18.0px}
    span.s1 {font-kerning: none}
  </style>
</head>
<body>
<p class="p1"><span class="s1"><b>&lt;!DOCTYPE html&gt;</b></span></p>
<p class="p1"><span class="s1"><b>&lt;html lang="zh-CN"&gt;</b></span></p>
<p class="p1"><span class="s1"><b>&lt;head&gt;</b></span></p>
<p class="p1"><span class="s1"><b>&lt;meta charset="UTF-8"&gt;</b></span></p>
<p class="p1"><span class="s1"><b>&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</b></span></p>
<p class="p1"><span class="s1"><b>&lt;title&gt;校招模拟面试 · AI 面试官&lt;/title&gt;</b></span></p>
<p class="p1"><span class="s1"><b>&lt;style&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>:root{</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>--bg:#f5f7fb; --card:#ffffff; --primary:#2563eb; --primary-dark:#1e40af;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>--accent:#f59e0b; --text:#1f2937; --muted:#6b7280; --border:#e5e7eb;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>--green:#10b981; --red:#ef4444;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>*{box-sizing:border-box;margin:0;padding:0}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>body{font-family:"PingFang SC","Microsoft YaHei",sans-serif;background:var(--bg);color:var(--text);min-height:100vh}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.wrap{max-width:860px;margin:0 auto;padding:24px 16px 60px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>header{text-align:center;margin-bottom:20px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>header h1{font-size:24px;color:var(--primary-dark)}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>header p{color:var(--muted);font-size:14px;margin-top:6px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.card{background:var(--card);border-radius:14px;box-shadow:0 2px 10px rgba(0,0,0,.06);padding:24px;margin-bottom:18px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.step-tag{display:inline-block;background:#eef2ff;color:var(--primary);font-size:12px;padding:3px 10px;border-radius:999px;margin-bottom:10px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>h2{font-size:18px;margin-bottom:14px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>label{display:block;font-size:14px;font-weight:600;margin:12px 0 6px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>input[type=text],textarea{width:100%;border:1px solid var(--border);border-radius:8px;padding:10px 12px;font-size:14px;font-family:inherit;outline:none}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>input:focus,textarea:focus{border-color:var(--primary)}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>textarea{resize:vertical;min-height:70px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.hint{font-size:12px;color:var(--muted);margin-top:4px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>button{background:var(--primary);color:#fff;border:none;border-radius:8px;padding:12px 28px;font-size:15px;cursor:pointer;font-family:inherit}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>button:hover{background:var(--primary-dark)}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>button:disabled{background:#c7d2fe;cursor:not-allowed}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.btn-ghost{background:#fff;color:var(--primary);border:1px solid var(--primary)}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.btn-ghost:hover{background:#eef2ff}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.hidden{display:none!important}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>#chatBox{height:420px;overflow-y:auto;border:1px solid var(--border);border-radius:10px;padding:16px;background:#fafbff;display:flex;flex-direction:column;gap:12px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.msg{max-width:82%;padding:11px 14px;border-radius:12px;font-size:14px;line-height:1.6;white-space:pre-wrap}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.msg.ai{background:#eef2ff;border-top-left-radius:4px;align-self:flex-start}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.msg.user{background:var(--primary);color:#fff;border-top-right-radius:4px;align-self:flex-end}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.msg .who{font-size:11px;opacity:.7;display:block;margin-bottom:4px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.reply-row{display:flex;gap:10px;margin-top:14px;align-items:flex-end}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.reply-row textarea{flex:1;min-height:60px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.mic-btn{width:60px;height:60px;border-radius:50%;padding:0;font-size:24px;flex-shrink:0;position:relative}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.mic-btn.rec{background:var(--red);animation:pulse 1.2s infinite}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>@keyframes pulse{0%{box-shadow:0 0 0 0 rgba(239,68,68,.5)}70%{box-shadow:0 0 0 14px rgba(239,68,68,0)}100%{box-shadow:0 0 0 0 rgba(239,68,68,0)}}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.voice-status{font-size:12px;color:var(--muted);margin-top:6px;min-height:16px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.tts-row{display:flex;align-items:center;gap:8px;margin-top:8px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.tts-row label{margin:0;font-weight:400;font-size:13px;color:var(--muted)}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.tipbar{background:#fffbeb;border:1px solid #fde68a;border-radius:8px;padding:10px 14px;font-size:13px;color:#92400e;margin-bottom:12px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.timer{font-size:13px;color:var(--muted);text-align:right;margin-bottom:8px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.score-big{font-size:42px;font-weight:700;color:var(--primary);text-align:center;margin:8px 0}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.dim-row{display:flex;align-items:center;gap:10px;margin:10px 0}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.dim-row .name{width:110px;font-size:13px;font-weight:600}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.bar{flex:1;height:10px;background:#eef2ff;border-radius:999px;overflow:hidden}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.bar i{display:block;height:100%;background:var(--primary);border-radius:999px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.dim-row .val{width:40px;text-align:right;font-size:13px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.fb{font-size:13px;color:var(--muted);margin:2px 0 12px 120px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.good{color:var(--green);font-weight:600}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.bad{color:var(--red);font-weight:600}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.quote{background:#f9fafb;border-left:3px solid var(--primary);padding:8px 12px;font-size:13px;color:#374151;margin:6px 0 14px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.actions{text-align:center;margin-top:18px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.guide-table{width:100%;border-collapse:collapse;font-size:13px;margin-top:10px}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.guide-table th,.guide-table td{border:1px solid var(--border);padding:8px 10px;text-align:left;vertical-align:top}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.guide-table th{background:#f3f4f6}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>.footer-note{font-size:12px;color:var(--muted);text-align:center;margin-top:24px}</b></span></p>
<p class="p1"><span class="s1"><b>&lt;/style&gt;</b></span></p>
<p class="p1"><span class="s1"><b>&lt;/head&gt;</b></span></p>
<p class="p1"><span class="s1"><b>&lt;body&gt;</b></span></p>
<p class="p1"><span class="s1"><b>&lt;div class="wrap"&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>&lt;header&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;h1&gt;🎙️ 校招一对一模拟面试 · AI 面试官&lt;/h1&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;p&gt;环节目标：完整表达简历基本信息 + 凸显个人特点 | 预计用时 8–10 分钟&lt;/p&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>&lt;/header&gt;</b></span></p>
<p class="p2"><span class="s1"><b></b></span><br></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>&lt;!-- 步骤1：准备 --&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>&lt;div id="step1" class="card"&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;span class="step-tag"&gt;第 1 步 · 面试准备&lt;/span&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;h2&gt;请在面试开始前填写你的「虚拟简历」&lt;/h2&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;p class="hint"&gt;就像真实面试一样：面试官会围绕你填写的内容提问。信息越真实，练习越有效。&lt;/p&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;label&gt;姓名&lt;/label&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;input id="fName" type="text" placeholder="例如：张小明"&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;label&gt;学校 &amp; 专业 &amp; 年级&lt;/label&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;input id="fSchool" type="text" placeholder="例如：华东师范大学 · 软件工程 · 大四"&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;label&gt;应聘岗位&lt;/label&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;input id="fRole" type="text" placeholder="例如：前端开发工程师"&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;label&gt;实习 / 项目经历（简述 1–2 段）&lt;/label&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;textarea id="fExp" placeholder="例如：在 XX 公司实习 3 个月，负责后台管理系统的组件开发；校内完成过校园二手交易平台项目…"&gt;&lt;/textarea&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;label&gt;一段最能代表你的经历 / 特点（加分项素材）&lt;/label&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;textarea id="fTrait" placeholder="例如：担任辩论队队长，带队拿到校级冠军；坚持写技术博客 2 年…"&gt;&lt;/textarea&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;div class="actions"&gt;&lt;button id="startBtn"&gt;开始面试 →&lt;/button&gt;&lt;/div&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>&lt;/div&gt;</b></span></p>
<p class="p2"><span class="s1"><b></b></span><br></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>&lt;!-- 步骤2：面试中 --&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>&lt;div id="step2" class="card hidden"&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;span class="step-tag"&gt;第 2 步 · 面试进行中&lt;/span&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;div class="tipbar" id="tipBar"&gt;💡 提示：这一题考察的是——&lt;/div&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;div class="timer"&gt;已用时 &lt;span id="clock"&gt;0:00&lt;/span&gt;&lt;/div&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;div id="chatBox"&gt;&lt;/div&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;div class="voice-status" id="voiceStatus"&gt;&lt;/div&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;div class="reply-row"&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>&lt;textarea id="userInput" placeholder="点击右侧 🎤 开始语音回答，或直接在此输入文字…（建议 30–90 秒的口语化表达）"&gt;&lt;/textarea&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>&lt;button id="micBtn" class="mic-btn" title="点击开始/停止语音输入"&gt;🎤&lt;/button&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>&lt;button id="sendBtn"&gt;发送&lt;/button&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;/div&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;div class="tts-row"&gt;&lt;input type="checkbox" id="ttsToggle" checked&gt;&lt;label for="ttsToggle"&gt;AI 面试官朗读问题（语音合成）&lt;/label&gt;&lt;/div&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>&lt;/div&gt;</b></span></p>
<p class="p2"><span class="s1"><b></b></span><br></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>&lt;!-- 步骤3：报告 --&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>&lt;div id="step3" class="card hidden"&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;span class="step-tag"&gt;第 3 步 · 面试评估报告&lt;/span&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;h2&gt;你的表现报告&lt;/h2&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;div class="score-big" id="totalScore"&gt;–&lt;/div&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;div id="dimReport"&gt;&lt;/div&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;div id="answerReview"&gt;&lt;/div&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;div class="actions"&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>&lt;button class="btn-ghost" onclick="location.reload()"&gt;再练一次&lt;/button&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>&lt;button id="showGuide" class="btn-ghost"&gt;查看面试官使用指南&lt;/button&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;/div&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>&lt;/div&gt;</b></span></p>
<p class="p2"><span class="s1"><b></b></span><br></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>&lt;!-- 步骤4：老师指南 --&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>&lt;div id="step4" class="card hidden"&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;span class="step-tag"&gt;附 · 面试官（老师/组织者）使用指南&lt;/span&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;h2&gt;环节设计与使用说明&lt;/h2&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;table class="guide-table"&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>&lt;tr&gt;&lt;th style="width:90px"&gt;阶段&lt;/th&gt;&lt;th&gt;内容与目的&lt;/th&gt;&lt;/tr&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>&lt;tr&gt;&lt;td&gt;破冰 (1min)&lt;/td&gt;&lt;td&gt;问候、缓解紧张，明确流程（共 5 问，每问 1–2 分钟）。&lt;/td&gt;&lt;/tr&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>&lt;tr&gt;&lt;td&gt;基本信息 (2min)&lt;/td&gt;&lt;td&gt;考察 Q1「自我介绍」：学校/专业/年级/岗位是否说清，条理是否清晰。&lt;/td&gt;&lt;/tr&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>&lt;tr&gt;&lt;td&gt;简历深挖 (3min)&lt;/td&gt;&lt;td&gt;考察 Q2–Q3：实习/项目细节。能否讲出「做了什么→怎么做的→结果如何」。&lt;/td&gt;&lt;/tr&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>&lt;tr&gt;&lt;td&gt;个人特点 (3min)&lt;/td&gt;&lt;td&gt;考察 Q4–Q5：用具体事例证明性格特点与岗位匹配度，避免空话。&lt;/td&gt;&lt;/tr&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>&lt;tr&gt;&lt;td&gt;反馈 (2min)&lt;/td&gt;&lt;td&gt;AI 输出四维评估报告，师生共同复盘。&lt;/td&gt;&lt;/tr&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;/table&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;h2 style="margin-top:20px"&gt;评分维度（各 25 分，满分 100）&lt;/h2&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;table class="guide-table"&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>&lt;tr&gt;&lt;th&gt;维度&lt;/th&gt;&lt;th&gt;加分表现&lt;/th&gt;&lt;th&gt;常见扣分点&lt;/th&gt;&lt;/tr&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>&lt;tr&gt;&lt;td&gt;信息完整&lt;/td&gt;&lt;td&gt;姓名、学校专业年级、应聘岗位、关键经历一项不落&lt;/td&gt;&lt;td&gt;漏说岗位；只报姓名就结束&lt;/td&gt;&lt;/tr&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>&lt;tr&gt;&lt;td&gt;条理结构&lt;/td&gt;&lt;td&gt;有结构（如"基本信息→经历→特点→求职意向"），分点表达&lt;/td&gt;&lt;td&gt;想到哪说到哪、重复绕圈&lt;/td&gt;&lt;/tr&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>&lt;tr&gt;&lt;td&gt;事例具体&lt;/td&gt;&lt;td&gt;有时间、有数字、有结果（STAR 法）&lt;/td&gt;&lt;td&gt;只说"我参与了…""我负责…"没有细节&lt;/td&gt;&lt;/tr&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>&lt;tr&gt;&lt;td&gt;特点匹配&lt;/td&gt;&lt;td&gt;特点 + 具体事例 + 与岗位的关联&lt;/td&gt;&lt;td&gt;空喊"我抗压能力强"却举不出例子&lt;/td&gt;&lt;/tr&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;/table&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;p class="hint" style="margin-top:12px"&gt;使用建议：① 组织者提前收简历，重点词填入第 1 步；② 可投屏全班观看一位同学面试，其余同学用评分表打分；③ 结束后对照报告做 5 分钟小组复盘。&lt;/p&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>&lt;div class="actions"&gt;&lt;button class="btn-ghost" onclick="location.reload()"&gt;关闭指南&lt;/button&gt;&lt;/div&gt;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>&lt;/div&gt;</b></span></p>
<p class="p2"><span class="s1"><b></b></span><br></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>&lt;p class="footer-note"&gt;校招互动环节 · AI 面试官模拟器（本页面为本地规则引擎演示版，可接入大模型 API 获得更真实的追问）&lt;/p&gt;</b></span></p>
<p class="p1"><span class="s1"><b>&lt;/div&gt;</b></span></p>
<p class="p2"><span class="s1"><b></b></span><br></p>
<p class="p1"><span class="s1"><b>&lt;script&gt;</b></span></p>
<p class="p1"><span class="s1"><b>const QUESTIONS = [</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>{ q:()=&gt;`你好，欢迎参加今天的面试！我是本场的 AI 面试官。面试大约 10 分钟，包含 5 个问题，不用紧张，把真实的自己展现出来就好。\n\n第一个问题：请先做一个 1 分钟左右的自我介绍，让我们认识一下你。`,</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>tip:"考察点：简历基本信息 + 表达条理", key:"q1",</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>eval:(a,f)=&gt;{ let pts=[],sc=0;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>const hit=[["姓名",f.name,()=&gt;hasAny(a,f.name)],["学校/专业",f.school,()=&gt;containsAny(a,splitWords(f.school))],["应聘岗位",f.role,()=&gt;containsAny(a,splitWords(f.role))],["经历",f.exp,()=&gt;a.length&gt;=60]];</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>hit.forEach(([n,,fn])=&gt;{ if(fn()){sc+=10;pts.push('&lt;span class="good"&gt;✓&lt;/span&gt; 提到了'+n)} else pts.push('&lt;span class="bad"&gt;✗&lt;/span&gt; 缺少「'+n+'」') });</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>if(a.length&gt;=120){sc+=5;pts.push('&lt;span class="good"&gt;✓&lt;/span&gt; 篇幅充实')}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>else pts.push('&lt;span class="bad"&gt;✗&lt;/span&gt; 内容偏少，建议加入一段关键经历');</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>return {score:Math.min(sc,25),pts}; } },</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>{ q:(f)=&gt;`好的，谢谢你。我注意到你填写了这段经历：「${f.exp.slice(0,60)}${f.exp.length&gt;60?"…":""}」。\n\n请具体讲一讲：在这段实习/项目中，你&lt;b&gt;做了什么、遇到了什么困难、最后的结果如何&lt;/b&gt;？`,</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>tip:"考察点：简历深挖——用 STAR 法讲具体细节", key:"q2",</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>eval:(a)=&gt;{ let sc=10,pts=[];</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>if(/\d/.test(a)){sc+=8;pts.push('&lt;span class="good"&gt;✓&lt;/span&gt; 包含数字，很有说服力')} else pts.push('&lt;span class="bad"&gt;✗&lt;/span&gt; 没有量化结果，建议补充数字');</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>if(/困难|问题|挑战|卡|难点|坑/.test(a)){sc+=4;pts.push('&lt;span class="good"&gt;✓&lt;/span&gt; 提到了遇到的困难')}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>else pts.push('&lt;span class="bad"&gt;✗&lt;/span&gt; 未提及困难与解决过程');</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>if(/结果|最终|完成|上线|落地|收到|效果|成绩/.test(a)){sc+=3;pts.push('&lt;span class="good"&gt;✓&lt;/span&gt; 有交代结果')}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>else pts.push('&lt;span class="bad"&gt;✗&lt;/span&gt; 缺少结果收尾');</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>return {score:Math.min(sc,25),pts}; } },</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>{ q:()=&gt;`听起来是一次不错的经历。接下来换个角度：你觉得这段经历&lt;b&gt;让你最大的成长或收获是什么&lt;/b&gt;？它为什么对你重要？`,</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>tip:"考察点：反思总结能力——从经历中提炼成长", key:"q3",</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>eval:(a)=&gt;{ let sc=12,pts=[];</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>if(a.length&gt;=50){sc+=8;pts.push('&lt;span class="good"&gt;✓&lt;/span&gt; 展开充分')} else pts.push('&lt;span class="bad"&gt;✗&lt;/span&gt; 表达过于简短');</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>if(/学会|成长|收获|提升|明白了|认识到|更/.test(a)){sc+=5;pts.push('&lt;span class="good"&gt;✓&lt;/span&gt; 有明确的成长提炼')} else pts.push('&lt;span class="bad"&gt;✗&lt;/span&gt; 没有提炼出具体成长点');</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>return {score:Math.min(sc,25),pts}; } },</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>{ q:(f)=&gt;`嗯，我了解你的经历了。现在想更认识「你这个人」：请用&lt;b&gt;一个词形容你自己&lt;/b&gt;，并举一个真实的事例来证明，最后说说这个特点为什么适合你应聘的「${f.role}」岗位。`,</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>tip:"考察点：个人特点 + 事例支撑 + 岗位匹配（黄金三段式）", key:"q4",</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>eval:(a,f)=&gt;{ let sc=0,pts=[];</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>if(/我觉得我|我是一个|我比较|我属于|坚韧|细心|踏实|开朗|认真|执行|负责|好奇|耐心|合作|沟通|抗/.test(a)){sc+=6;pts.push('&lt;span class="good"&gt;✓&lt;/span&gt; 给出了明确的性格词')}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>else pts.push('&lt;span class="bad"&gt;✗&lt;/span&gt; 缺少明确的性格关键词');</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>if(a.length&gt;=80||/比如|例如|有一次|当时|记得/.test(a)){sc+=10;pts.push('&lt;span class="good"&gt;✓&lt;/span&gt; 用具体事例支撑了特点')} else pts.push('&lt;span class="bad"&gt;✗&lt;/span&gt; 没有具体事例——空话是最常见的扣分点');</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>if(containsAny(a,splitWords(f.role))||/岗位|这份工作|这个职位|适合/.test(a)){sc+=9;pts.push('&lt;span class="good"&gt;✓&lt;/span&gt; 把特点和岗位做了关联')}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>else pts.push('&lt;span class="bad"&gt;✗&lt;/span&gt; 未与应聘岗位建立联系');</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>return {score:Math.min(sc,25),pts}; } },</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>{ q:()=&gt;`最后一个问题：如果用 30 秒向 HR 推荐自己，你会怎么说？请给出一个&lt;b&gt;简短有力的结尾版自我介绍&lt;/b&gt;（为什么你值得一个 offer）。`,</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>tip:"考察点：个人特点总结 + 求职意愿表达", key:"q5",</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>eval:(a)=&gt;{ let sc=10,pts=[];</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>if(a.length&gt;=40){sc+=5;pts.push('&lt;span class="good"&gt;✓&lt;/span&gt; 有实质内容')}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>if(/经验|能力|学习|热情|匹配|胜任|相信|希望|期待/.test(a)){sc+=6;pts.push('&lt;span class="good"&gt;✓&lt;/span&gt; 表达了意愿与自信')}</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>else pts.push('&lt;span class="bad"&gt;✗&lt;/span&gt; 意愿表达不充分');</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>if(/因为|所以|因此|这让|正因/.test(a)){sc+=4;pts.push('&lt;span class="good"&gt;✓&lt;/span&gt; 有逻辑连接，说服力更强')} else pts.push('&lt;span class="bad"&gt;✗&lt;/span&gt; 逻辑感偏弱');</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>return {score:Math.min(sc,25),pts}; } },</b></span></p>
<p class="p1"><span class="s1"><b>];</b></span></p>
<p class="p1"><span class="s1"><b>function hasAny(s,sub){ return sub &amp;&amp; s.includes(sub.trim()); }</b></span></p>
<p class="p1"><span class="s1"><b>function splitWords(s){ return (s||"").split(/[·,，、\s/]+/).filter(w=&gt;w.length&gt;=2); }</b></span></p>
<p class="p1"><span class="s1"><b>function containsAny(s,words){ return words.some(w=&gt;s.includes(w)); }</b></span></p>
<p class="p2"><span class="s1"><b></b></span><br></p>
<p class="p1"><span class="s1"><b>let formData, qIndex=0, answers={}, startT, timerId, tipSeq=0;</b></span></p>
<p class="p2"><span class="s1"><b></b></span><br></p>
<p class="p1"><span class="s1"><b>function addMsg(role,html){ const d=document.createElement("div"); d.className="msg "+role; d.innerHTML=(role==="ai"?"&lt;span class='who'&gt;AI 面试官&lt;/span&gt;":"&lt;span class='who'&gt;我&lt;/span&gt;")+html; document.getElementById("chatBox").appendChild(d); document.getElementById("chatBox").scrollTop=1e9; }</b></span></p>
<p class="p2"><span class="s1"><b></b></span><br></p>
<p class="p1"><span class="s1"><b>document.getElementById("startBtn").onclick=()=&gt;{</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>const g=id=&gt;document.getElementById(id).value.trim();</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>formData={name:g("fName"),school:g("fSchool"),role:g("fRole"),exp:g("fExp"),trait:g("fTrait")};</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>if(!formData.name||!formData.role){ alert("请至少填写姓名和应聘岗位"); return; }</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>document.getElementById("step1").classList.add("hidden");</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>document.getElementById("step2").classList.remove("hidden");</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>qIndex=0; startT=Date.now();</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>timerId=setInterval(()=&gt;{ const s=Math.floor((Date.now()-startT)/1000); document.getElementById("clock").textContent=Math.floor(s/60)+":"+String(s%60).padStart(2,"0"); },1000);</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>addMsg("ai",QUESTIONS[0].q(formData));</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>document.getElementById("tipBar").textContent="💡 "+QUESTIONS[0].tip;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>setTimeout(()=&gt;document.getElementById("userInput").focus(),100);</b></span></p>
<p class="p1"><span class="s1"><b>};</b></span></p>
<p class="p2"><span class="s1"><b></b></span><br></p>
<p class="p1"><span class="s1"><b>document.getElementById("sendBtn").onclick=()=&gt;{</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>const ta=document.getElementById("userInput"); const a=ta.value.trim();</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>if(!a){ return; }</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>ta.value=""; addMsg("user",escapeHtml(a));</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>answers[QUESTIONS[qIndex].key]=a;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>qIndex++;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>if(qIndex&lt;QUESTIONS.length){</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>const q=QUESTIONS[qIndex];</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>setTimeout(()=&gt;{ addMsg("ai",q.q(formData)); document.getElementById("tipBar").textContent="💡 "+q.tip; document.getElementById("userInput").focus(); },600);</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>} else { finish(); }</b></span></p>
<p class="p1"><span class="s1"><b>};</b></span></p>
<p class="p1"><span class="s1"><b>function escapeHtml(s){ return s.replace(/&amp;/g,"&amp;amp;").replace(/&lt;/g,"&amp;lt;"); }</b></span></p>
<p class="p2"><span class="s1"><b></b></span><br></p>
<p class="p1"><span class="s1"><b>function finish(){</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>clearInterval(timerId);</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>document.getElementById("step2").classList.add("hidden");</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>document.getElementById("step3").classList.remove("hidden");</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>const map=[["信息完整性","q1","自我介绍是否说清姓名/学校/岗位/经历"],["简历深挖（STAR）","q2","事例是否具体、有数字、有结果"],["反思与成长","q3","能否从经历中提炼成长"],["特点与岗位匹配","q4","是否特点+事例+岗位关联"],["收尾说服力","q5","30 秒推荐是否简洁有力"]];</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>let total=0, dimHtml="", review="";</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>map.forEach(([n,k,desc])=&gt;{ const q=QUESTIONS.find(x=&gt;x.key===k); const r=q.eval(answers[k]||"",formData);</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>total+=r.score;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>dimHtml+=`&lt;div class="dim-row"&gt;&lt;span class="name"&gt;${n}&lt;/span&gt;&lt;div class="bar"&gt;&lt;i style="width:${r.score/25*100}%"&gt;&lt;/i&gt;&lt;/div&gt;&lt;span class="val"&gt;${r.score}/25&lt;/span&gt;&lt;/div&gt;`;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>review+=`&lt;h2 style="margin-top:18px"&gt;Q：${desc}&lt;/h2&gt;&lt;div class="quote"&gt;你的回答：「${escapeHtml((answers[k]||"").slice(0,120))}${(answers[k]||"").length&gt;120?"…":""}」&lt;/div&gt;&lt;p class="fb"&gt;${r.pts.join("&lt;br&gt;")}&lt;/p&gt;`; });</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>document.getElementById("totalScore").textContent=total+" / 100";</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>document.getElementById("dimReport").innerHTML=dimHtml;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>document.getElementById("answerReview").innerHTML=review;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>document.getElementById("step3").scrollIntoView({behavior:"smooth"});</b></span></p>
<p class="p1"><span class="s1"><b>}</b></span></p>
<p class="p1"><span class="s1"><b>document.getElementById("showGuide").onclick=()=&gt;{</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>document.getElementById("step3").classList.add("hidden");</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>document.getElementById("step4").classList.remove("hidden");</b></span></p>
<p class="p1"><span class="s1"><b>};</b></span></p>
<p class="p1"><span class="s1"><b>document.getElementById("userInput").addEventListener("keydown",e=&gt;{ if(e.key==="Enter"&amp;&amp;!e.shiftKey){e.preventDefault();document.getElementById("sendBtn").click();} });</b></span></p>
<p class="p2"><span class="s1"><b></b></span><br></p>
<p class="p1"><span class="s1"><b>/* ===== 语音输入（Web Speech API）===== */</b></span></p>
<p class="p1"><span class="s1"><b>const SR=window.SpeechRecognition||window.webkitSpeechRecognition;</b></span></p>
<p class="p1"><span class="s1"><b>const micBtn=document.getElementById("micBtn"), voiceStatus=document.getElementById("voiceStatus");</b></span></p>
<p class="p1"><span class="s1"><b>let recog=null, listening=false, baseText="";</b></span></p>
<p class="p1"><span class="s1"><b>if(SR){</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>recog=new SR();</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>recog.lang="zh-CN"; recog.continuous=true; recog.interimResults=true;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>recog.onstart=()=&gt;{ listening=true; micBtn.classList.add("rec"); micBtn.textContent="⏹"; voiceStatus.textContent="🎙️ 正在聆听，请开始回答…"; };</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>recog.onend=()=&gt;{ listening=false; micBtn.classList.remove("rec"); micBtn.textContent="🎤"; if(voiceStatus.textContent.includes("聆听")) voiceStatus.textContent=""; };</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>recog.onerror=(e)=&gt;{ if(e.error==="not-allowed"){ voiceStatus.textContent="⚠️ 无法访问麦克风，请在浏览器设置中允许麦克风权限（或改用键盘输入）。"; } else if(e.error==="no-speech"){ voiceStatus.textContent="⚠️ 未检测到语音，请再试一次。"; } };</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>recog.onresult=(e)=&gt;{ let interim="";</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>for(let i=e.resultIndex;i&lt;e.results.length;i++){ const t=e.results[i][0].transcript;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">      </span>if(e.results[i].isFinal){ baseText=(baseText?baseText:"")+t; } else interim+=t; }</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>document.getElementById("userInput").value=(baseText+interim).trim(); };</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>micBtn.onclick=()=&gt;{ if(listening){ recog.stop(); return; }</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>baseText=document.getElementById("userInput").value?document.getElementById("userInput").value+" ":"";</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">    </span>try{ recog.start(); }catch(err){} };</b></span></p>
<p class="p1"><span class="s1"><b>}else{</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>micBtn.disabled=true; micBtn.textContent="🚫"; micBtn.title="当前浏览器不支持语音识别";</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>voiceStatus.textContent="⚠️ 当前浏览器不支持语音识别，请使用 Chrome/Edge，或改用键盘输入。";</b></span></p>
<p class="p1"><span class="s1"><b>}</b></span></p>
<p class="p2"><span class="s1"><b></b></span><br></p>
<p class="p1"><span class="s1"><b>/* ===== AI 语音合成朗读 ===== */</b></span></p>
<p class="p1"><span class="s1"><b>function speak(text){</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>if(!document.getElementById("ttsToggle").checked||!window.speechSynthesis) return;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>window.speechSynthesis.cancel();</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>const plain=text.replace(/&lt;[^&gt;]+&gt;/g,"");</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>const u=new SpeechSynthesisUtterance(plain); u.lang="zh-CN"; u.rate=1;</b></span></p>
<p class="p1"><span class="s1"><b><span class="Apple-converted-space">  </span>window.speechSynthesis.speak(u);</b></span></p>
<p class="p1"><span class="s1"><b>}</b></span></p>
<p class="p1"><span class="s1"><b>const _addMsg=addMsg;</b></span></p>
<p class="p1"><span class="s1"><b>addMsg=function(role,html){ _addMsg(role,html); if(role==="ai"&amp;&amp;document.getElementById("step2")&amp;&amp;!document.getElementById("step2").classList.contains("hidden")) speak(html); };</b></span></p>
<p class="p1"><span class="s1"><b>&lt;/script&gt;</b></span></p>
<p class="p1"><span class="s1"><b>&lt;/body&gt;</b></span></p>
<p class="p1"><span class="s1"><b>&lt;/html&gt;</b></span></p>
</body>
</html>
