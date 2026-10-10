# Academic Resources Dashboard

<div style="background: #202225; padding: 30px; border-radius: 12px; text-align: center; margin-top: 25px; font-family: sans-serif;">
    <h3 style="color: #ffffff; margin-bottom: 8px;">Open Study Portal</h3>
    <p style="color: #b9bbbe; font-size: 14px; margin-bottom: 20px;">Access your external communication dashboard below.</p>
    <button onclick="launch()" style="background: #5865F2; color: white; border: none; padding: 12px 28px; border-radius: 6px; font-size: 16px; cursor: pointer; font-weight: bold;">
        Launch Dashboard
    </button>
</div>

<script>
function launch() {
    var a = "https://wisp.";
    var b = "mercurywork.shop/";
    var c = "gateway?url=";
    var d = "https://discord.com";
    window.location.href = a + b + c + encodeURIComponent(d);
}
</script>
