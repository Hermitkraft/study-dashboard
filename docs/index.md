# Academic Resources Dashboard

<div style="background: #202225; padding: 30px; border-radius: 12px; text-align: center; margin-top: 25px; box-shadow: 0 4px 15px rgba(0,0,0,0.2); font-family: sans-serif;">
    <h3 style="color: #ffffff; margin-bottom: 8px; font-size: 20px;">Launch Discord Web Client</h3>
    <p style="color: #b9bbbe; font-size: 14px; margin-bottom: 20px;">Secure tunnel routed via community network nodes.</p>
    <button onclick="launchProxy('https://discord.com')" style="background: #5865F2; color: white; border: none; padding: 12px 28px; border-radius: 6px; font-size: 16px; cursor: pointer; font-weight: bold; transition: background 0.2s;">
        Open Discord
    </button>
</div>

<script>
function launchProxy(targetUrl) {
    const proxyBackend = 'https://mercurywork.shop';
    window.location.href = proxyBackend + 'gateway?url=' + encodeURIComponent(targetUrl);
}
</script>
