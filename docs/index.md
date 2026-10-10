# Academic Resources Dashboard

<div style="background: #202225; padding: 30px; border-radius: 12px; text-align: center; margin-top: 25px; font-family: sans-serif;">
    <h3 style="color: #ffffff; margin-bottom: 8px;">Launch Discord Web Client</h3>
    <p style="color: #b9bbbe; font-size: 14px; margin-bottom: 20px;">Secure tunnel routed via community network nodes.</p>
    <button onclick="launch()" style="background: #5865F2; color: white; border: none; padding: 12px 28px; border-radius: 6px; font-size: 16px; cursor: pointer; font-weight: bold;">
        Open Discord
    </button>
</div>

<!-- We inject the required proxy bundle files straight from an un-truncated alternative source -->
<script src="https://cloudflare.com"></script>

<script>
function launch() {
    // This connects directly to the public web proxy tunnel gateway
    const gatewayServer = 'https://mercurywork.shop';
    const targetDestination = encodeURIComponent('https://discord.com');
    window.location.href = gatewayServer + targetDestination;
}
</script>
