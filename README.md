index.html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>捡手机</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,sans-serif}
body{background:#eee;padding:20px;display:flex;justify-content:center}
.phone{width:375px;height:700px;background:#000;border-radius:40px;padding:12px;overflow:hidden;position:relative}
.screen{width:100%;height:100%;background:#f5f5f7;border-radius:30px;overflow:hidden;display:flex;flex-direction:column}
.status{height:44px;background:#f5f5f7;display:flex;justify-content:space-between;align-items:center;padding:0 22px;font-size:14px;font-weight:500}
.chat-header{height:52px;background:#e9e9eb;display:flex;align-items:center;justify-content:center;font-weight:500;font-size:17px;border-bottom:1px solid #d2d2d7}
.chat-box{flex:1;padding:12px;overflow-y:auto;background:#f5f5f7}
.msg{max-width:70%;margin:6px 0;padding:9px 12px;border-radius:18px;font-size:16px;line-height:1.4}
.left{background:#e5e5ea;align-self:flex-start;border-bottom-left-radius:4px}
.right{background:#007aff;color:white;margin-left:auto;border-bottom-right-radius:4px}
.send-bar{height:50px;background:#e9e9eb;display:flex;align-items:center;padding:0 10px;gap:8px;border-top:1px solid #d2d2d7}
.send-bar input{flex:1;border-radius:20px;border:none;padding:8px 14px;font-size:16px;outline:none}
</style>
</head>
<body>
<div class="phone">
  <div class="screen">
    <div class="status">
      <span>9:41</span>
      <span>●●●</span>
    </div>
    <div class="chat-header">角色A</div>
    <div class="chat-box">
      <!-- ==========在这里改对话！========== -->
      <div class="msg left">你今天去哪里了？</div>
      <div class="msg right">刚忙完，才看到消息</div>
      <div class="msg left">什么时候有空见一面吗</div>
      <div class="msg right">等这阵子忙完吧</div>
      <!-- 想多加消息，就复制上面一行<div class="msg xxx">内容</div> -->
    </div>
    <div class="send-bar">
      <input placeholder="iMessage">
    </div>
  </div>
</div>
</body>
</html>
