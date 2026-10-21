index.html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>捡手机</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,sans-serif}
body{background:#222;padding:20px;display:flex;justify-content:center;min-height:100vh}
.phone{width:375px;height:780px;background:#000;border-radius:48px;padding:12px;overflow:hidden;position:relative;box-shadow:0 0 30px #0008}
.screen{width:100%;height:100%;border-radius:36px;overflow:hidden;position:relative}

/* 状态栏通用 */
.status{height:48px;display:flex;justify-content:space-between;align-items:center;padding:0 24px;font-size:15px;font-weight:600;position:absolute;top:0;width:100%;z-index:9;color:#fff}

/* ========== 锁屏页面 ========== */
#lockScreen{position:absolute;inset:0;background:linear-gradient(160deg,#2c3e70,#7a4b8f,#d67c96);display:flex;flex-direction:column;align-items:center;padding-top:90px;color:white;transition:opacity .4s}
.lock-time{font-size:72px;font-weight:300;letter-spacing:-2px}
.lock-date{font-size:18px;margin-top:6px;opacity:0.9}
.notice{margin-top:40px;width:90%;background:#ffffff25;border-radius:20px;padding:16px;backdrop-filter:blur(10px)}
.notice h3{font-size:17px;margin-bottom:8px}
.notice-item{display:flex;justify-content:space-between;align-items:center;padding:8px 0;border-bottom:1px solid #ffffff22;font-size:15px}
.notice-item:last-child{border-bottom:none}
.unlock-btn{margin-top:auto;margin-bottom:60px;padding:12px 36px;border:none;border-radius:30px;background:#ffffff35;color:#fff;font-size:17px;cursor:pointer;backdrop-filter:blur(10px)}

/* ========== 主菜单（联系人列表） ========== */
#homeScreen{position:absolute;inset:0;background:#f2f2f7;display:none;flex-direction:column}
.home-header{height:52px;background:#e9e9eb;display:flex;align-items:center;justify-content:center;font-size:18px;font-weight:600;border-bottom:1px solid #d1d1d6}
.contact-list{flex:1;overflow-y:auto;padding:8px}
.contact{display:flex;align-items:center;gap:14px;padding:14px 12px;border-bottom:1px solid #e4e4e9;cursor:pointer;background:#fff;border-radius:14px;margin-bottom:6px}
.avatar{width:46px;height:46px;border-radius:50%;background:#88a0c8;color:white;display:flex;align-items:center;justify-content:center;font-size:18px;font-weight:bold}
.contact-info{flex:1}
.contact-name{font-size:17px;font-weight:500}
.contact-preview{font-size:14px;color:#8e8e93;margin-top:2px}
.contact-time{font-size:13px;color:#8e8e93}
.back-home{margin-top:10px;padding:8px 16px;border:none;background:#007aff;color:white;border-radius:20px;cursor:pointer;font-size:15px}

/* ========== 聊天页面 ========== */
#chatScreen{position:absolute;inset:0;background:#f5f5f7;display:none;flex-direction:column}
.chat-header{height:52px;background:#e9e9eb;display:flex;align-items:center;justify-content:center;font-weight:600;font-size:17px;border-bottom:1px solid #d2d2d7}
.chat-box{flex:1;padding:14px;overflow-y:auto;display:flex;flex-direction:column}
.msg{max-width:72%;margin:6px 0;padding:10px 13px;border-radius:19px;font-size:16px;line-height:1.45}
.left{background:#e5e5ea;align-self:flex-start;border-bottom-left-radius:5px}
.right{background:#007aff;color:white;margin-left:auto;border-bottom-right-radius:5px}
.send-bar{height:54px;background:#e9e9eb;display:flex;align-items:center;padding:0 10px;gap:8px;border-top:1px solid #d2d2d7}
.send-bar input{flex:1;border-radius:22px;border:none;padding:9px 15px;font-size:16px;outline:none}
</style>
</head>
<body>
<div class="phone">
  <div class="screen">

    <!-- 锁屏页 -->
    <div id="lockScreen">
      <div class="status">
        <span>9:41</span>
        <span>📶 🔋</span>
      </div>
      <div class="lock-time">21:37</div>
      <div class="lock-date">10月21日 星期三</div>
      <div class="notice">
        <h3>通知</h3>
        <div class="notice-item"><span>妈妈</span><span>未接来电</span></div>
        <div class="notice-item"><span>好友A</span><span>你看到消息了吗</span></div>
      </div>
      <button class="unlock-btn" onclick="unlock()">滑动/点击解锁</button>
    </div>

    <!-- 主菜单 联系人列表 -->
    <div id="homeScreen">
      <div class="status" style="color:#000">
        <span>21:37</span>
        <span>📶 🔋</span>
      </div>
      <div class="home-header">信息</div>
      <div class="contact-list">
        <!-- 联系人入口，想加联系人就复制这一整块 -->
        <div class="contact" onclick="openChat()">
          <div class="avatar">莱恩</div>
          <div class="contact-info">
            <div class="contact-name">莱恩</div>
            <div class="contact-preview">你看到消息了吗</div>
          </div>
          <div class="contact-time">21:20</div>
        </div>
        <div class="contact" onclick="openChat()">
          <div class="avatar">阿什</div>
          <div class="contact-info">
            <div class="contact-name">阿什</div>
            <div class="contact-preview">记得早点回家</div>
          </div>
          <div class="contact-time">20:45</div>
        </div>
      </div>
    </div>

    <!-- 聊天页 -->
    <div id="chatScreen">
      <div class="status" style="color:#000">
        <span>21:37</span>
        <span>📶 🔋</span>
      </div>
      <div class="chat-header">小绿</div>
      <div class="chat-box">
        <!-- ✏️ 在这里修改对话！left=对方，right=本机主人 -->
        <div class="msg left">人类，你今天去哪里了？</div>
        <div class="msg right">刚去沙漠远行，才看到消息</div>
        <div class="msg left">什么时候有空见一面吗</div>
        <div class="msg right">找我什么事？不是忘了我吗</div>
      </div>
      <div class="send-bar">
        <input placeholder="iMessage">
      </div>
      <div style="text-align:center;padding-bottom:10px">
        <button class="back-home" onclick="backHome()">返回信息列表</button>
      </div>
    </div>

  </div>
</div>

<script>
// 解锁：锁屏隐藏，显示联系人主页
function unlock(){
  document.getElementById('lockScreen').style.display='none';
  document.getElementById('homeScreen').style.display='flex';
}
// 打开聊天
function openChat(){
  document.getElementById('homeScreen').style.display='none';
  document.getElementById('chatScreen').style.display='flex';
}
// 返回主页
function backHome(){
  document.getElementById('chatScreen').style.display='none';
  document.getElementById('homeScreen').style.display='flex';
}
</script>
</body>
</html>
